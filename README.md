นการใช้งาน Angular CLI ตั้งแต่ขั้นตอนการสร้าง Angular Project
การทดสอบการทำงาน หรือ Run Project Code และการนำ Angular App ที่ได้ไปใช้งาน
สำหรับเนื้อหาในการติดตั้ง เครื่องมือต่างๆ ในการใช้งาน Angular Project เช่น Visual Studio Code (VSCode)
การสร้าง Angular Project
    การสร้าง Angular Project ใหม่ ผ่าน Angular CLI (Angular command line interface) หรือที่เรียกว่าการใช้งานคำสัง
ผ่าน command line 
สร้างโปรเจค เราสามารถใช้คำสั่ง
ผ่าน commnad line ดังนี้
 
D:\projects>ng new my-web
การทดสอบรัน Angular App
    เสร็จแล้ว ทดสอบรัน app ผ่าน command line ดังนี้
 
D:\projects\>my-web ng serve
หลักนั้นให้เปิด เบาเซอร์
พิมพ์ localhost: 42000
ก็จะแสดงหน้า App ผ่านบราวเซอร์ขึ้นมา
Angular เป็น Component Base ทำให้โค๊ดมีคุณภาพสูง component มีความคล้าย MVC แต่ว่าจะเน้นที่การ reusability ซึ่งทำให้เราได้ประโยชน์ดังนี้
Reusability
Readability
Unit-test friendly
Maintainability
