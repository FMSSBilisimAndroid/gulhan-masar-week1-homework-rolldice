Namespace
Namespace(İsim Alanı) Nedir?

Kısaca; aynı isimde farklı sınıflar oluşturmak için kullandığımız küme adlarına namespace denir.

İsim alanlarından; sınıflar, fonksiyonlar ve sabitler etkilenir. Çoğunlukla sınıflara tanımlanır.

Bir namespace’in yapısı aşağıdaki gibidir.

```
namespace namespace_ismi
{
// isim alanı içerisinde yer alacak sınıflar ve kod tanımlamaları bu alanda olacak.
}
```

XML de NameSpaces Nedir?

XML(Extensible Markup Language) bir etiketleme dilidir ve etiket isimleri programcı tarafından belirlenir. Xml namespace mekanizması aynı isimli xml elementlerini(element) ve xml özelliklerini(attribute) çakışma olmaması için ayırır.
Namespace tanımlarken URI(Uniform Resource Identifier) isim olarak verilir.


```
xmlns:android="http://schemas.android.com/apk/res/android"
xmlns:app="http://schemas.android.com/apk/res-auto"
xmlns:tools="http://schemas.android.com/tools"
```
xmlns:android isim alanı, Android platformu tarafından sağlanan özelliklere erişmek ve bunları kullanmak için kullanılır. Eğer namespace silinirse hiçbir özellik kullanılamaz.
xmlns:app isim alanı, uygulama kapsamında tanımlanan özel niteliklere erişmek için kullanılır.
xmlns:tools yalnızca geliştirme aşamasında çalışır, geliştiricilere yardımcı olacak bir araç olarak düşünebiliriz. Sadece geliştirme aşamasında çalışır. Bir uygulama paketlendiğinde, tüm araç özellikleri atılır!# gulhan-masar-week1-homework-rolldice
