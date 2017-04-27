# Umbraco kurulumu
Visula studio da yeni proje olarak web application seçin.<br>
Şablon olarak empty,core referance ise MVC olsun.Proje açıldıktan sonra ister nuget package manager kullanarak isterseniz de package Manager
Console a şu komutu yazarak: ``` Install-Package UmbracoCms``` Umbraco yu projenize dahil edin.
Umbraco ve bileşenleri yüklenmesinden sonra console ekranında, global.asax ın üzerine web.config yazılsın mı? diye bir soruyla karşılaşacaksınız.Cevap olarak ```Y``` komutunu vermelisiniz.(Özellikle core referance ı MVC yaptığınızda bu soru karşınıza çıkıyor, farklı bir seçenekte console ekrananında bu soru çıkmıyor. Daha sonra solution explorer(klasör penceresi sağda)show all files seçeneğiyle
şu klasörleri seçip<br>
**Umbraca**<br>
**Umbraco_Client**<br>
include ederek, uygulamamıza bu klasörleri ekleriz.Son olarak da projemizi derleyerek Umbraco CMS i kurmaya başlarız.

**NOT**:Visual Studio da REsharper varsa, kapalı olması lazım uyumsuzluk çıkartıyor<br>

## **Localhost için IIS ayarları**<br>
![1](https://raw.githubusercontent.com/melihs/Umbraco_CMS_ASP.NET-MVC/master/IIS_ayarlari(localhost_icin)/1.png)
![2](https://raw.githubusercontent.com/melihs/Umbraco_CMS_ASP.NET-MVC/master/IIS_ayarlari(localhost_icin)/2.png)
![3](https://raw.githubusercontent.com/melihs/Umbraco_CMS_ASP.NET-MVC/master/IIS_ayarlari(localhost_icin)/3.png)
![4](https://raw.githubusercontent.com/melihs/Umbraco_CMS_ASP.NET-MVC/master/IIS_ayarlari(localhost_icin)/4.png)
![5](https://raw.githubusercontent.com/melihs/Umbraco_CMS_ASP.NET-MVC/master/IIS_ayarlari(localhost_icin)/5.png)
