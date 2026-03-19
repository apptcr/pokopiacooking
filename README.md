# 🌿 Pokopia Web Tools Project

[![Web Design](https://img.shields.io/badge/Design-Pastel%20Forest-98FB98?style=for-the-badge)]()
[![Frontend](https://img.shields.io/badge/Frontend-HTML5%20%2F%20CSS3%20%2F%20JS-blue?style=for-the-badge)]()
[![Project-Type](https://img.shields.io/badge/Game--Tool-Pokopia-orange?style=for-the-badge)]()

**Pokopia Web Tools** คือชุดเครื่องมือสนับสนุนสำหรับผู้เล่นเกม **Pokopia** ที่ถูกออกแบบมาด้วยธีม *Pastel Forest* เพื่อมอบประสบการณ์การใช้งานที่สวยงามและสบายตา ประกอบด้วยระบบค้นหาสูตรอาหารและระบบคำนวณการผสมวัตถุดิบที่แม่นยำ

---

## 📂 ส่วนประกอบของโปรเจกต์

ในชุดเครื่องมือนี้จะแบ่งออกเป็น 2 เว็บไซต์หลัก ดังนี้:

### 1. 📖 Pokopia Ultimate Cooking Guide
*ระบบจัดการฐานข้อมูลสูตรอาหารทั้งหมดภายในเกม*

* **Smart Flavor Filtering:** ระบบกรองข้อมูลตามรสชาติ (Spicy, Sweet, Sour, Bitter, Normal) ที่เลือกดูได้ทันที
* **Comprehensive Database:** ตารางแสดงรายละเอียดแบบละเอียด:
    * **Ingredients:** วัตถุดิบที่จำเป็นพร้อมไอคอนประกอบ
    * **Buff Effects:** ผลลัพธ์ของสเตตัสที่จะได้รับ
    * **Helper Skills:** ข้อมูลสกิลเสริมจากตัวละครที่เกี่ยวข้อง
* **Visual Highlights:** มีการใช้สีแยกตามประเภทของรสชาติอาหารเพื่อให้แยกแยะข้อมูลได้ง่าย

### 2. 🧪 Pokopia Master Mixer
*เครื่องมือจำลองการผสมอาหาร (Cooking Simulator)*

* **Equipment Selection:** เลือกใช้อุปกรณ์ได้ 4 ชนิด (Pot, Frying Pan, Oven, Kettle) ซึ่งจะมีผลต่อช่องใส่วัตถุดิบและบัฟพื้นฐาน
* **Dynamic Slot System:** ระบบเลือกวัตถุดิบลงในช่อง (Slots) แบบ Real-time
* **Helper Skill Toggle:** ระบบสลับการเปิด-ปิด สกิลผู้ช่วยเพื่อดูความเปลี่ยนแปลงของผลลัพธ์
* **Instant Result:** แสดงชื่อเมนู, รสชาติ และบัฟที่จะได้รับทันทีหลังกด "Cook!"

---

## 🎨 การออกแบบและเทคนิค (UI/UX & Tech)

| หัวข้อ | รายละเอียด |
| :--- | :--- |
| **Theme** | **Pastel Forest:** เน้นสี Mint, Teal และ Sky Blue เพื่อความสบายตา |
| **Style** | **Glassmorphism:** ใช้ความโปร่งใสของ Card เพื่อความทันสมัย |
| **Typography** | **Prompt:** ใช้ฟอนต์ที่มีความทันสมัยและอ่านง่ายในทุกขนาดหน้าจอ |
| **Responsive** | รองรับการทำงานเต็มรูปแบบทั้งบน **Mobile** และ **Desktop** |
| **Performance** | เขียนด้วย **Vanilla JavaScript** (No Library) เพื่อความเร็วสูงสุดในการโหลด |

---

## 🚀 วิธีการใช้งาน

1. Clone โปรเจกต์นี้ลงในเครื่องของคุณ
2. เปิดไฟล์ `guide.html` เพื่อดูสูตรอาหารทั้งหมด
3. เปิดไฟล์ `mixer.html` หากต้องการทดลองผสมสูตรอาหารใหม่ๆ

---

## 🛠️ โครงสร้างไฟล์ในโปรเจกต์
```text
.
├── guide.html        # หน้าแสดงข้อมูลสูตรอาหารทั้งหมด
├── mixer.html        # หน้าโปรแกรมคำนวณการผสมอาหาร
├── images/           # โฟลเดอร์เก็บไอคอนและรูปภาพประกอบ
└── README.md         # ข้อมูลรายละเอียดโปรเจกต์
