# CNN

## Introduction

งานชิ้นนี้เป็นการศึกษาวิธีการ Objective Detection โดยการตรวจจับภาพพนักงานขนส่งอาหารและสิ่งของต่าง ๆ หรือ ไรเดอร์

## Data
Dataset: https://drive.google.com/file/d/1rfRW-fLsrcBeZohVVYFM4LAU0q1auY2a/view?usp=sharing

## Training
โมเดลที่ใช้ในการทำ Objective Detection ในงานนี้ได้แก่ RetinaNet และ YOLOv7

## Conclusion

สรุปได้ว่า การทำ Objective Detection โดยใช้โมเดล RetinaNet และ YOLOv7 ในการตรวจจับพนักงานขนส่งพบว่า เมื่อทำการปรับ feature extractor โดยการ freeze backbone แล้ว ผลลัพธ์ที่ได้ของทั้ง 2 โมเดลให้ค่า Mean Average Precision (mAP) ที่ดีขึ้นกว่าตอน pretrained model โดยก่อนจะทำการ freeze backbone นั้นโมเดล RetinaNet และ YOLOv7 ให้ค่า mAP หลังการตรวจจับคือ 0.106 และ 0.152 ตามลำดับ หลังจากทำการ freeze backbone นั้นให้ค่า mAP คือ 0.116 และ 0.611 ซึ่งเพิ่มขึ้นอย่างเห็นได้ชัด

### ปล.รายละเอียดเพิ่มเติมของการทดลองแสดงใน Report

## Member
6310432002 ทรงคมกฤช ไชยกาล

6410412005 เดโช ศรีสวัสดิ์

6410412015 คุณานนต์ กลิ่นจันทร์หอม
