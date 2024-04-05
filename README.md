# Kaostatik Bernoulli Haritası Raporu
## Giriş

Kaostatik Bernoulli haritası, kaotik dinamik sistemler alanında önemli bir yere sahip olan basit bir ayrık zamanlı haritadır. Bu harita, basit doğrusal bir dönüşüm uygulayarak kaotik davranış sergiler. Bu raporda, Kaostatik Bernoulli haritasının özelliklerini, davranışlarını ve uygulamalarını inceleyeceğiz.

## Tanım

Kaostatik Bernoulli haritası, [0, 1] aralığındaki gerçel sayıları [0, 1] aralığına dönüştüren bir fonksiyondur. Aşağıdaki denklemle tanımlanır:

x_(n+1) = { 2 * x_n  if 0 <= x_n < 1/2
           1 - 2 * (x_n - 1/2)  if 1/2 <= x_n <= 1 }
Burada, x_n n. iterasyondaki girişi ve x_(n+1) (n+1). iterasyondaki çıktıyı temsil eder.

## Özellikleri

Kaostatik Bernoulli haritasının önemli özellikleri şunlardır:

Ergodisite: Harita, başlangıç değerinden bağımsız olarak uzun vadede [0, 1] aralığının tüm noktalarını ziyaret eder.
Duyarlılık terhadap başlangıç koşulları: Başlangıç değerlerindeki küçük değişiklikler bile uzun vadede büyük farklılıklara yol açar. Bu özellik, kaotik sistemlerin ayırt edici özelliğidir.
Periyodik olmayan: Harita, belli bir periyotla aynı noktaya dönmez.
Karmaşık davranış: Basit bir denkleme sahip olmasına rağmen, karmaşık ve öngörülemez davranış sergiler.
Davranış

Kaostatik Bernoulli haritasının davranışı, başlangıç değerine bağlı olarak değişir.

0 < x_0 < 1/2: Bu aralıktaki başlangıç değerleri için, x_n değerleri her iterasyonda iki katına çıkar ve sonunda 1'e yaklaşır.
1/2 <= x_0 <= 1: Bu aralıktaki başlangıç değerleri için, x_n değerleri her iterasyonda 1'den uzaklaşır ve sonunda 0'a yaklaşır.
Uygulamalar

Kaostatik Bernoulli haritası, çeşitli alanlarda uygulamalara sahiptir:

Kriptografi: Karmaşık davranışı nedeniyle, kriptografik sistemlerde güvenli anahtar üretimi için kullanılabilir.
Rastgele sayı üretme: Kaotik davranışı, gerçek rastgele sayı üretmek için kullanılabilir.
** sinyal işleme:** Karmaşık sinyalleri analiz etmek için kullanılabilir.
Doğal olayların modellenmesi: Bazı doğal olayların kaotik davranışını modellemek için kullanılabilir.
Sonuç

Kaostatik Bernoulli haritası, basit bir denkleme sahip olmasına rağmen zengin ve karmaşık davranış sergileyen bir kaotik sistemdir. Bu özellikleri nedeniyle, çeşitli bilimsel ve mühendislik alanlarında uygulamalara sahiptir.