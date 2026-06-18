# KUMYAI Smart Health Volunteer 2569 - PWA ฉบับสมบูรณ์

## วิธีติดตั้งใช้งานบนมือถือ
1. แตกไฟล์ ZIP
2. อัปโหลดไฟล์ทั้งหมดไปยัง Web Server ที่เป็น HTTPS เช่น GitHub Pages, Netlify, Vercel หรือ Hosting ของหน่วยงาน
3. เปิดลิงก์ด้วย Chrome บน Android หรือ Safari บน iPhone
4. Android: กดปุ่ม "ติดตั้ง" หรือเมนู ⋮ > Add to Home screen
5. iPhone: กด Share > Add to Home Screen

## ไฟล์สำคัญ
- index.html = ตัวแอปหลัก
- manifest.json = ข้อมูลติดตั้ง PWA
- sw.js = ระบบ Offline Cache
- icon.svg = ไอคอนแอป

## หมายเหตุ
PWA จะติดตั้งได้เต็มรูปแบบเมื่อเปิดผ่าน HTTPS หรือ localhost เท่านั้น
