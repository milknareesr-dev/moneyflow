# MoneyFlow PWA 📱

## วิธีติดตั้งบนมือถือ (ใน 3 ขั้นตอน)

### ขั้นที่ 1 — อัปโหลดขึ้น GitHub Pages (ฟรี)
1. สมัคร GitHub ที่ https://github.com (ฟรี)
2. กด **New repository** → ตั้งชื่อ `moneyflow` → Public → Create
3. ลากไฟล์ทั้งหมดในโฟลเดอร์นี้ขึ้นไปวางในหน้า repository
4. ไปที่ **Settings → Pages → Source: main / root** → Save
5. รอ 1-2 นาที จะได้ URL เช่น `https://yourname.github.io/moneyflow`

### ขั้นที่ 2 — เปิดบนมือถือ
- เปิด URL นั้นใน **Chrome** (Android) หรือ **Safari** (iPhone)

### ขั้นที่ 3 — Add to Home Screen
**Android (Chrome):**
- กดเมนู ⋮ → "Add to Home screen" → Add

**iPhone (Safari):**
- กดปุ่ม Share 🔗 → "Add to Home Screen" → Add

✅ ได้แอปบนหน้าจอเลย! ใช้งานได้แบบออฟไลน์ด้วย

---
## ไฟล์ในโฟลเดอร์
- `index.html` — ตัวแอปหลัก
- `manifest.json` — ข้อมูล PWA (ชื่อ, ไอคอน, สี)
- `sw.js` — Service Worker (ทำให้ใช้ออฟไลน์ได้)
- `icons/` — ไอคอนแอป
