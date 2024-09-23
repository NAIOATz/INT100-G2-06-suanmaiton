# Test Script Line Official Account ของสวนธนฯ

### Test Case 1: การตรวจสอบฟังก์ชันอัปเดตสภาพอากาศ <br>
+ **Test Case ID:** `01`
+ **Test Name:** ตรวจสอบการแสดงผลข้อมูลสภาพอากาศ
+ **Objective:** ตรวจสอบว่าฟังก์ชันการอัปเดตสภาพอากาศทำงานอย่างถูกต้องและข้อมูลที่แสดงตรงกับแหล่งข้อมูลอื่น
+ **Pre-condition:** ผู้ใช้เข้าสู่ระบบ Line Official Account ของสวนสาธารณะแล้ว
+ **step:**
  - ผู้ใช้เปิด Line Official Account ของสวนสาธารณะ
  - เลือกเมนู "สภาพอากาศ" จากหน้าแชท
  - สังเกตข้อมูลสภาพอากาศที่แสดง
  - เปิดเว็บไซต์แหล่งข้อมูลอื่น เช่น Google Weather เพื่อเปรียบเทียบข้อมูล
+ **Expected Result:** ข้อมูลสภาพอากาศ เช่น อุณหภูมิ และสภาพท้องฟ้า (แดด, ฝน, เมฆ) ต้องตรงกับแหล่งข้อมูลภายนอก
+ **Actual Result:** 
+ **Pass/Fail:** 

### Test Case 2: การทดสอบฟังก์ชันการแจ้งของชำรุด
- **Test Case ID:** `02`
- **Test Name:** ตรวจสอบการแจ้งของชำรุดในสวนสาธารณะ
- **Objective:** ตรวจสอบว่าผู้ใช้สามารถแจ้งของชำรุดผ่าน Line Official Account ได้สำเร็จ และได้รับการยืนยันว่าระบบรับการแจ้งปัญหา
- **Pre-condition:** ผู้ใช้ล็อกอินเข้าสู่ Line Official Account แล้ว
- **Steps:**
  - ผู้ใช้เลือกเมนู "แจ้งของชำรุด"
  - กรอกรายละเอียดเกี่ยวกับปัญหาที่พบ เช่น เครื่องเล่นพัง พร้อมแนบรูปภาพ (ถ้ามี)
  - กดปุ่มส่งเพื่อแจ้งปัญหา
  - รอรับการยืนยันว่าการแจ้งปัญหาสำเร็จ
- **Expected Result:** ระบบต้องยืนยันว่าได้รับการแจ้งของชำรุดเรียบร้อย และควรมีข้อความตอบกลับยืนยันให้ผู้ใช้ทราบ
- **Actual Result:** 
- **Pass/Fail:** 

### Test Case 3: การทดสอบฟังก์ชันกลุ่มชมรม
- **Test Case ID:** `03`
- **Test Name:** ตรวจสอบการเข้าร่วมและการอัปเดตในกลุ่มชมรมต่างๆ
- **Objective:** ตรวจสอบว่าผู้ใช้สามารถเข้าร่วมกลุ่มชมรมได้และรับการแจ้งเตือนกิจกรรมจากกลุ่มนั้นๆ
- **Pre-condition:** ผู้ใช้ต้องเข้าถึงกลุ่มชมรมที่ต้องการ
- **Steps:**
  - ผู้ใช้เปิด Line Official Account ของสวนสาธารณะ
  - เลือกชมรมที่ต้องการเข้าร่วม เช่น ชมรมวิ่ง
  - กดเข้าร่วมชมรม
  - ตรวจสอบว่าได้รับข้อความอัปเดตหรือแจ้งเตือนเกี่ยวกับกิจกรรมของชมรมนั้นๆ
- **Expected Result:** ผู้ใช้สามารถเข้าร่วมชมรมได้ และได้รับการแจ้งเตือนกิจกรรมที่เกี่ยวข้องกับชมรมนั้นๆ อย่างถูกต้อง
- **Actual Result:** 
- **Pass/Fail:** 

### Test Case 4: การทดสอบระบบอัปเดตข่าวสารประจำ
- **Test Case ID:** `04`
- **Test Name:** ตรวจสอบการอัปเดตข่าวสารอัตโนมัติ
- **Objective:** ตรวจสอบว่าข่าวสารที่อัปเดตในระบบ Line Official Account จะแสดงผลตรงเวลาตามที่ระบบกำหนดไว้
- **Pre-condition:** ผู้ใช้เข้าสู่ Line Official Account ของสวนสาธารณะแล้ว
- **Steps:**
  - ผู้ใช้เปิด Line Official Account ของสวนสาธารณะ
  - ตรวจสอบการอัปเดตข่าวสารในหน้าแชท
  - สังเกตเวลาและเนื้อหาของข่าวสารว่ามีการอัปเดตตามกำหนดเวลาหรือไม่
- **Expected Result:** ข่าวสารที่อัปเดตจะต้องตรงเวลาตามที่กำหนด และเนื้อหาข่าวสารจะต้องแสดงข้อมูลที่ครบถ้วนและถูกต้อง
- **Actual Result:** 
- **Pass/Fail:** 

### Test Case 5: การทดสอบประสิทธิภาพการตอบสนองของระบบ (Response Time Test)
- **Test Case ID:** `05`
- **Test Name:** ตรวจสอบความเร็วในการตอบสนองของฟังก์ชันหลัก
- **Objective:** ตรวจสอบว่าแต่ละฟังก์ชันใน Line Official Account ตอบสนองได้เร็วและไม่มีความล่าช้าเกินไป
- **Pre-condition:** ผู้ใช้มีการเชื่อมต่ออินเทอร์เน็ตที่ดี
- **Steps:**
  - ผู้ใช้เปิด Line Official Account ของสวนสาธารณะ
  - กดเลือกเมนู "อัปเดตสภาพอากาศ" หรือ "แจ้งของชำรุด"
  - วัดระยะเวลาที่ระบบตอบสนองหรือแสดงข้อมูลกลับมาภายในแอปพลิเคชัน
- **Expected Result:** ฟังก์ชันควรตอบสนองภายใน 2-3 วินาทีหลังจากที่ผู้ใช้ทำการเลือกเมนู
- **Actual Result:** 
- **Pass/Fail:** 