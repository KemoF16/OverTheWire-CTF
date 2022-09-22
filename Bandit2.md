# السلام عليكم ورحمة الله وبركاته
## اهلا بكم فى سلسله حلول Bandit 
اليوم سوف نجتاز المستوى Bandit2

 1- لبدء التحدى يجب علينا ان نتصل بهذا المستوى  `ssh bandit2@bandit.labs.overthewire.org -p 2220` و الرقم السرى لهذا المستوى هو {**rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi**} 

 2-  هذا الامر سيساعدنا على عرض جميع الملفات والمستندات  `ls `

 3-لرؤيه حل هذا المستوى   سوف نقوم بنتفيذ هذا الامر `"cat "spaces in this filename `   او `cat spaces\ in\ this\ filename` 

هذا هو الحل {**aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG**}



لاحظ: عند استعمال هذا الامر `cat spaces in this filename` لن نستطيع  ان نرى محتوى الملف هذا لان التيرمنال سيترجم هذا الامر بالشكل التالى `cat spaces` وسيترجم بقيه اسم الملف `in this filename ` على انها اوامر جديده فلكى نتخطى هذه العقبه يحب علينا ان نضع `\` قبل المسافات او نضع اسم المف بداخل `""` او `''`
 


## Welcome To Bandit Serious 

Today we are going to solve **Bandit2**
1- start the chanllenge `ssh bandit2@bandit.labs.overthewire.org -p 2220` the password for this level is {**rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi**}
 
2- `ls ` to view all the directories and files , You are going to see file calls **spaces in this filename**    

3- `cat "spaces in this filename"` or `cat spaces\ in\ this\ filename` to read the file  , And here we go this is the flag  {**aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG**}

note:this command `cat spaces in this filename` will  not work because terminal will understand it like `cat spaces` and the rest of the file name which are `in this filename ` are new commands ,so to get through this problem we have to put `\` before spaces or to put the file name into `""`or `''`

