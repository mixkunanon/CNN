# CNN

## Introduction

งานชิ้นนี้เป็นการศึกษาวิธีการ Objective Detection โดยการตรวจจับภาพพนักงานขนส่งอาหารและสิ่งของต่าง ๆ หรือ ไรเดอร์

## Data
Dataset: https://drive.google.com/file/d/1rfRW-fLsrcBeZohVVYFM4LAU0q1auY2a/view?usp=sharing

## Training
โมเดลที่ใช้ในการทำ Objective Detection ในงานนี้ได้แก่ RetinaNet และ YOLOv7

## Conclusion

| Model  |  mAP(Pretrained model) | Runtime(Freeze backbone) |
| ----  |  ---- | ---- |
| RetinaNet     |     0.116 | 0.106
| YOLOv7     |     0.152 | 0.611

จากการทดลองครั้งนี้สรุปได้ว่า โมเดล RetinaNet เมื่อ pretrained model นั้นจะให้ค่า mAP เท่ากับ 0.116 ซึ่งแตกต่างกันไม่มากจากหลังทำการ freeze backbone ที่ได้ค่า mAP 0.106 ส่วนโมเดล YOLOv7 หลังทำการ freeze backbone นั้นจะให้ค่า mAP เท่ากับ 0.611 ซึ่งสูงกว่าเมื่อ pretrained model ที่ให้ค่า mAP เท่ากับ 0.152 โดยผลที่ออกมาอาจเป็นเพราะจำนวน dataset ที่มีนั้นอาจจะไม่เพียงพอ หรือไม่ครอบคลุมในบาง class หรืออาจมีการวิเคราะห์การปรับค่าและทดลองที่น้อยไป หากมีการปรับปรุงส่วนที่กล่าวคาดว่าสามารถเพิ่มประสิทธิภาพของการตรวจจับของโมเดลทั้งสองได้ดียิ่งขึ้น

### ปล.รายละเอียดเพิ่มเติมของการทดลองแสดงใน Report

## Member
6310432002 ทรงคมกฤช ไชยกาล

6410412005 เดโช ศรีสวัสดิ์

6410412015 คุณานนต์ กลิ่นจันทร์หอม
