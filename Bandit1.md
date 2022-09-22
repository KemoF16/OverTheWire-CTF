# السلام عليكم ورحمة الله وبركاته
## اهلا بكم فى سلسله حلول Bandit 
اليوم سوف نجتاز المستوى Bandit1

 1- لبدء التحدى يجب علينا ان نتصل بهذا المستوى  `ssh bandit1@bandit.labs.overthewire.org -p 2220` و الرقم السرى لهذا المستوى هو {**NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL**} 

 2-  هذا الامر سيساعدنا على عرض جميع الملفات والمستندات  `ls `

 3-لرؤيه حل هذا المستوى   سوف نقوم بنتفيذ هذا الامر `- > cat`   

هذا هو الحل {**rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi**}



لاحظ: عندما ننفذ هذا الامر ` - cat` لن يعمل لان التيرمنال سيترجم هذا الامر على انه باراميتر ولتفادى هذا الخطأ نضع علامه   **>** ليتجم هذا الامر على ان مابعد العلامه هو اسم الملف   


---

## Welcome To Bandit Serious 

Today we are going to solve **Bandit1**


2- `ls ` to view all the directories and files , You are going to see file calls **-**    

3- `cat < -` to read the file  , And here we go this is the flag  "rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi"

note: this command `cat - ` will not work because linux going to interpret **-** as a parameter not as a file name but when you do it like this `cat < -` it will interpret it as a file name 

---
