# 🌿 Pokopia Web Tools Project

[![Web Design](https://img.shields.io/badge/Design-Pastel%20Forest-98FB98?style=for-the-badge)]()
[![Frontend](https://img.shields.io/badge/Frontend-HTML5%20%2F%20CSS3%20%2F%20JS-blue?style=for-the-badge)]()
[![Project-Type](https://img.shields.io/badge/Game--Tool-Pokopia-orange?style=for-the-badge)]()

**Pokopia Web Tools** เว็บสูตรทำอาหารสำหรับผู้เล่น **Pokopia**

---

## 📂 ส่วนประกอบของโปรเจกต์

ในชุดเครื่องมือนี้จะแบ่งออกเป็น 2 เว็บไซต์หลัก ดังนี้:

### 1. Cooking Guide
*รายการอาหารพร้อมสูตรทำอาหารแบบครบ ๆ*

* **Smart Flavor Filtering:** ระบบกรองเมนูตามรสชาติ (Spicy, Sweet, Sour, Bitter, Normal) ที่เลือกดูได้ทันที
* **Comprehensive Database:** ตารางแสดงรายละเอียดแบบละเอียด:
    * **Ingredients:** วัตถุดิบที่จำเป็นพร้อมไอคอนประกอบ
    * **Buff Effects:** ผลลัพธ์ของสเตตัสที่จะได้รับ
    * **Helper Skills:** ข้อมูลสกิลเสริมจากตัวละครที่เกี่ยวข้อง
* **Visual Highlights:** มีการใช้สีแยกตามประเภทของรสชาติอาหารเพื่อให้แยกแยะข้อมูลได้ง่าย

### 2. Cooking Mixer
*ระบบจำลองการผสมอาหาร (Cooking Simulator)*

* **Equipment Selection:** เลือกใช้อุปกรณ์ในการทำได้ 4 ชนิด (Cooking Pot, Frying Pan, Bread Oven, Chopping Board) ซึ่งจะมีผลต่อช่องใส่วัตถุดิบและบัฟพื้นฐาน
* **Dynamic Slot System:** ระบบเลือกวัตถุดิบลงในช่อง (Slots) แบบ Real-time
* **Helper Skill Toggle:** ระบบสลับการเปิด-ปิด สกิลผู้ช่วยเพื่อดูความเปลี่ยนแปลงของเมนูผลลัพธ์
* **Instant Result:** แสดงชื่อเมนู, รสชาติ และบัฟที่จะได้รับทันทีหลังกดทำอาหารเสร็จแล้ว

---

## 🎨 การออกแบบและเทคนิค (UI/UX & Tech)

| หัวข้อ | รายละเอียด |
| :--- | :--- |
| **Theme** | **Pastel Forest:** เน้นสี Mint, Teal และ Sky Blue ให้ใกล้เคียงสีเกม |
| **Style** | **Glassmorphism:** ใช้ความโปร่งใสของ Card เพื่อความทันสมัย |
| **Typography** | **Prompt:** ใช้ฟอนต์ที่มีความทันสมัยและอ่านง่ายในทุกขนาดหน้าจอ |
| **Responsive** | รองรับการทำงานเต็มรูปแบบทั้งบน **Mobile** และ **Desktop** |
| **Performance** | เขียนด้วย **Vanilla JavaScript** (No Library) เพื่อความเร็วสูงสุดในการโหลด |
