# learngit

# hotfix/hotfix_name

ทำการย้าย branch ไปอยู่ที่ develop 
```
	 git co develop
```	 
ทำการสร้าง branch ชื่อ hotfix/hotfix_name
```
	 git co -b hotfix/hotfix_name
```	 

ทำการเปิดไฟล์ README.md ด้วย editor ที่มีในเครื่อง
```	 
	 subl README.md 
```
ทำการเช็คดูว่ามีไฟล์ README.md การเปลี่ยนแปลงหรือไม่
```	 
	 git diff
```
ทำการ ADD ไฟล์ ทั้งหมดที่อยู่ในโฟลเดอร์ นั้นๆ
```
	 git add .
```
ทำการ ยืนยัน ไฟล์ ว่าต้องการบันทึกเป็นแบบนี้	 
```
	 git commit -m "Edit Code Bug"
```
เช็คการเปลี่ยนแปลง โดยให้โชว์ค่า 1 บรรทัด	 
```
	 git log --oneline
```
ทำการเช็ค ว่า ไฟล์มีการ แก้ไข หรือ commit แล้ว  
```
	 git status
```	
ทำการอัปโหลดไฟล์ ไปที่ Github เพื่อทำการ merge ที่แก้ไข code ที่พบว่าทำงานผิดพลาด เข้าไปที่ branch develop และ master (pust เสร็จ ทำบนเว็ป Github)
```
	 git push origin hotfix/hotfix_name
```
ทำการย้าย branch ไปอยู่ที่ develop 
```
	 git co develop 
```
ทำการ pull เพื่อให้ อัปเดรตจาก server มา ที่เครื่องของเรา
```
     git pull origin develop
```
ทำการย้าย branch ไปอยู่ที่ master
```
     git co master
```
ทำการ pull เพื่อให้ อัปเดรตจาก server มา ที่เครื่องของเรา
```
     git pull origin master
```
ทำการปริ้น ข้อความที่อยู่ในไฟล์ README.md ออกมาทาง terminal
```
	 cat README.md

```


