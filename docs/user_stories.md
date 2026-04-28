LAB 3: KULLANICI SENARYOLARI ANALİZ DOKÜMANI
Proje Adı: SupplySense AI: Otonom Envanter Yönetimi ve Öngörüsel Stok Analiz Sistemi
1. Giriş ve Amaç
Bu çalışma, LAB 2 aşamasında tanımlanan "stok yönetimindeki belirsizlik ve manuel hata"
problemlerine çözüm getirmek amacıyla kurgulanmıştır. Aşağıdaki senaryolar, uygulamanın farklı
kullanıcı rollerinin hedeflerine nasıl ulaştığını, herhangi bir teknik detay veya arayüz tasarımı
içermeden, tamamen kullanıcı etkileşimi odaklı olarak tanımlamaktadır.
Kullanıcı Senaryoları
Senaryo 1: Kamera Desteğiyle Raf Kontrolü ve Doğrulama
• Kullanıcı: Depo Saha Personeli
• Kullanıcının Amacı: Raftaki ürün sayısını fiziksel olarak tek tek saymak yerine dijital sistemle hızlıca
doğrulamak.
• Etkileşim Süreci:
1. Kullanıcı mobil uygulamaya giriş yapar.
2. Ana ekranda bulunan tarama modülünü aktif hale getirir.
3. Cihazın kamerasını kontrol etmek istediği rafa yönlendirir.
4. Sistemin raf üzerindeki ürünleri algılaması için görseli onaylar.
5. Sistem, görüntüden elde ettiği veriyi mevcut stok kaydıyla kıyaslar.
6. Kullanıcı, ekran üzerinde beliren "Eşleşme Sağlandı" veya "Eksik Ürün" uyarısını inceler.
7. Kullanıcı, tespit edilen bir fark varsa tek dokunuşla sayım sonucunu onaylayarak raporu tamamlar.
Senaryo 2: Gelecek Ayın Satış İhtiyacını Tahminleme
• Kullanıcı: İşletme Yöneticisi
• Kullanıcının Amacı: Gelecekte oluşabilecek talep artışlarını öngörerek hatalı sipariş verme riskini
ortadan kaldırmak.
• Etkileşim Süreci:
1. Kullanıcı yönetim panelindeki analiz bölümüne gider.
2. İncelemek istediği ürün kategorisini listeden seçer.
3. Sistemin sunduğu "Gelecek Dönem Öngörüsü" seçeneğini işaretler.
4. Sistem, geçmiş verileri işleyerek önümüzdeki ay için beklenen satış miktarını grafik olarak sunar.
5. Kullanıcı, grafik üzerinde oluşan tahmini talep zirvelerini inceler.
6. Sistem, bu tahmine dayanarak önerilen güvenli stok miktarını kullanıcıya gösterir.
7. Kullanıcı, elde ettiği bu öngörü verisini tedarik planına dahil eder.
Senaryo 3: Kritik Stok Uyarısı Üzerinden Sipariş Hazırlama
• Kullanıcı: Envanter Takip Sorumlusu
• Kullanıcının Amacı: Azalan ürünler için tedarik sürecini gecikmeden ve hatasız başlatmak.

• Etkileşim Süreci:
1. Kullanıcı, cihazına düşen "Stok Seviyesi Kritik" bildirimine tıklar.
2. Sistem, bitmek üzere olan ürünlerin listesini eksik miktarlarıyla birlikte listeler.
3. Kullanıcı, sistemin bu ürünler için otomatik hazırladığı tedarik önerisini açar.
4. Listede yer alan ürün adetlerini ve öncelik sıralamasını kontrol eder.
5. Kullanıcı, onay butonuna basarak dijital sipariş formunu kesinleştirir.
6. Sistem, oluşturulan bu formu ilgili birime iletilmek üzere hazır hale getirir.
