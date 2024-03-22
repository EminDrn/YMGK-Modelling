# YMGK-Modelling
### Tent Map - Emin Duran (200541069)
### Giriş:
Çadır haritası, dinamik sistemleri temsil etmek için kullanılan matematiksel bir kavramdır. Özellikle kaos teorisini incelemek için oldukça kullanışlıdır. Çadır haritası, bir boyutta uygulanan parça doğrusal bir fonksiyondur. Kullanılan μ parametresine bağlı olarak karmaşık davranışlar gösterebilir. Görsel olarak fonksiyonun grafiği bir çadır şeklini andırır, bu nedenle bu isimle anılır.

![image](https://github.com/EminDrn/YMGK-Modelling/assets/115322253/b9a727e2-8235-48fb-80fc-f67e35e759b8)


### Tanım:

Matematikte μ parametreli çadır haritası , μ ile tanımlanan gerçek değerli fonksiyondur .

![image](https://github.com/EminDrn/YMGK-Modelling/assets/115322253/3371a454-35cc-4970-a2a5-9e71d7c2e1fe)

Çadır haritası, bir boyutta x ∈ [0, 1] aralığında tanımlanan parça doğrusal bir fonksiyondur. Fonksiyonun formülü şu şekildedir:

![image](https://github.com/EminDrn/YMGK-Modelling/assets/115322253/059fb96c-5fd4-4050-ae53-f8176a3d3f90)

### Nasıl çalışır?

burada μ pozitif bir gerçek sabittir. Örneğin μ = 2 parametresi seçildiğinde, f μ fonksiyonunun etkisi, birim aralığı ikiye katlama, ardından ortaya çıkan aralığı [0, 1/2] uzatarak aralığı tekrar elde etme işleminin sonucu olarak görülebilir. [0, 1]. Prosedür tekrarlandığında, aralığın herhangi bir x 0 noktası, yukarıda açıklandığı gibi yeni ardışık konumlar alır ve [0, 1]'de bir x n dizisi oluşturur .


### Davranış ve Karmaşıklık:

μ değerine bağlı olarak çadır haritası tahmin edilebilirden kaotike kadar değişen bir dizi dinamik davranış gösterir.

- μ < 1: Sabit nokta: Sistem, her başlangıç değerinden 0'a yakınsar.
- μ = 1: Sabit noktalar: 0 ve 1/2 değerleri sabit noktadır.
- 1 < μ < √2: Julia kümesi: Sistem, μ - μ^2/2 ve μ/2 arasındaki aralıkları kendilerine eşler.
- √2 < μ < 2: Kararsız periyodiklik: Yörüngeler kararsızdır ve yakındaki noktalar onlardan uzaklaşır.
- μ > 2: Kaos: Yörüngeler öngörülemez ve rastgele görünür.

Daha detaylı anlatıcak olursak: 

- Eğer μ 1 ile 2'nin karekökü arasındaysa, sistem μ − μ 2/2 ve μ/2 arasındaki aralıkları kendilerine eşler. Bu aralıklar kümesi haritanın Julia kümesidir ; yani bu haritanın altındaki gerçek doğrunun en küçük değişmez alt kümesidir. Eğer μ 2'nin karekökünden büyükse, bu aralıklar birleşir ve Julia kümesi μ − μ 2/2 ile μ/2 arasındaki aralığın tamamı olur (çatallanma diyagramına bakın).

![image](https://github.com/EminDrn/YMGK-Modelling/assets/115322253/e94237d0-090e-475f-ade0-4b515704c80d)

- Eğer μ 1 ile 2 arasındaysa, [μ − μ 2/2 , μ/2] aralığı hem periyodik hem de periyodik olmayan noktaları içerir, ancak tüm yörüngeler kararsızdır (yani yakındaki noktalar yörüngelere doğru gitmek yerine onlardan uzaklaşır). ). μ arttıkça daha uzun uzunluklara sahip yörüngeler ortaya çıkar. Örneğin:

![image](https://github.com/EminDrn/YMGK-Modelling/assets/115322253/b2f7046d-bcaa-4610-9a1f-ba6b345cce6d)

- Eğer μ 2'den büyükse haritanın Julia kümesinin bağlantısı kesilir ve [0, 1] aralığı içinde bir Cantor kümesine bölünür. Julia kümesi hala sonsuz sayıda hem periyodik olmayan hem de periyodik noktalar (herhangi bir yörünge uzunluğu için yörüngeler dahil) içerir, ancak [0, 1] içindeki hemen hemen her nokta artık sonunda sonsuza doğru ıraksayacaktır. Kanonik Cantor kümesi (birim çizgisinin alt kümelerinden ortadaki üçte birlerin art arda silinmesiyle elde edilir), μ = 3 için çadır haritasının Julia kümesidir.

### Uygulamalar:

Çadır haritası, kaos teorisinin birçok farklı alanında uygulamaya sahiptir. Örneğin:

- Hava durumu tahmini

- Finansal piyasaların analizi

- Biyolojik sistemlerin modellenmesi

- Kriptoloji

### Güçlü Yönleri (Strengths):

Basitlik: Çadır haritası, tek bir parametre (μ) ile tanımlanan basit bir matematiksel yapıya sahiptir. Bu basitlik, karmaşık kaotik davranışları anlamayı kolaylaştırır.
Çok yönlülük: Çadır haritası, kaotik davranış sergileyen çeşitli dinamik sistemleri modellemek için kullanılabilir. Bu nedenle, meteoroloji, finans ve biyoloji gibi farklı alanlarda uygulamalara sahiptir.
Görselleştirme kolaylığı: Çadır haritasının davranışları, görselleştirilmesi ve anlaşılması kolay olan grafiklerle temsil edilebilir. Bu, karmaşık kavramları daha erişilebilir hale getirir.
Kaotik davranışın anlaşılması: Çadır haritası, kaotik sistemlerin temel özelliklerini ve hassas başlangıç koşullarına duyarlılığı göstererek kaos teorisinin anlaşılmasına katkıda bulunur.

### Zayıf Yönleri (Weaknesses):

Basitleştirme: Çadır haritası, gerçek dünyadaki karmaşık sistemleri basitleştirilmiş bir şekilde temsil eder. Bu basitleştirme, gerçek dünyadaki kaotik davranışların tüm nüanslarını yakalamayabilir.
Kısıtlı tahmin gücü: Kaosun doğası gereği, çadır haritası uzun vadede sistemin davranışını tahmin etmekte güçlük çeker. Bu, özellikle kaotik sistemlerin gerçek dünya uygulamalarında bir sınırlama olarak görülebilir.
Analiz karmaşıklığı: Belirli μ değerlerinde, çadır haritasının davranışları oldukça karmaşık hale gelebilir. Bu durum, sistemin analiz edilmesini ve yorumlanmasını zorlaştırabilir.

### Fırsatlar (Opportunities):

Yeni uygulamaların keşfi: Çadır haritasının farklı disiplinlerdeki potansiyel uygulamaları henüz tam olarak keşfedilmemiştir. Yeni araştırmalar, çadır haritasının daha geniş bir yelpazede kullanılmasına yol açabilir.
Karmaşık sistemlerin analizi: Çadır haritası gibi modellerin geliştirilmesi, karmaşık sistemlerin davranışlarını daha iyi anlamamıza ve tahmin etmemize yardımcı olabilir. Bu durum, çeşitli bilimsel alanlarda önemli gelişmelere yol açabilir.
Eğitim aracı olarak kullanımı: Çadır haritasının basit yapısı ve kaotik davranışları göstermesi, onu kaos teorisi ve dinamik sistemler gibi konuları öğretmek için etkili bir araç haline getirebilir.


### Tehditler (Threats):

Yanlış yorumlanma: Çadır haritasının davranışlarının yanlış yorumlanması, kaotik sistemler hakkındaki yanlış bilgilere yol açabilir. Bu durum, kaotik sistemlerin gerçek dünyadaki uygulamalarında hatalara neden olabilir.
Daha karmaşık modellerin rekabeti: Çadır haritası gibi basit modeller, daha karmaşık ve gerçek dünya sistemlerini daha iyi temsil eden modellerin geliştirilmesiyle rekabete girebilir. Bu, çadır haritasının kullanım alanlarını sınırlayabilir.
Kısıtlamaların anlaşılması: Çadır haritasının bir model olduğunu ve gerçek dünyadaki sistemlerin tüm karmaşıklıklarını tam olarak yansıtmadığını unutmamak önemlidir. Bu sınırlamaların anlaşılmaması, modelin yanlış kullanılmasına neden olabilir.


### Sonuç:

Çadır haritası, basit bir matematiksel fonksiyon olmasına rağmen, kaos teorisinin temel kavramlarını ve karmaşık dinamik sistemlerin davranışlarını anlamamıza yardımcı olan güçlü bir araçtır. Bu basit modelin sunduğu zengin ve karmaşık davranışlar, kaotik sistemlerin doğası hakkında önemli bilgiler verir. 

Çadır haritası, meteorolojiden finans piyasalarına, biyolojiden kriptografiye kadar geniş bir yelpazede uygulama alanına sahiptir. Farklı disiplinlerde kaotik sistemleri modellemek ve analiz etmek için kullanılmaktadır.

Sonuç olarak çadır haritası, basit bir matematiksel modelin arkasında yatan karmaşıklığın ve güzelliğin bir örneğidir. Kaos teorisinin ve dinamik sistemlerin incelenmesinde önemli bir rol oynamaktadır ve gelecekte de birçok yeni keşfe yol açması muhtemeldir.

