# 🛒 Campus Marketplace System
**ระบบตลาดนัดส่งต่อสิ่งของและหนังสือเรียนมือสองภายในมหาวิทยาลัย**

---

## 📌 วัตถุประสงค์ (Project Overview)
ระบบตลาดนัดส่งต่อสิ่งของและหนังสือเรียนมือสองภายในมหาวิทยาลัย เป็น Web Application ที่จัดทำขึ้นเพื่อแก้ปัญหาการส่งต่อสิ่งของ/หนังสือเรียนผ่านกลุ่มโซเชียลทั่วไป ซึ่งมักประสบปัญหาโพสต์ถูกดันหาย ค้นหาตามรหัสวิชายาก และเสี่ยงต่อการถูกหลอกลวง 

ระบบนี้ช่วยให้นักศึกษาและบุคลากรส่งต่อสิ่งของสภาพดีในราคาประหยัดหรือแจกฟรี ผ่านเครือข่ายที่ปลอดภัยภายในมหาวิทยาลัย

---

## ✨ คุณลักษณะเด่นของระบบ (Key Features)
1. **Domain-Specific Authentication:** สมัครและเข้าสู่ระบบด้วย E-mail มหาวิทยาลัยเท่านั้น เพื่อยืนยันตัวตนคนภายในสถาบัน (UC-01)
2. **Course Code Search & Filter:** ค้นหาหนังสือเรียนตามรหัสวิชา คณะ หรือหมวดหมู่สิ่งของได้อย่างรวดเร็ว (UC-03)
3. **Embedded Chat & Location Pins:** ระบบแชทส่วนตัวพร้อมปักหมุดพิกัดจุดนัดรับ-ส่งมอบสินค้าภายในพื้นที่มหาวิทยาลัยบนแผนที่ (UC-04, UC-05)
4. **Mutual Rating & Review System:** ระบบประเมินและให้คะแนนความน่าเชื่อถือของผู้ซื้อ-ผู้ขายหลังจบการซื้อขาย (UC-06)
5. **Admin Moderation:** ระบบสำหรับผู้ดูแลระบบในการตรวจสอบและจัดการโพสต์ที่ไม่เหมาะสม (UC-07)

---

## 📁 โครงสร้างโปรเจกต์ (Project Structure)
- `frontend/` - ส่วนแสดงผลผู้ใช้งาน (Responsive Design สำหรับ Web/Mobile)
- `backend/` - ส่วนประมวลผลเซิร์ฟเวอร์ (REST API, Authentication, Business Logic)
- `database/` - ไฟล์จัดเก็บและจัดการสคีมาฐานข้อมูล (User, Product, ChatMessage, Review, PickupLocation)
- `docs/` - เอกสารประกอบโครงงาน (SRS, Use Case Diagrams, Process Workflows)
- `tests/` - ชุดทดสอบระบบ (Unit Testing & System Integration Testing)

---

## 👥 สมาชิกในทีมและการแบ่งหน้าที่ความรับผิดชอบ (Team Members & Roles)

| ชื่อ-นามสกุล | บทบาทหน้าที่ (Role & Responsibilities) | โมดูลที่รับผิดชอบ |
| :--- | :--- | :--- |
| **นางสาวโสรญา สวรรค์งาม** | **UI/UX Designer & System Analyst:** ออกแบบ Wireframe/Prototype ด้วย Figma และออกแบบ Database Schema & API Endpoints | `frontend/`, `docs/` |
| **นางสาวเกสรา ชำนิเขตกิจ** | **Project Manager / Product Owner (PO):** บริหารจัดการโครงการ, รวบรวม Requirement, ทำ Backlog และจัดลำดับความสำคัญของ User Stories | `docs/`, `database/` |
| **นายวรชิต คำอินทา** | **DevOps & QA Engineer:** พัฒนาระบบ Rating/Review, ทดสอบระบบ (Testing), Deploy ระบบขึ้น Cloud Server และรวบรวม Feedback | `tests/`, `backend/` |
| **นายปุรเชษฐ์ ศิริเขตรกิจ** | **Full-Stack Developer (Lead Dev):** พัฒนาระบบ Authentication, การลงประกาศ, ระบบค้นหา และระบบ Chat | `backend/`, `frontend/` |

---

## 🛠️ เทคโนโลยีที่ใช้พัฒนา (Tech Stack)
- **Frontend:** HTML, CSS, JavaScript / React (Responsive Web Design)
- **Backend:** Node.js / Python / Java (RESTful API)
- **Database:** PostgreSQL / MySQL / MongoDB
- **Version Control & DevOps:** Git, GitHub, Cloud Deployment
