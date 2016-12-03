1.agile เน้นการทำงานกับลูกค้าและยอมรับการเปลี่ยนแปลงตลอดและยังไม่มีการทำเอกสาร
2.git และ github นั้นดีที่สุดแล้วในหลายๆเรื่อง
3.$ git checkout feature1
  $ git merge --no-ff feature
  $ git branch -d feature
  $ git push origin feature1
4.การเกิด conflict เป็นเรื่องธรรมดาเราต้องเตรียมรับมือกับมันให้ได้
5.abcde"a".."e"
6.การที่เราทำ web application เราอยากเก็บไว้บนระบบออนไลน์ การทำใส่ CD หากเกิดการหายหรือชำรุด เราจะลำบากในการนำมาใช้อีกครั้ง
7.กลไกมีตั้งนี้
1.	The browser issues a request for the /users URL.
2.	Rails routes /users to the index action in the Users controller.
3.	The index action asks the User model to retrieve all users (User.all).
4.	The User model pulls all the users from the database.
5.	The User model returns the list of users to the controller.
6.	The controller captures the users in the @users variable, which is passed to the indexview.
7.	The view uses embedded Ruby to render the page as HTML.
8.	The controller passes the HTML back to the browser.5
8.ข้อดีของ Rails เมื่อเทียบกับ Angular 1.Rails เขียนด้วยภาษาrubyซึ่งสั้นและเข้าใจง่ายกว่า
ข้อเสียของ Rails เมื่อเทียบกับ Angular 1.Rails มีการติดตั้งที่ซับซ้อนเข้าใจยาก
9.Heroku เป็น Platform as a Service (Paas) โดยรองรับภาษาโปรแกรมที่หลากหลาย เช่น  Ruby, PHP, Node.js, Python, Java, Clojure, Scala และยังสามารถสร้าง buildpack สำหรับภาษาอื่นๆได้ เช่น Lua ที่รันอยู่บน OpenResty ได้อีกด้วย มีบทบาทสำหรับเราคือ สามารถใช้งานได้ฟรี เราจึงลดต้นทุนในการพัฒนา web application

