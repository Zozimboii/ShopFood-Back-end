# ShopFood API Service (Backend)

ระบบ API หลักสำหรับจัดการข้อมูลร้านอาหาร พัฒนาด้วย Node.js และ PostgreSQL โดยเน้นความปลอดภัยและการจัดการข้อมูลที่มีประสิทธิภาพ

### PLAY VIDEO

[FOODSHOP VIDEO DEMO](https://youtu.be/REF7OBksKoc)

### Tech Stack

- **Runtime:** Node.js
- **Framework:** Express.js
- **Database:** PostgreSQL (Managed via pgAdmin 4)
- **Authentication:** JWT (JSON Web Token) & Bcrypt Hashing
- **Documentation:** Swagger UI (OpenAPI Spec)

### Key Features

- **User & Auth:** ระบบสมัครสมาชิก, Login และการจัดการสิทธิ์เข้าถึง
- **Product API:** จัดการข้อมูลเมนูอาหารและเครื่องดื่มแบบ Dynamic
- **Order Management:** ระบบจัดการตะกร้าสินค้า (Carts) และรายละเอียดการสั่งซื้อ (Cart Details)
- **File Upload:** รองรับการอัปโหลดและจัดการรูปภาพโปรไฟล์ผู้ใช้งาน

### Installation

1. ติดตั้ง Dependencies:

   ```bash
   npm install

   ```

2. How to run:
   ```bash
   npm start
   ```

### setup Environment

PORT=3000

DBHOST=127.0.0.1

DBUSER=your_user

DBPWD=your_password

DB=yournamefood
