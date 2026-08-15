# ระบบแจ้งซ่อมบ้าน & มอบหมายงาน — BE MORE Home Care

เว็บแอปไฟล์เดียว (static) เปิดผ่านลิงก์ได้ทันทีเมื่อขึ้น GitHub Pages

## ไฟล์
- `index.html` — เว็บแอปหลัก (เปิดใช้งานได้เลย มีข้อมูลจริงฝังไว้)
- `docs/user-guide-th.html` — คู่มือใช้งานสำหรับพนักงาน
- `docs/setup-guide-th.html` — คู่มือติดตั้งระบบคลาวด์ (Google Sheets + LINE)
- `docs/system-summary-th.html` — สรุประบบทั้งหมด
- `.nojekyll` — ให้ GitHub Pages เสิร์ฟไฟล์ตรงๆ

## วิธีขึ้น GitHub Pages
ดูขั้นตอนละเอียดในข้อความที่ Claude ส่งให้ หรือโดยย่อ:
1. สร้าง repository ใหม่บน GitHub
2. อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ (index.html ต้องอยู่ที่ราก repo)
3. Settings → Pages → Source: Deploy from a branch → Branch: `main` / `/ (root)` → Save
4. รอ 1–2 นาที จะได้ลิงก์ `https://<username>.github.io/<repo>/`

## หน้าใช้งาน
- `…/` → เว็บแอป
- `…/docs/user-guide-th.html` → คู่มือพนักงาน
