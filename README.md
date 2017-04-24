# Umbraco kurulumu
Visula studio da yeni proje olarak web application seçin.<br>
Şablon olarak empty,view engine ise MVC olsun.Proje açıldıktan sonra ister nuget package manager den isterseniz de package Manager
Console a şu komutu yazarak: ``` Install-Package UmbracoCms``` Umbraco yu projenize dahil edin.
Install-Package UmbracoCms yaz yüklenmeye başlasın
sonuna doğru bir soru soracak global.asax ın üzerine web.config yazılsın mı diye
cevap olarak console a ```Y``` yazıp enter a basın.(Özellikle view engine i MVC yaptığınızda bu soru karşınıza çıkıyor, farklı bir
seçenekte console ekrananında bu soru çıkmıyor. Daha sonra solution explorer(klasör penceresi sağda)show all files deyip,
şu klasörleri seç
>Umbraca<br>
>Umbraco_Client<br>
#### ve sağ tıklayarak include project deyip uygulamamıza bu klasörleri ekleriz. Sonra Build yapıp uygulamayı debug ederek Umbraco CMS i kurmaya başlarız.

#### NOT:Visual Studio da REsharper varsa, kapalı olması lazım uyumsuzluk çıkartıyor

