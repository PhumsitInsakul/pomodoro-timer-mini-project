# pomodoro-timer-mini-project (TokyoTech leave)
# ผมได้ส่งใบลาใน Teams เรียบร้อยครับ

1) อธิบายตัวงาน pomodoro timer:
-index.html:
ไฟล์นี้เป็นโครงสร้าง HTML หลักของหน้าเว็บแสดงตัวจับเวลาแบบ Pomodoro
  - <head>: มีข้อมูล meta และลิงก์ไปยังแหล่งข้อมูลภายนอกด้วย link
    - <meta name="Viewport" content="width=device-width, initial-scale=1.0" />: กำหนดพอร์ตตัวแสดงสำหรับการออกแบบตอบสนอง
    - <title>Pomodoro Timer</title>: กำหนดชื่อหน้าเว็บ
    - <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />: นำเข้า icon- Font Awesome
    - <link href="https://fonts.googleapis.com/css2?family=Lora:wght@400;600&display=swap" rel="stylesheet" />: นำเข้า font- "Lora" จาก Google Fonts
    - <link rel="stylesheet" href="style.css" />: นำเข้าไฟล์ CSS 
  - <body>: มีเนื้อหาที่แสดงบนหน้าเว็บ
    - ปุ่ม  Focus, Short Break และ Long Break
    - แสดงตัวจับเวลา
    - ปุ่ม  Start, Pause และ Reset
  - <script src="script.js"></script>: ลิงก์ไปยังไฟล์ JavaScript 

-style.css:
ไฟล์นี้ช้ในการสร้างรูปแบบของการแสดงผลในไฟล์ HTML
  - กำหนดรูปแบบสำหรับองค์ประกอบต่างๆเช่น สีพื้นหลัง, แบบอักษร, สไตล์ปุ่มและเค้าโครง

-script.js:
ไฟล์ JavaScript นี้เพิ่มประสิทธิภาพให้กับตัวจับเวลาแบบ Pomodoro 
  - ไฟล์นี้เลือกองค์ประกอบ HTML (ปุ่ม, แสดงจับเวลา) โดยใช้ ID และ CLASS
  - ไฟล์นี้กำหนดค่าตัวแปรสำหรับการตั้งค่าและสถานะของตัวจับเวลา
  - ไฟล์นี้กำหนดฟังก์ชันเพื่อ:
    - เพิ่มเลขศูนย์นำหน้าให้กับตัวเลขที่น้อยกว่า 10
    - รีเซ็ตตัวจับเวลา
    - ลบการโฟกัสจากปุ่ม
    - จัดการเหตุการณ์คลิกปุ่มเช่น Focus, Short Break และ Long Break
    - เริ่ม, พัก, และอัปเดตการนับถอยหลังของตัวจับเวลา

2) วิธีการรัน pomodoro-timer:

  -  สร้างไฟล์สามไฟล์ index.html, style.css และ script.js และวางไว้ในโฟลเดอร์เดียวกัน
  - เปิดไฟล์ index.html จากนั้นคลิกขวาที่ไฟล์ index.html คลิก "Open With Live Server" หรือ
  - เปิดไฟล์ index.html จากนั้นคลิกที่ขวาล่างของหน้าจอชื่อ "Go Live" หรือ
  - ในกรณีที่ไม่มี Extension "Live Server" สามารถกดไปที่ "Run -> Start Debugging(F5)" ในไฟล์ index.html เพื่อรัน pomodoro-timer
  - อย่าลืมตรวจสอบว่ามีการเชื่อมต่ออินเทอร์เน็ตเพราะไฟล์ HTML ลิงก์ไปยังแหล่งข้อมูลภายนอก Font Awesome และ Google Fonts 
