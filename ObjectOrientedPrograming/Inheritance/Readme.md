#Inheritance(Kalıtım) Nedir
OOP'nin en önemli özelliğidir.Üretilen nesneler farklı nesnelere özelliklerini aktarabilmekte ve böylece hiyerarşik bir düzenleme yapılabilmektedir.

Aynı aile grubundan gelen nesnelerin ya da yatayda eşit seviyede olan tüm olguların benzer özelliklerini tekrar tekrar her birinde tanımlamaktansa bir üst sınıfa tanımlanmasını ve her bir sınıfın bu özellikleri üst sınıftan kalıtımsal olarak almasını sağlamaktadır.

Örnek olarak kadın ve erkek insandan türer.
bir diğer örnek insan ve hayvan canlıdan kalıtım alır.Böyle düşünebiliriz..


#C# Programlama Dilinde Kalıtım
C# Dilinde kalıtım sınıflara özel bir niteliktir.
Yani bir sınıf sade ve sadece bir sınıftan kalıtım alabilir.


#C#'da Kalıtım Nasıl Alınır 
C#'da iki sınıf arasında kalıtımsal ilişki kurabilmek için ":" operatörü kullanılmaktadır.
Örneğin;
class Araba 
{
	................
	................
	................
}

class Opel : Araba   //Opel sınıfı Araba sınıfından kalıtım alsın dedik.  
{

}