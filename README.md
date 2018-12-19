# ![](/img/tr3.png)International-Tourist-Arrivals-to-Thailand
<a href=""><img src="img/travel.PNG" width="1000px"></a><br>
 <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<h2>PROJECT PROBLEM SOLVING IN INFORMATION TECHNOLOGY 1/2560</h2>
# ผลการดำเนินการ 
Start : 14 Nov 2018<br>
Complete : 19 Dec 2018
## วิดิโอ Present
- https://www.youtube.com/watch?v=np8hhAQCe1g&t=21s
## เว็ป Present
- https://nutpapat.github.io/International-Tourist-Arrivals-to-Thailand/docs/?fbclid=IwAR2Q5-e3dRDSfGfywA3VLR0WLurQJD5ycQ_XVECtvSbOCshMXm3bXK5aSVY <br>


## ![](/img/house.png)คำอธิบายโปรเจค
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;สวัสดีค่ะวันนี้กลุ่ม Poro so cute จะมานำเสนอการวิเคราะห์ข้อมูลในเรื่องของสถิตินักท่องเที่ยวที่เข้ามาเที่ยวในประเทศไทยตั้งแต่ปี 2013-2018 และรายได้ที่ประเทศไทยเราได้จากนักท่องเที่ยวในแต่ละประเทศ โดยเราจะวิเคราะห์ในแต่ละเดือนตั้งแต่มกราถึงธันวาว่ามีนักท่องเที่ยวตั้งแต่ปี2013-2018เข้ามาเที่ยวประเทศไทยจำนวนเท่าไหร่โดยเราจะแสดงข้อมูลออกมาเป็นทวีปว่าทวีปไหนเข้ามาเที่ยวประเทศไทยมากที่สุดและเพราะมีเหตุการณ์อะไรจึงทำให้มีนักท่องเที่ยวเข้ามาเที่ยวเป็นจำนวนมากในแต่ละเดือนและในแต่ละปีโดยเราเลือกใช้ภาษา python ในการเขียนโปรแกรมคำนวณ

## วัตถุประสงค์
- เพื่อวิเคราะห์จำนวนนักท่องเที่ยวที่เข้ามาเที่ยวประเทศไทยในแต่ละฤดู
- เพื่อวิเคราะห์จำนวนนักท่องเที่ยวที่เข้ามาเที่ยวประเทศไทยในแต่ละทวีป
- เพื่อวิเคราะห์รายได้ที่ได้จากนักท่องเที่ยวในแต่ละทวีป
- เพื่อวิเคราะห์รายได้ที่ได้จากนักท่องเที่ยวในในแต่ละประเทศ

## ใช้ข้อมูลจากไหน ?
ข้อมูลจาก
- https://www.mots.go.th/more_news.php?cid=411&filename=index
- http://www.tourism.go.th/view/1/%E0%B8%AA%E0%B8%96%E0%B8%B4%E0%B8%95%E0%B8%B4%E0%B8%99%E0%B8%B1%E0%B8%81%E0%B8%97%E0%B9%88%E0%B8%AD%E0%B8%87%E0%B9%80%E0%B8%97%E0%B8%B5%E0%B9%88%E0%B8%A2%E0%B8%A7/TH-TH

รูปแบบข้อมูล : ไฟล์ข้อมูลนามสกุล .csv ซึ่งประกอบด้วย
- Country : ประเทศต่างๆที่อยู่ในทวีปที่เราจะเลือก
- Years : ปีที่นักท่องเที่ยวเข้ามาเที่ยวตั้งแต่ 2013 - 2018
- Summary : สรุปข้อมูลนักท่องเที่ยวที่เข้ามา
- Receipts : รายได้ที่ได้รับจากนักเที่ยวที่เข้ามา

## สถิตินักท่องเที่ยวที่เข้ามาเที่ยวไทยในช่วงฤดูฝน
อธิบาย
- เราจะวิเคราห์นักท่องเที่ยวที่เข้ามาเที่ยวประเทศไทยตั้งแต่เดือนกุมภาถึงพฤษภา
เกิดไรขึ้นในปี ?
- สาเหตุที่นักท่องเที่ยวเข้ามามากเข้ามาน้อย

## สถิตินักท่องเที่ยวที่เข้ามาเที่ยวไทยในช่วงฤดูร้อน
อธิบาย
- เราจะวิเคราห์นักท่องเที่ยวที่เข้ามาเที่ยวประเทศไทยตั้งแต่เดือนมิถุนาถึงกันยา
เกิดไรขึ้นในปี ?
- สาเหตุที่นักท่องเที่ยวเข้ามามากเข้ามาน้อย

## สถิตินักท่องเที่ยวที่เข้ามาเที่ยวไทยในช่วงฤดูหนาว
อธิบาย
- เราจะวิเคราห์นักท่องเที่ยวที่เข้ามาเที่ยวประเทศไทยตั้งแต่เดือนตุลาถึงมกรา
เกิดไรขึ้นในปี ?
- สาเหตุที่นักท่องเที่ยวเข้ามามากเข้ามาน้อย

## สถิติรายได้ที่ประเทศไทยได้จากนักท่องเที่ยวต่างชาติ
อธิบาย
- เราจะวิเคราะห์รายได้ที่ประเทศไทยได้รับจากนักท่องเที่ยวต่างชาติของปี 2013 - 2018
- สรุปรายได้ที่ได้รับจากนักท่องเที่ยวของแต่ละทวีปและจัดอันดับ ซึ่งประกอบด้วย 7 ทวีป
- จัดอันดับรายได้แต่ละประเทศที่เข้ามาเที่ยวในประเทศไทย

## สรุป
- ฤดูทั้ง3ฤดู
- รายได้จากนักท่องเที่ยว

## ![](/img/collaboration.png)Team Members
| | รหัสนักศึกษา        | ชื่อ | นามสกุล |
|:-:| :-------------: |:----------:|:--------:|
| <a href=""><img src="img/group3.jpg" width="200px"></a> | 60070024    | นางสาวณัฐปภัสร์ | อยู่ยง |
| <a href=""><img src="img/group1.jpg" width="200px"></a> | 61070160    | นายภานุวัฒน์ | ศรีจันทร์วิจิตร์ |
| <a href=""><img src="img/group2.jpg" width="200px"></a> | 61070241    | นายสิรภพ | รักเกื้อ |

## ![](/img/administrator.png)Assistant Teacher
- Instructor: Chotipat Pornavalai
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;รายงานนี้เป็นส่วนหนึ่งของวิชา PROBLEM SOLVING IN INFORMATION TECHNOLOGY (06016314)
<br>เทคโนโลยีสารสนเทศ สถาบันเทคโนโลยีพระจอมเกล้าเจ้าคุณทหารลาดกระบัง
