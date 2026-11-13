# CagePulse 0.2.11

## Türkçe

- Gelecek yılın maçlarını dışarıda bırakan tarih sınırı düzeltildi. Duyurulmuş etkinlikler yaklaşık üç yıl ileriye kadar sorgulanır; UFC 336 Van–Kape takvimde yer alır.
- Açılışta, uygulamaya dönünce ve uygulama ekranda açıkken beş dakikada bir yenileme. Son tam takvim güncelleme zamanı gösterilir. Kısmi bağlantı hatası gelecekteki kayıtlı kartları silmez.
- Etkinlikte **Bu karta tahmin yap**: tek maç veya karttan istediğin seçimleri, isteğe bağlı bitiş yöntemi ve raundla kaydet. **Profil → Tahminlerim** üzerinden kazanan/yöntem/raund doğruluğunu ayrı gör.
- Tahminler cihazda saklanır, etkinlik başlangıcında kilitlenir. Eksik sonuçlar bekler; doğrulanmış iptal veya rakip değişikliği kayıp sayılmaz. Hesaplar arası tahmin eşitlemesi yoktur.
- Haberler ve Profil içinde kaynaklı **Eşleşme gündemi**. Karşılaşma olasılığı yüzdesi uydurulmaz. Erişilebilir akışta uygun haber bulunması gerekir.

## English

- Fixed the date boundary excluding next-year cards. The schedule queries announced events roughly three years ahead and includes UFC 336 Van vs. Kape.
- Refresh on launch, return to foreground and every five minutes while active. Shows the last complete schedule refresh; partial outages preserve cached future cards.
- **Predict this card** saves any subset of an event with optional finish method and round. **Profile → My predictions** grades winner, method and round separately.
- Prediction cards are device-local and lock at event start. Missing outcomes stay pending; confirmed cancellations/replacements are void. No cross-device prediction sync.
- Sourced **Matchup watch** in News and Profile. No invented matchup probability percentages; matching accessible news must be available.

Android ARM64, Android 8.0+. Unsigned iPhone/iPad IPA, iOS 15.1+. Update the existing app using the same signing identity to retain local data. Physical-device testing was not performed for this release.
