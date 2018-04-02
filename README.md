# learngit

# feature/feature_name




ทำการย้าย branch ไปอยู่ที่ develop 
```
	 git co develop
```	 
ทำการสร้าง branch ชื่อ feature/feature_name
```
	 git co -b feature/feature_name
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
	 git commit -m "Addfeature login Test"
```
เช็คการเปลี่ยนแปลง โดยให้โชว์ค่า 1 บรรทัด	 
```
	 git log --oneline
```
ทำการเช็ค ว่า ไฟล์มีการ แก้ไข หรือ commit แล้ว  
```
	 git status
```	
ทำการอัปโหลดไฟล์ ไปที่ Github เพื่อทำการ merge ที่แก้ไข หรือเพิ่ม Featuer เข้าไปที่ branch develop 
```
	 git push origin HWhotfix/1.2
```
ทำการปริ้น ข้อความที่อยู่ในไฟล์ README.md ออกมาทาง terminal
```
	 cat README.md

```



# releae/v1.0
```
releae/v1.0

	 git co develop
	 git co -b releae/v1.0
```



# hotfix/v1.5

```
hotfix/v1.5

	 git co develop
	 git co -b hotfix/v1.5

```

