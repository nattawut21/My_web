## บทความ 
การใช้งาน Angular CLI ตั้งแต่ขั้นตอนการสร้าง Angular Project
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

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.2.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
