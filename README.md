# Mernis
Mernis // E-Devlet Doğrulama Sistemi // Java GUI JFrame Demo Project


Java GUI (JFrame) öğrenimi için denediğim bir çalışma. Mernis E-Devlet WSDL sistemini gui ile görsel hale getirip bilgilerin tam olarak doldurulduğunda,
doğrulandı veya doğrulanmadı şeklinde dönüt veren bir program haline getirildi. 


Belli başlı basit düzeyde yapılan düzenlemelerin çıktıları;

Genel Görünümü:

![1](https://user-images.githubusercontent.com/71668283/118731115-5d24a600-b841-11eb-9741-161613283fef.png)


Doğru bilgiler verildiğinde:

![2](https://user-images.githubusercontent.com/71668283/118731177-7fb6bf00-b841-11eb-8d7b-9dd36460319a.png)


Yanlış bilgiler verildiğinde:

![3](https://user-images.githubusercontent.com/71668283/118731231-95c47f80-b841-11eb-84fb-9d54fb0cd3f5.png)


Tc. No 11 hane ile - Doğum Yılı bölümü 4 hane ile sınırlandırıldı ve daha fazla karater girilemiyor, ayrıca sadece rakam kabul ediyor.

![4](https://user-images.githubusercontent.com/71668283/118731551-b7be0200-b841-11eb-99e6-891c0e968d60.png)


Herhangi bir bölüm boş bırakıldığı zaman doğrula butonuna basınca boş olan bölümü ilk boşluktan son boş olan bölüme doğru sırayla hata verip uyarıyor. 
(Önce Ad boşsa Ad için daha sonra eğer ad dolduruldu soyad boşsa sıradaki o olduğu için onun hatasını veriyor her bölüm doldurulana kadar)

![5](https://user-images.githubusercontent.com/71668283/118731833-e6d47380-b841-11eb-814c-9e83c2afde04.png)



Projenin asıl amacı Java JFrame kısmını öğrenmek butonları ve text boxları kullanmak bunları da kullanırken proje fikri olarak 
mernisin doğrulama sistemini projeye entegre etmeyi öğrenmek amaçlandı.
