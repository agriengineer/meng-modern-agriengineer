เว็บไซต์หลักสูตร วศ.ม. วิศวกรรมเกษตรสมัยใหม่ (ปรับปรุง พ.ศ. 2569)
==============================================================
index.html        หน้าเว็บทั้งหมด (ไฟล์เดียว) แก้ข้อมูลที่ var DATA / var STATIC / var I18N_EN
images/           ภาพประกอบ (hero-dark.svg = ภาพหน้าแรก)
images/faculty/   วางรูปอาจารย์ แล้วใส่ photo:"images/faculty/ชื่อไฟล์.jpg" ใน DATA
images/voices/    รูปผู้ให้ความเห็น (testimonials)
docs/             ไฟล์ PDF ของหลักสูตร

แบนเนอร์ด้านบนแต่ละหน้า (พื้นเข้ม)
- สีและลวดลาย: แก้ CSS ส่วน "/* page banners — dark, matches hero */" (.phead, .band)
- ข้อความตัวใหญ่จาง ๆ ด้านขวา: <span class="ph-mark">ABOUT</span> ในแต่ละหน้า
- หัวข้อ/คำอธิบาย: แก้ใน <div class="phead"> ... <h2> ... <p> ของหน้านั้น
- แบนเนอร์หน้าแรก: CSS ส่วน "/* hero — dark banner */" และภาพที่ DATA.hero

เปิดดูภาษาอังกฤษ: index.html?lang=en
รายละเอียดทั้งหมดดู "คู่มือดูแลเว็บไซต์หลักสูตร" (Claude Doc)
