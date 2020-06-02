Küçük bir işletmeye sahip bir müşteri tarafından personel takip sistemi istenmektedir. Müşteri firmasında depertmanların, personellerin ve personel izinlerinin kaydını tutmak ve takip etmek istemektedir.  Personellerin yıllık izinlerini de buradan takip etmek istiyor.   

Yukarıda bulunan senaryo .NET Core platformunda MVC mimarisi ile ve MSSQL veritabanı yapısı kullanarak geliştirilmiştir ve bu projede aşağıdaki işlemler yapılmıştır.
•	Personel CRUD işlemleri,
•	Personel İzin CRUD işlemleri,
•	Departman CRUD İşlemleri,
•	Personel listesi sayfasında yıllık izin hakkının gösterilmesi,
•	Personelin yıllık izinin hesaplanması 
o	(1-5 sene çalışan personeller için 14 gün, 5 yıldan fazla çalışan personeller için 20 gün. Olacak şekilde hesaplanmalıdır.)
o	Aynı departmanda aynı tarih aralıklarında yanlızca 1 personel izne çıkabilmelidir.
•	Personel yıllık izni hesaplanırken aldığı izinler dikkate alınarak hesaplanmalı.
