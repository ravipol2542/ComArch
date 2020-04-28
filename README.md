#                                                              CN210

### หัวข้อที่1. คำสั่ง Add ใน R-type
<br>คำสั่งใน MIPS มีทั้งหมด 3 ประเภท ประกอบด้วย R-format, I-format และ J-format ซึ่งแต่ละคำสั่งมีขนาด 32 บิท 
![รูปภาพประเภทของMIPS](https://www.researchgate.net/profile/Yul_Chu/publication/228942202/figure/fig2/AS:669511661412368@1536635427816/Instruction-formats-for-MIPS-architecture-1.png)
* ประเภทที่ 1  R-format  มีทั้งหมด 6 ส่วน คือ
1. op หรือ opcode (เลข 6 บิทแรก) หมายถึง ระบุการดำเนินการ ในประเภท R-format คือเลข 000000 
2. rs (5 บิท) หมายถึง รีจิสเตอร์ตัวแรก
3. rt (5 บิท) หมายถึง รีจิสเตอร์ตัวที่ 2
4. rd (5 บิท) หมายถึง รีจิสเตอร์ตัวที่เก็บผลลัพธ์จากการกระทำของ rs และ rt
5. shamt (5 บิท) หมายถึง จำนวนบิทที่ต้องการ shift แต่หากไม่มีการshift ค่าshamtจะเป็น 00000
6. funct (5 บิท) หมายถึง ระบุคำสั่งใน R-format ที่จะให้rs กระทำกับ rt
<br>ตัวอย่าง ADD $5,$1,$2  rs =$1 =00001, rt =$2 =00010, rd =$5 =00101
|op|rs|rt|rd|shamt|func|
|-----|------|------|------|------|------|
|000000|00001|00010|00101|00000|10000|

* ประเภทที่ 2  I-format
* ประเภทที่ 3  J-format

<br>[วิดีโอที่1 คำสั่งadd ใน R-type](https://youtu.be/pT1bIVJNtd4)

<br>**หัวข้อที่2.How CPU Work**

<br>[วิดีโอที่2 ขั้นตอนการทำงานของCPU](https://youtu.be/X4YcjFMqclM)

<br>**หัวข้อที่3. Multi-cycle VS Single-cycle**

<br>[วิดีโอที่3 การเปรียบเทียบระหว่าง Multi-cycle และ single cycle](https://youtu.be/f6bQtnDyrzQ)

<br>**หัวข้อที่4. Load word in Multi-cycle**

<br>[คลิปวิดีโอที่4 คำสั่งloadword ในMulti-cycle](https://youtu.be/DK0LAkcEjHc)

<br>**หัวข้อที่5. Branch of Equal in Multi-cycle**

<br>[วิดีโอที่5 คำสั่งBEQ ในMulti-cycle](https://youtu.be/Eh2OFieFIFA)

<br>**หัวข้อที่6. FSM controller in Multi-cycle**

<br>[วิดีดอที่6 FSM controller ในMUlti-cycle](https://youtu.be/zDQW-HyqBxg)

<br>**หัวข้อที่7. Pipelining**

<br>[วิดีโอที่7 Pipelining](https://youtu.be/3Bm1NIazgtc)
