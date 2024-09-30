# Armut---Association-Rule-Based-Recommender-System
Armut - Association Rule / Based Recommender System

# İş Problemi (Business Problem)
Türkiye’nin en büyük online hizmet platformu olan Armut, hizmet verenler ile hizmet almak isteyenleri buluşturmaktadır.
Bilgisayarın veya akıllı telefonunun üzerinden birkaç dokunuşla temizlik, tadilat, nakliyat gibi hizmetlere kolayca
ulaşılmasını sağlamaktadır.
Hizmet alan kullanıcıları ve bu kullanıcıların almış oldukları servis ve kategorileri içeren veri setini kullanarak
Association Rule Learning ile ürün tavsiye sistemi oluşturulmak istenmektedir.

# Veri Seti Hikayesi
Veri seti Armut firmasının müşterilerinin aldıkları servislerden ve bu servislerin kategorilerinden oluşmaktadır.
Alınan her hizmetin tarih ve saat bilgisini içermektedir.

# Veri Seti Hakkında
 UserId: Müşteri numarası
 ServiceId: Her kategoriye ait anonimleştirilmiş servislerdir. (Örnek : Temizlik kategorisi altında koltuk yıkama servisi)
 Bir ServiceId farklı kategoriler altında bulanabilir ve farklı kategoriler altında farklı servisleri ifade eder.
 Örnek: CategoryId’si 7 ServiceId’si 4 olan hizmet petek temizliği iken CategoryId’si 2 ServiceId’si 4 olan hizmet mobilya montaj)
 CategoryId: Anonimleştirilmiş kategorilerdir. (Örnek : Temizlik, nakliyat, tadilat kategorisi)
 CreateDate: Hizmetin satın alındığı tarih

# Amaç

Bu projenin temel amacı, Amazon gibi e-ticaret platformlarında satış sonrası kullanıcıların verdiği ürün puanlarının ve yorumların daha doğru, adil ve güvenilir bir şekilde değerlendirilmesini sağlamaktır. Doğru bir puanlama ve yorum sıralama sistemi sayesinde:

Müşteri Memnuniyeti: Alıcılar, daha güvenilir bilgiye dayalı alışveriş yaparak memnuniyetlerini artırabilir.
Satıcı Performansı: Satıcılar, ürünlerinin adil bir şekilde değerlendirilmesiyle daha fazla görünürlük kazanabilir ve satışlarını artırabilir.
Yanıltıcı Yorumların Engellenmesi: Doğru sıralama ile yanıltıcı ve gerçek dışı yorumlar ön planda olmayarak, hem müşteri kaybı hem de maddi kayıplar minimize edilir.

# Proje Aşamaları
1. Veri Toplama
Amazon platformundan ürün puanları ve kullanıcı yorumları gibi ilgili veriler toplanır. Bu veriler, ürünlerin performansını ve müşteri geri bildirimlerini anlamak için analiz edilecektir.

2. Veri Ön İşleme
Toplanan veriler üzerinde temizlik ve düzenleme işlemleri yapılır. Yanıltıcı, eksik veya hatalı veriler temizlenerek analiz için uygun bir veri seti oluşturulur.

3. Puanlama Modeli Geliştirme
Ürünlerin doğru bir şekilde puanlanmasını sağlamak için istatistiksel yöntemler ve makine öğrenimi algoritmaları kullanılarak bir model geliştirilir. Bu model, her ürünün gerçek müşteri memnuniyetini daha doğru bir şekilde yansıtmayı hedefler.

4. Yorum Sıralama Algoritması
Yorumların güvenilirlik ve fayda düzeyine göre sıralanmasını sağlamak amacıyla bir algoritma geliştirilir. Kullanıcıların verdiği "faydalı" oyları ve yorumların doğruluğu göz önünde bulundurularak, güvenilir yorumlar ön plana çıkarılır.

5. Uygulama ve Test
Geliştirilen puanlama modeli ve yorum sıralama algoritması gerçek zamanlı veriler üzerinde test edilir. Testler, algoritmaların performansını ve doğruluğunu değerlendirmek için kritik bir aşamadır.

6. Sonuçların Değerlendirilmesi
Sonuçlar analiz edilerek sistemin e-ticaret sitesi üzerindeki etkileri incelenir. Müşteri memnuniyeti, satış artışı ve kullanıcı deneyimindeki gelişmeler bu aşamada değerlendirilir.

Bu aşamaların tamamlanmasıyla, e-ticaret platformları hem müşteri hem de satıcılar için daha verimli ve güvenilir bir alışveriş deneyimi sunacaktır.
