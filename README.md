# LearnByNewbie
สวัสดีครับ คุณเป็นคนที่เราอยากให้ดูว่าเราได้เรียนรู้อะไรบ้าง

## เราสามารถปรับ README.md จากเว็บไซต์ README.so
- [README.so](https://readme.so/editor)

# การใช้งาน Git ใน terminal
## การเชื่อมต่อกับ Repo ของเรา
`
git remote add origin https://github.com/SFtraktorFS/Learn-Github-by-Newbie.git
`
## การ commit การเปลี่ยนแปลง 
```
git add .  // git add file
git commit -am "message" 
```
โดยต้องใส่ message เข้าไปเพื่อทำให้เราเข้าใจการเปลี่ยนแปลงของเรา

`git add <>` คือการนำไฟล์เข้าสู่การ commit โดย <> คือไฟล์ที่จะถูกส่ง ถ้าเป็น . คือไฟล์ทั้งหมด 

`-am` คือการเพิ่มไฟล์ที่ถูกเปลี่ยน + เขียนข้อความ
## การ push เข้าไปใน Github
`
git push origin main 
`