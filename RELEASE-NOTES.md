# CagePulse 0.2.12

## Türkçe

- Etkinliklere **Tümü / UFC / PFL / OKTAGON** organizasyon filtreleri eklendi; yaklaşan ve geçmiş kartlarda çalışır.
- PFL'nin ESPN kartları ve resmî takvimindeki bölgesel etkinlikler birleştirilir. Aynı kart iki kez gösterilmez; önceki ESPN kimlikleri korunur.
- OKTAGON resmî takvimi, eşleşmeleri, fotoğrafları ve yayımlanan sonuçları okunur. Profilden yayımlanan yakın geçmiş ve kayıtlı maçlara erişilebilir.
- Yeni organizasyonların kartlarında da cihazda tahmin listesi kaydetme ve kaynakta bulunan kazanan/bitiş yöntemi bilgilerini görme desteklenir.
- Eksik eşleşmeler, saatler, raund/süre ve istatistikler üretilmez. Bazı bölgesel PFL etkinliklerinde kaynak henüz eşleşme sağlamıyor. Ayrıntılı UFC raund istatistikleri diğer organizasyonlara taşınmaz.
- 68 otomatik kontrol ve TypeScript kontrolü geçti. Telefon ölçüsündeki web önizlemesinde PFL kartı, OKTAGON filtresi ve tahmin ekranı kontrol edildi. Fiziksel cihaz testi yapılmadı.

## English

- Added **All / UFC / PFL / OKTAGON** organization filters for upcoming and past events.
- Merges ESPN PFL cards with regional events from the official PFL calendar, retaining ESPN identities and avoiding duplicate cards.
- Reads the official OKTAGON schedule, matchups, photos and published outcomes. Profiles show published recent history and saved fights.
- New promotion cards also support device-local prediction cards and published winner/finish information.
- Missing matchups, times, finish round/time and statistics are not invented. Some regional PFL events currently supply no matchups. UFC round statistics are not reused for other organizations.
- 68 automated checks and TypeScript passed. Phone-size web verification covered the PFL card, OKTAGON filter and prediction screen. Physical-device testing was not performed.

Android ARM64, Android 8.0+. Unsigned iPhone/iPad IPA, iOS 15.1+. Update the existing app using the same signing identity to retain local data.
