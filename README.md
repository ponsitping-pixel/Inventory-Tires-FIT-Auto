# ค้นหายางตามขนาด (FIT Auto)

หน้าเว็บค้นหาสต็อกยาง เป็นไฟล์ HTML ไฟล์เดียว (`index.html`) ข้อมูลสต็อก ราคา โปรยางปีเก่า AM และพิกัดสาขา ฝังอยู่ในไฟล์แล้ว ไม่ต้อง build ไม่ต้องมี backend

ข้อมูลสต็อกวันที่ 23 พ.ย. 2569

## อัปโหลดขึ้น GitHub
1. สร้าง repository ใหม่ แนะนำให้ตั้งเป็น **Private** (ในไฟล์มีสต็อก ราคา และพิกัดสาขา)
2. อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ (`index.html`, `vercel.json`, `robots.txt`, `README.md`, `.gitignore`)

## Deploy บน Vercel
1. เข้า vercel.com แล้วเลือก Add New → Project → Import repository ที่สร้างไว้
2. Framework Preset เลือก **Other** ช่อง Build Command และ Output Directory ปล่อยว่าง
3. กด Deploy จะได้ลิงก์ `https://ชื่อโปรเจกต์.vercel.app`

## อัปเดตข้อมูลสต็อก
แทนที่ `index.html` ด้วยไฟล์ใหม่ แล้ว commit/push Vercel จะ deploy ใหม่ให้อัตโนมัติ

## หมายเหตุ
- ใครมีลิงก์ก็เปิดดูได้ ถ้าต้องการจำกัดผู้ใช้ ให้เปิด Password Protection ของ Vercel (ต้องใช้แผนที่รองรับ) หรือใช้ Cloudflare Access
- ไฟล์ตั้งค่า noindex ไว้แล้ว เพื่อไม่ให้ค้นเจอทาง Google
- ฟอนต์ Noto Sans Thai โหลดจาก Google Fonts ถ้าออฟไลน์จะใช้ฟอนต์สำรองของเครื่อง
