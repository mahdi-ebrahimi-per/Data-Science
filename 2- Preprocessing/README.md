# Doc

![Source 1](https://github.s3.ir-thr-at1.arvanstorage.com/mahdi-ebrahimi-per/Data-Science/2-%20Preprocessing/Missing%20data%20handling_1.png)

<div dir="rtl">

`def __init__` <br>
  
تابعی است که ورودی دیتاست رو میگیریم تا فانکشن های مورد نظرمون رو روش اعمال کنیم 
آدرسی که گرفتیم رو با فانکشنی به نام
`read_csv`
پانداس خوانده ایم رو میریزیم درون
یک متغیر به نام
`self.df`
پشت آن هم
self
میذاریم، چون قراره همه جا روی همین فانکشن اعمال شود
که در نهایت بتوانیم تمام فانکشن های مورد نظرمان رو، روی دیتاست اعمال کنیم و راحت ذخیره کنیم

محتویات درون

<div dir="rtl">
  
`self.df`
باید همیشه از جنش دیتا فریم پانداس باشد
```python
print(type(self.df))
```
[out: <class 'pandas.core.frame.DataFrame'>]
</div>
 
</div

