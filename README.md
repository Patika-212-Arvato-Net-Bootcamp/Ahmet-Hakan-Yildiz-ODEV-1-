# Araştırma Ödevi 1 - Sealed Class

1-Sealed Class'lar başka sınıflar tarafından miras alınamayan ama kendisi başka bir sınıftan miras alabilen sınıflardır.
Bir developer geliştirilmesini istemediği yani geliştirilmesinin son bulduğu classları mühürler daha doğrusu sealed class kullanır.
Örneğin --> 



sealed class 9mm : Bullet  // Sealed Class'ta tanımlanan kodlar sabit kodlardır.Geliştirici bu kodların üzerine kod yazılmasını ya da geliştirilmesini istemediği için mühürler.9mm'lik merminin her zaman 25 hp'lik hasar vermesini ve ücretinin her zaman 5 olmasını ister.Bu kodların üzerine de başka kodlar başka modüller eklemesini istemediğinden ekletmez.

{
	
	public int damage=22;
	public int price=5;


}


public class Uzi : Weapon //Normal class'larda ise geliştirici bunun daha da geliştirilebilir ya da başka özelliklerin de eklenebileceğini ifade eder.

{
	public int sarjor=35;
	this.BackColor = Color.Blue;
	this.Size=120;

}

public class BurnEffect : 9mm // Bu class 9mm Class'ından miras alamaz çünkü 9mm Class'ı mühürlenmiş yani Sealed Class olarak tanımlanmıştır, geliştirmeye kapalı sabit kodlardır.

{


}


# PAT-ARV-COMPUTER--AUTOMATION
PATİKA &amp; ARVATO .NET CORE BOOTCAMP / 1.HAFTA ÖDEV
----------------------------------------------------

.NET CONSOLE UYGULAMASI MODÜLLER \
\
1.0-TC Kimlik no girişi ile müşteri sipariş \
2.0-Giriş yaparken kayıtlı müşteri değilse kayıt ekranına yönlendirme\
3.0-ADMİN PANELİ\
3.1-Ürün ekleme\
3.2-Sipariş verme(Stoktan düşer,indirim uygulanır.)\
3.3-Siparişleri listeleme\
3.4-Müşteri Listeleme

