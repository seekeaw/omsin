# ออมสิน

แอพพลิเคชั่นรายรับ-รายจ่าย ส่วนบุคคล ช่วยให้การบันทึกรายรับรายจ่ายสามารถทำได้ง่ายๆ และ ปลอดภัย รองรับการทำงานทุกอุปกรณ์ เช่น Desktop Tablet และ มือถือ

## ความต้องการของระบบ
* PHP 5.3 ขึ้นไป
* ext-mbstring
* PDO Mysql

## การติดตั้ง
* ดาวน์โหลดโค้ดทั้งหมดจาก Github
* แตกไฟล์และอัปโหลดไฟล์ทั้งหมดไปยัง Server ยกเว้นไฟล์ omsin.sql
* สร้างฐานข้อมูล และ Import ข้อมูลจาก omsin.sql ไปยังฐานข้อมูล
* กำหนดค่า settings/config.php และ settings/database.php ให้ถูกต้อง
* สร้างไดเร็คทอรี่ datas/ (ถ้ายังไม่มี) และปรับ chmod ให้ไดเร็คทอรี่ datas/ สามารถเขียนได้ (หรือปรับ chmod เป็น 777)
* ทดสอบเรียกใช้งาน