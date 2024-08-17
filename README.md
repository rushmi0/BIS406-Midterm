### 2013111089 วัชรพล พงษ์วิลัย

# การวิเคราะห์และป้องกันความเสี่ยงในการเข้าถึงระบบข้อมูล

## 1. การวิเคราะห์ความเสี่ยง

- **ประเมินจุดอ่อนของระบบการเข้าถึง**: ตรวจสอบทั้งการเข้าถึงทางกายภาพและลอจิคัล
- **วิเคราะห์ความเสี่ยงจากการเข้าถึงภายนอก**: พิจารณาอุปกรณ์ที่ไม่ได้รับอนุญาต
- **ประเมินผลกระทบ**: วิเคราะห์ข้อมูลที่เป็นเป้าหมายและความเสียหายที่อาจเกิดขึ้น
- **กำหนดระดับความเสี่ยง**: ประเมินโอกาสเกิดเหตุและผลกระทบ

## 2. มาตรการควบคุมใหม่

- **การเข้าถึงทางกายภาพ**:
  - ใช้ MFA, จำกัดพื้นที่สำคัญ, ติดกล้องวงจรปิด
- **การเข้าถึงทางลอจิคัล**:
  - ใช้ MFA, จำกัดอุปกรณ์ภายนอก, เข้ารหัสข้อมูล, ติดตั้ง IDS/IPS

## 3. การตรวจสอบประสิทธิภาพ

- **Penetration Testing**: จำลองการเจาะระบบ
- **ตรวจสอบ Access Logs**: ตรวจจับการเข้าถึงที่ไม่ถูกต้อง
- **ทดสอบฟังก์ชันการเข้าถึง**: ทดสอบการเข้าถึงจากอุปกรณ์ต่าง ๆ
- **อบรมพนักงาน**: เพิ่มความรู้ในการรักษาความปลอดภัย


# การประเมินและปรับปรุงระบบสำรองข้อมูลและการกู้คืน

## 1. ความเสี่ยงหลัก

- **การพึ่งพาผู้ให้บริการคลาวด์**: อาจเกิดการหยุดชะงักหรือการเข้าถึงข้อมูลไม่ได้
- **เวลาการกู้คืน (RTO)**: การกู้คืนไม่ทันตามกำหนด อาจกระทบต่อความต่อเนื่องทางธุรกิจ
- **ความปลอดภัยของข้อมูล**: ความเสี่ยงจากการเข้าถึงข้อมูลที่ไม่ได้รับอนุญาต

## 2. แนวทางการปรับปรุง

- **ระบบสำรองหลายระดับ**: เพิ่มสำรองข้อมูลในหลายภูมิภาคและใช้ผู้ให้บริการหลายราย
- **การทดสอบกู้คืนข้อมูลประจำ**: ทดสอบความสามารถในการกู้คืนข้อมูลตาม RTO ที่กำหนด
- **การเข้ารหัสข้อมูล**: ป้องกันการเข้าถึงข้อมูลทั้งขณะพักและขณะส่ง

## 3. ขั้นตอนการตรวจสอบ

- **ทดสอบการกู้คืนข้อมูล**: จำลองเหตุการณ์ฉุกเฉินและตรวจสอบความสามารถในการกู้คืน
- **ตรวจสอบ RTO**: เปรียบเทียบกับเป้าหมายที่กำหนด
- **ตรวจสอบการเข้าถึงและความปลอดภัย**: ประเมินการเข้ารหัสและนโยบายการเข้าถึงข้อมูล

