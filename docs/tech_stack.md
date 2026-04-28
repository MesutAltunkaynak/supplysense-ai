LAB 5: TEKNOLOJİ SEÇİMİ VE GEREKÇELENDİRME DOKÜMANI
Proje Adı: SupplySense AI: Otonom Envanter Yönetimi ve Öngörüsel Stok Analiz Sistemi

2.1 Mobil Geliştirme Teknolojisi
Seçim: Cross-platform (Flutter)

Gerekçe: Uygulamanın hem depo sahasındaki personel (Android) hem de ofis ortamındaki yöneticiler (iOS) tarafından kullanılabilmesi için tek kod tabanıyla her iki platforma da yüksek performanslı çıktı verebilen Flutter tercih edilmiştir. Bu seçim, geliştirme süresini optimize ederken yerel (native) uygulamaya yakın akıcı bir arayüz sağlar.

2.2 Veri Kaynağı
Seçim: Bulut tabanlı NoSQL veritabanı (Firebase Firestore)

Gerekçe: Depo ortamında yapılan stok güncellemelerinin tüm cihazlarda anlık (real-time) olarak senkronize edilmesi gerekmektedir. Firebase Firestore, internet kesintilerinde çevrimdışı veri saklama ve bağlantı geldiğinde otomatik eşitleme özelliği sunduğu için projenin sürekliliğine tam uyum sağlar.

2.3 Ek Araçlar ve Kütüphaneler
Google ML Kit: Mobil cihaz üzerinde gerçek zamanlı nesne tespiti ve barkod okuma (Görsel Denetim) için.

TensorFlow Lite: Geçmiş verileri işleyip cihaz üzerinde düşük gecikmeyle talep tahmini (Öngörüsel Analiz) yapabilmek için.

Provider/Riverpod: Uygulama içi veri akışını (state management) düzenli ve performanslı yönetmek için.

2.4 Gerekçelendirme
Teknoloji seçimleri yapılırken aşağıdaki kriterler temel alınmıştır:

Problemin Yapısı: Uygulamanın temel taşı olan görüntü işleme ve yapay zeka analizleri, mobil donanımı yormadan çalışmalıdır. Seçilen ML kütüphaneleri bu optimizasyonu sağlar.

Kullanıcı Sayısı Beklentisi: Başlangıçta KOBİ ölçekli depolar hedeflendiği için, Firebase gibi sunucusuz (serverless) bir yapı, kullanıcı sayısı arttıkça otomatik ölçeklenerek maliyet ve performans avantajı sunar.

Geliştirme Süresi: LAB süreci kısıtlı olduğu için, veritabanı altyapısıyla vakit kaybetmek yerine Firebase'in hazır çözümleri kullanılarak projenin ana fonksiyonu olan "Yapay Zeka Destekli Envanter Takibi"ne odaklanılmıştır.
