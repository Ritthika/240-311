# 240-311_application
  Lucky Application Lottery Online 
  
สมาชิกในกลุ่ม
  1. 6310110415 นายฤทธิไกร ฮั่นสกุล
  2. 6310110443 นางสาววริศรา คงปรก
  3. 6310110625 นายณัฐภัทร อ่อนแก้ว

Backend
  - ใช้ morgan เก็บ log การใช้งาน
  - ใช้ gzip ในการบีดอัดข้อมูล
  - ใช้ mongodb เป็น ฐานข้อมูล
  - ใช้ body-paser ในการรับข้อมูล
  - ใช้หลักการของ CRUD
  
Frontend
  - ใช้ Static files เป็นส่วนประกอบ
  - ใช้ Components โดยแบ่งส่วนของ code HTML ย่อยๆ สำหรับส่วนหัว ส่วนแสดงตัวสลากกินแบ่งรัฐบาล หรือรูปแบบการแสดงผล และการกดรูปภาพมีการแสดงผลเป็น pop-up
    ภาพตัวอย่างการแสดงผลเป็น pop up
    ![image](https://user-images.githubusercontent.com/111529177/225994439-40bc7776-cfb4-4984-a501-053b367dcfca.png)
  - ใช้ Props ในการรับข้อมูลเข้ามาใช้งานในส่วนของ components ทำให้ React component หนึ่งสามารถ pass ข้อมูลต่างๆ 
    ไปอีก componentเมื่อมีการรับ props เข้ามาได้จะทำให้มีข้อมูลที่แตกต่างมาใช้งานใน components แต่ละที่
  - ใช้ States เป็นข้อมูลที่อยู่ภายใน components เป็น data ที่มีการใช้แค่ภายใน Component นั้นๆ โดยจะทำการเก็บข้อมูล 
    และยังสามารเปลี่ยนแปลงระหว่างการทำงานได้
  - ใช้ Events จัดการลำดับเหตุการณ์ ของ React Element
  - ใช้ From inputs สำหรับการทำการค้นหาข้อมูล ให้แสดงผลตามที่ต้องการ
    ภาพตัวอย่างการค้นหา
    ![image](https://user-images.githubusercontent.com/111529177/225992417-43126652-465f-425a-8cad-96dbdb72009b.png)
  - Build & Deploy
  - ภาพตัวอย่างการล็อกอินบัญชีผู้ใช้งาน
  ![image](https://user-images.githubusercontent.com/111529177/225994970-361d3451-d58f-41ba-a2ad-94719810a10f.png)

