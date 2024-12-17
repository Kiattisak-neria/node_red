# node_red
การใช้ node red เพื่อเป็น dashboard และใช้ในการเป็นตัวกลางในการสิ้อสาร

<br/>


## <a name="content"></a> สารบัญ
1. [การติดตั้ง node red](#InN)
2. [การติดตั้งไลบรารี่](#library)
3. [การ import ไฟล์ .json ลงไปยัง node red](#import)
  
<br/>

## <a name="InN"></a> การติดตั้ง node red
1. การทำการติดตั้ง node red หรือ Node.js สามารถโหลดได้จากเว็บไซต์ https://nodejs.org/en/ 
<p align="center">
<img src=https://github.com/user-attachments/assets/a71f7548-11bb-4fe1-9d39-3693408edd54>

2. เมื่อทำการดาวโหลดเสร็จจึงทำการติดตั้ง
3. ทำการเปิด Command promp เพื่อทำการติดตั้งเครื่องมือเพิ่มเติม
4. ทำการเช็คเวอร์ชั่นของ Node.js โดยการใช้คำสั้ง node --version ใน Command promp
<p align="center">
<img src=https://github.com/user-attachments/assets/74e6a2cf-7bcd-4002-8988-01ce0041a206>

5. ใช้คำสั้ง npm --version เพื่อตรวจสอบเวอร์ชันของ npm(node package manager คือเครื่องเมือที่ใช้ในการจัดเก็บ package ของ Node.js)
<p align="center">
<img src=https://github.com/user-attachments/assets/6a2a908a-9d2d-4cd5-9fe7-19d211cb19e1>

6. ทำการติดตั้ง Node-RED ลงในคอมพิวเตอร์โดยใช้คำสั่ง npm install --g -–unsafe-perm Node-RED ใน Command promp
<p align="center">
<img src=https://github.com/user-attachments/assets/9e985a46-8fff-476d-b616-b14fcc84fd37>

7. เข้าใช้งาน Node-RED โดยใช้คำสั่ง Node-RED ใน Command promp เมื่อเปิดการทำงานเสร็จสิ้นจะขึ้นตัวเลข IP ให้คัดลอกไปวางใน Tab ค้นหาบน Google chrome เพื่อเข้าใช้งาน Node-RED 
<p align="center">
<img src=https://github.com/user-attachments/assets/9c8db505-c0b5-4c5b-88f0-81bb7fb5929b>


<br/>

## <a name="library"></a> การติดตั้งไลบรารี่
การทำการ import ไฟล์ข้างต้นจำเป็นต้อดาวโหลดไลบรารี่ซึ่งสามารถดาวโหลดได้ด้วยการเลือกที่ เครื่องมายสามขีด > Manage pelette > Install > ทำการค้นหา > install
<p align="center">
<img src=https://github.com/user-attachments/assets/5bdba33c-c5a8-415d-bf93-c9b43a7f531e>

ไลบรารี่ที่จำเป็นต้องใช้มีดังต่อไปนี้
1. node-red-node-ui-list
2. node-red-dashboard
3. node-red-contrib-ui-media
4. node-red-contrib-ui-level
5. node-red-contrib-ui-led
6. node-red

<br/>

## <a name="import"></a> การ import ไฟล์ .json ลงไปยัง node red
เมื่อทำการมำให้ node red สามารถใช้งานได้ จึงสามารถทำการ import โดยการที่เลือกที่สามขีด > import > select a file to import > เลือกไฟล์ > improt
<p align="center">
<img src=https://github.com/user-attachments/assets/26599967-a780-408d-9901-2f8f937aba0c>

<br/>
