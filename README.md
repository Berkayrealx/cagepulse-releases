<p align="center"><img src="media/app-icon.png" width="96" alt="CagePulse"></p>
<h1 align="center">CagePulse</h1>
<p align="center">MMA takvimi, dövüşçüler ve maç istatistikleri.</p>
<p align="center"><b>Türkçe</b> · <a href="README.en.md">English</a></p>

## İndir

| Platform | Güncel paket | Gereksinim |
| --- | --- | --- |
| Android | [APK indir](https://github.com/Berkayrealx/cagepulse-releases/releases/latest/download/CagePulse-Android-arm64.apk) | Android 8.0+ · ARM64 |
| iPhone / iPad | [IPA indir](https://github.com/Berkayrealx/cagepulse-releases/releases/latest/download/CagePulse-iPhone-iPad.ipa) | iOS 15.1+ · kendi hesabınla imzalama gerekir |

[Tüm sürüm bilgileri ve indirmeler](https://github.com/Berkayrealx/cagepulse-releases/releases/latest)

Bu depo yalnızca uygulama paketleri, görseller ve kullanım belgeleri içindir. Uygulamanın kaynak kodu, API anahtarları, hesap bilgileri ve özel imzalama dosyaları burada yayımlanmaz.

## Uygulamadan görünümler

| Dövüşçü profili | Maç istatistikleri |
| :---: | :---: |
| <img src="media/fighter-profile.jpg" width="240" alt="Dövüşçü profili ve ölçüler"> | <img src="media/fight-stats.jpg" width="240" alt="Gerçek maç istatistikleri"> |

Görseller önceki sürümün telefon ölçüsündeki web önizlemesinden alınmıştır; 0.2.6 etkinlik sayfasının yeni düzenini göstermez. iPhone’daki yerel Liquid Glass efekti tarayıcı görsellerinde gösterilmez; Android sürümü standart siyah/kırmızı kontroller kullanır.

## Neler var?

- UFC/MMA etkinlik takvimi; afişli etkinlik sayfası, erken ön kart / ön kart / ana kart saatleri. Açıklanmayan saatler tahmin edilmez.
- Karttaki dövüşçü fotoğrafı veya adına dokunarak profil açma; geri dönüşte liste konumunu ve kart seçimini koruma.
- Kayarak sayfa geçişleri, iOS kenardan geri kaydırma, hareketli sekme çizgisi ve Hareketi Azalt desteği.
- META ve medya sıralamaları, açılır siklet paneli, P4P, kart/liste görünümü ve A–Z dövüşçü araması.
- Dövüşçü takibi, fiziksel karşılaştırma ve kariyer istatistikleri. Profilde şampiyonluk, P4P ve siklet rozetleri ile yayımlanan doğum tarihi, doğum yeri, UFC’ye çıkış tarihi ve bacak mesafesi.
- Tüm dövüşçüler için, kaynaktaki tüm organizasyonlardan maç geçmişi; kazanan, KO/TKO/submission/karar, raund ve süre bilgisi.
- Tam maç ve raund bazında toplam/önemli vuruş, yere alma, kontrol süresi, vuruş hedefleri ve pozisyon dağılımı. Oynanmayan raundlar pasif görünür.
- Saat bazlı ana kart, ön kart ve özel saat hatırlatmaları.
- Dövüşçünün sonraki maçına veya etkinlikte seçilen tek maça canlı başlangıç uyarısı. CagePulse ekranda açıkken çalışır.
- Gruplanmış ayarlar, ayrı dil ve bildirim sayfaları, uygulama içinden destek bağlantıları. Türkçe, İngilizce ve Brezilya Portekizcesi seçenekleri.
- iPhone/iPad: desteklenen iOS 26+ cihazlarda UIKit tabanlı yerel Liquid Glass düğmeleri, sistem alt menüsü ve dokuz tema.
- Android: cam efekti olmadan standart siyah/kırmızı tema ve düz alt menü.
- Görseller için disk/bellek önbelleği; gömülü 64 baş fotoğrafı, 65 orantılı tam boy görsel ve dört etkinlik afişi.
- Kapaklı haber kartları, sabit arama ve okundu filtreleri, kayıtlı haberler ve kişisel notlar.
- Fight Digitale ve MMA 101 Türkiye’nin herkese açık X gönderileri, gerçek görseller ve kaynak yayımladığında video oynatma.

## Kurulum

**Android**

1. Yukarıdaki APK’yı indir.
2. Dosyayı Android cihazda aç. Sistem isterse kullandığın tarayıcı/dosya yöneticisi için yükleme izni ver.
3. Önceki CagePulse kurulumu varsa aynı imzalı yeni paket üzerine güncellenebilir; verileri korumak için önce uygulamayı kaldırma.

**iPhone / iPad**

1. IPA’yı bilgisayarına indir.
2. Daha önce kullandığın iOS imzalama/kurulum aracında IPA’yı seçip kendi Apple hesabınla imzala ve yükle.
3. iOS isterse kendi geliştirici profilini güvenilir olarak işaretle ve Geliştirici Modu adımını tamamla.

IPA imzasız cihaz paketidir; App Store veya TestFlight dağıtımı değildir. Dosyaya iPhone’da dokunmak tek başına kurulum yapmaz. Apple şifreni, doğrulama kodunu veya token’larını GitHub sorunlarına yazma.

## İlk kullanım

1. **Etkinlikler** bölümünden yaklaşan veya geçmiş bir kart seç.
2. Dövüşçünün adına veya fotoğrafına dokunarak profilini, satırın kalan alanına dokunarak maç ayrıntılarını aç. Geçmiş karşılaşmalarda kazanan, bitiş yöntemi, raund ve süre doğrudan gösterilir.
3. **Dövüşçüler** bölümünde isim/siklet filtresiyle profil bul. **Maçlar** sekmesi kaynaktaki tüm geçmişi otomatik yükler. Bu ekranda sonuçlar her zaman açıktır; yüklenen maçlar cihazda saklanır.
4. **Ayarlar** bölümünden dili, iPhone’da **Temalar** sayfasından görünümü değiştir.
5. Dövüşçü profilinde **Sonraki maç → Maç başlayınca bildir** seçeneğine dokun. Etkinliğin alarm menüsünden **Tek maç** seçerek de aynı uyarıyı kurabilirsin. Bildirim izni gerekir.

## Veri ve mevcut sınırlar

Sıralamalar [UFC’nin resmî sıralama sayfasından](https://www.ufc.com/rankings), etkinlik afişleri, kart saatleri, dövüşçü biyografileri ve ayrıntılı raund istatistikleri UFC’den; fikstür ve yedek maç toplamları ESPN’den, haberler herkese açık X profilleri, ESPN ve RSS kaynaklarından gelir. META ve medya listeleri ayrı tutulur; P4P medya paneli olarak etiketlenir. Sıralama ekranında son kontrol zamanı gösterilir. Kaynak gecikmesi, eksik alanlar ve kart değişiklikleri olabilir. Kaynak KO ve TKO’yu ayırmıyorsa uygulama **KO/TKO** gösterir. Bulunmayan ölçüler veya istatistikler tahmin edilmez.

- Raund sekmeleri UFC verisiyle eşleşen maçlarda çalışır. Ayrıntılı veri alınamadığında mevcut maç toplamları gösterilir. Hakem puan kartları ayrı bir özellik olarak bu sürümde bulunmaz.
- Fight Digitale ve MMA 101 Türkiye gönderileri herkese açık X profil sayfalarından alınır. Bu sayfaların yapısı veya erişimi değişirse uygulama son alınan gönderileri gösterir. Kaynak satırı X profiline, gönderi düğmesi ilgili paylaşıma gider.
- Canlı başlangıç uyarısı, uygulama ekranda açıkken ESPN’de seçili eşleşmenin durumunu 20 saniyede bir kontrol eder. Kaynak gecikmesi uyarıyı geciktirebilir. Kilit ekranında canlı uyarı için sunucu push kurulumu gerekir.
- Topluluk, hesap eşitlemesi ve sunucu push hizmetleri bu dağıtımda etkin değildir.
- Sessiz mod/Odak ayarları normal bildirim sesini engelleyebilir.

CagePulse’un UFC, ESPN veya MMA360 ile resmî bağlantısı yoktur. Haberin başlığı, görselleri ve içerikleri ilgili yayıncılara aittir.

## Destek

- [GitHub üzerinden sorun bildir](https://github.com/Berkayrealx/cagepulse-releases/issues)
- Telegram: [@berkayrealx](https://t.me/berkayrealx)
- Discord: **@berkayrealx**

Sorun bildirirken uygulama sürümünü, cihaz modelini, işletim sistemini ve sorunun adımlarını yaz. Ekran görüntüsünde kişisel bilgileri gizle.

> GitHub’ın otomatik oluşturduğu “Source code” arşivleri yalnızca bu tanıtım deposunun belgelerini ve görsellerini içerir; uygulama kaynak kodunu içermez.
