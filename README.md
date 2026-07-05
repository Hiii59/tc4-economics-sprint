# TC4 Economics Final Review

เว็บสรุปเศรษฐศาสตร์ TC4 จากไฟล์แนบ พร้อมกราฟ interactive, simulation lab สำหรับเล่นกับตลาด, เครื่องคำนวณโจทย์สมดุลตลาด/เพดานราคา/ภาษี, ชุดข้อสอบจำลอง 15 คะแนน, แบบฝึกหัดเลือกคำตอบ, เติมคำ, flashcards และข้อเขียนสั้น

## เปิดดูในเครื่อง

```powershell
cd D:\THcult
python -m http.server 8765 --bind 127.0.0.1
```

จากนั้นเปิด:

```text
http://127.0.0.1:8765/
```

## นำขึ้น GitHub Pages หรือ Cloudflare Pages

อัปโหลดไฟล์เว็บจาก root ของโปรเจกต์นี้ขึ้น repository แล้วตั้งค่าให้ deploy จาก root

- GitHub Pages: Settings -> Pages -> Deploy from branch -> folder `/`
- Cloudflare Pages: Build command เว้นว่าง, Output directory ใส่ `.`

## Impeccable

ติดตั้ง Impeccable project skills แล้ว และ live mode ถูกตั้งค่าให้ inject ที่ `index.html`

## เวอร์ชัน polish ล่าสุด

- เพิ่ม note block เชิงสอบเป็น 53 บล็อก พร้อมทริคจำและตัวอย่างสถานการณ์จริง
- แก้ระบบกราฟย่อย 7 แบบให้วาดจากพิกัดเศรษฐศาสตร์จริงขึ้น โดยเฉพาะ price ceiling, tax, externality และ monopoly DWL
- เพิ่ม simulation lab ที่ปรับ demand shift, price ceiling และ tax/unit ได้ พร้อม preset ค่าเช่า หน้ากาก ภาษีน้ำตาล และอุดหนุนการศึกษา
- เพิ่มคลังแบบฝึก: MCQ 41 ข้อ, เติมคำ 22 ข้อ, flashcards 30 ใบ, ตอบสั้น 13 ข้อ
- เพิ่ม random drill เป็น 10 แนว รวม derive curve, social welfare, tax incidence, market structure และ market failure policy
- เพิ่ม animation, reading progress และ reveal motion พร้อมรองรับ reduced motion
- ปรับ typography เป็น TH Sarabun-first stack พร้อม Google Sarabun fallback สำหรับเครื่องที่ไม่มีฟอนต์ TH Sarabun ติดตั้ง
- เพิ่ม hamburger menu มุมขวาบนสำหรับสารบัญแบบไม่ดัน layout
