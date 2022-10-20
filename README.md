# Objective Detection

## Introduction

งานชิ้นนี้เป็นการศึกษา Convolutional Neural Network ที่ใช้ในการทำ Objective Detection ในการตรวจจับภาพพนักงานขนส่งอาหารและสิ่งของต่าง ๆ หรือ ไรเดอร์ โดยใช้โมเดล RetinaNet และ YOLO

## Data
Dataset: https://drive.google.com/file/d/1rfRW-fLsrcBeZohVVYFM4LAU0q1auY2a/view?usp=sharing

## Environment Setting
Google Colab with GPU runtimes setting

## Training
โมเดลที่ใช้ในการทำ Objective Detection ในงานนี้ได้แก่ RetinaNet และ YOLOv7

## Conclusion

| Model  |  mAP (Pretrained model) | mAP (Freeze backbone) |
| ----  |  ---- | ---- |
| RetinaNet     |     0.116 | 0.106 |
| YOLOv7     |     0.152 | 0.611  |

จากการทดลองครั้งนี้สรุปได้ว่า โมเดล RetinaNet เมื่อ pretrained model นั้นจะให้ค่า mAP เท่ากับ 0.116 ซึ่งแตกต่างกันไม่มากจากหลังทำการ freeze backbone ที่ได้ค่า mAP 0.106 ส่วนโมเดล YOLOv7 หลังทำการ freeze backbone นั้นจะให้ค่า mAP เท่ากับ 0.611 ซึ่งสูงกว่าเมื่อ pretrained model ที่ให้ค่า mAP เท่ากับ 0.152 คาดว่า หากมีการเพิ่มจำนวน dataset ให้มากขึ้น และครอบคลุมในแต่ละ class หรือมีระยะเวลาในการศึกษาการวิเคราะห์การปรับค่า parameter ต่าง ๆ และการทดลองที่มากขึ้น จะสามารถเพิ่มประสิทธิภาพการทำ Objective Detection ของโมเดลให้ดียิ่งขึ้น

### ปล.รายละเอียดเพิ่มเติมของการทดลองแสดงใน Report
https://github.com/scorepia/CNN/blob/main/Report_CNN_DADS7202.pdf

## Member
6310432002 ทรงคมกฤช ไชยกาล

6410412005 เดโช ศรีสวัสดิ์

6410412015 คุณานนต์ กลิ่นจันทร์หอม
