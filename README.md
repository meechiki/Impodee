# อิ่มพอดี (Impodee) — Flixo Clean & Minimalist Edition 🥗✨

ผู้ช่วยคำนวณและบันทึกโภชนาการตามค่า **TDEE (Total Daily Energy Expenditure)** ในสไตล์ **Flixo (Modern Enterprise Minimalist UX)** 

🔗 **GitHub Repository**: [https://github.com/meechiki/Impodee](https://github.com/meechiki/Impodee)

---

## 🎨 จุดเด่นการดีไซน์ (Design Aesthetics - Flixo Style)

1. **Soft Cloud & Glassmorphism Aesthetics**:
   - พาเลทสีนุ่มสบายตา โทนสีเขียวพาสเทล (`#10B981`), ส้มคอรัล (`#FF6B4A`), ฟ้าอบอุ่น (`#3B82F6`) และโกลด์ (`#F59E0B`)
   - การ์ดกระจกใสแบบโปร่งแสง (`backdrop-filter: blur(20px)`) ขอบมนนุ่มนวล `26px`
   - เงาสะท้อนลอยตัว (Soft Drop Shadows & Glowing Accents)
2. **Typography & Readability**:
   - หัวข้อและตัวเลขคมชัดระดับพรีเมียมด้วยฟอนต์ **Kanit**
   - ข้อความอ่านง่าย สบายตาด้วย **Inter** และ **Sarabun**
3. **Micro-Animations & Dynamic Reactions**:
   - ตัวละคร SVG ดุ๊กดิ๊กตอบสนองอารมณ์ตามปริมาณแคลอรี่ที่รับประทานจริง (**Idle**, **Happy**, **Hungry**, **Full**)
   - แถบดาวโหลดเป้าหมายสารอาหาร (Protein, Fat, Carb, Sodium) พร้อมแอนิเมชันลื่นไหล
   - สตรีคไฟลุก (Flame Pulse) สำหรับการทานอาหารได้ตามเป้าต่อเนื่อง

---

## ⚙️ คุณสมบัติระบบ (Features)

- 🧮 **TDEE & Macro Calculator**: คำนวณพลังงาน BMR ด้วย Mifflin-St Jeor Formula ตามเพศ อายุ น้ำหนัก ส่วนสูง กิจกรรม และเป้าหมาย (ลด/รักษา/เพิ่มน้ำหนัก)
- 🍽️ **Daily Food Logger**: บันทึกมื้ออาหาร คอยติดตามแคลอรี่ สารอาหารหลัก และโซเดียมสะสม
- 🤖 **AI Food Vision & Barcode Scanning**: รองรับการถ่ายรูปอาหารและสแกนฉลากโภชนาการโดยใช้ **Anthropic Claude API Vision**
- 🧍 **SVG Character Customizer**: ปรับแต่งทรงผม สีผม สีผิว เสื้อ กางเกง และรองเท้าของตัวละครได้อิสระ
- 🔐 **Privacy First**: ข้อมูลทั้งหมดถูกบันทึกใน `localStorage` ของเบราว์เซอร์เครื่องผู้ใช้โดยตรง

---

## 🚀 วิธีเปิดใช้งาน (Getting Started)

เพียงเปิดไฟล์ `index.html` บนเว็บเบราว์เซอร์ใดก็ได้ หรือเปิดผ่าน Local Web Server / GitHub Pages:

```bash
# Clone repository
git clone https://github.com/meechiki/Impodee.git

# เปิดใช้งานในเบราว์เซอร์
open index.html
```

---

## 📄 License

MIT License — พัฒนาและดูแลโดย [meechiki/Impodee](https://github.com/meechiki/Impodee)
