# Umbraco kurulumu
Visula studio da yeni proje olarak web application seçin.<br>
Şablon olarak empty,core referance ise MVC olsun.Proje açıldıktan sonra ister nuget package manager den isterseniz de package Manager
Console a şu komutu yazarak: ``` Install-Package UmbracoCms``` Umbraco yu projenize dahil edin.
Install-Package UmbracoCms yaz yüklenmeye başlasın
sonuna doğru bir soru soracak global.asax ın üzerine web.config yazılsın mı diye
cevap olarak console a ```Y``` yazıp enter a basın.(Özellikle core referance ı MVC yaptığınızda bu soru karşınıza çıkıyor, farklı bir
seçenekte console ekrananında bu soru çıkmıyor. Daha sonra solution explorer(klasör penceresi sağda)show all files deyip,
şu klasörleri seç<br>
**Umbraca**<br>
**Umbraco_Client**<br>
ve sağ tıklayarak include project deyip uygulamamıza bu klasörleri ekleriz. Sonra Build yapıp uygulamayı debug ederek Umbraco CMS i kurmaya başlarız.

**NOT**:Visual Studio da REsharper varsa, kapalı olması lazım uyumsuzluk çıkartıyor<br>

## **Localhost için IIS ayarları**<br>
![1](https://raw.githubusercontent.com/melihs/Umbraco_CMS_ASP.NET-MVC/master/IIS_ayarlari(localhost_icin)/1.png)
![2](https://raw.githubusercontent.com/melihs/Umbraco_CMS_ASP.NET-MVC/master/IIS_ayarlari(localhost_icin)/2.png)
![3](https://raw.githubusercontent.com/melihs/Umbraco_CMS_ASP.NET-MVC/master/IIS_ayarlari(localhost_icin)/3.png)
![4](https://raw.githubusercontent.com/melihs/Umbraco_CMS_ASP.NET-MVC/master/IIS_ayarlari(localhost_icin)/4.png)
![5](https://raw.githubusercontent.com/melihs/Umbraco_CMS_ASP.NET-MVC/master/IIS_ayarlari(localhost_icin)/5.png)
