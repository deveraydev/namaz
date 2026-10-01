# RÜKÛ V3 — Namaz Rehberi

GitHub Pages için statik, mobil-öncelikli PWA prototipi.

## V3 özellikleri
- Ana ekran + sıradaki namaz
- Konuma göre canlı vakit sorgusu
- Diyanet hesap yöntemi (`method=13`)
- Hanefî asr seçimi (`school=1`)
- Şehir seçimi / cihaz konumu
- Kıble yönü ve cihaz sensörü denemesi
- Günlük namaz takip işaretleri (localStorage)
- Bildirim izni + sayfa açıkken demo hatırlatması
- Adım adım namaz rehberi
- Dua ekranı
- PWA manifest + service worker

## GitHub Pages
1. Dosyaları repository köküne yükleyin.
2. Settings → Pages → Deploy from branch → `main` → `/root` → Save.
3. HTTPS üzerinden açın; geolocation, notifications ve service worker HTTPS/localhost altında daha güvenilir çalışır.

## Önemli üretim notları
Bu paket MVP'dir. Namaz vakitleri AlAdhan API üzerinden Diyanet yöntemine bağlanır. Üretim sürümünde API kullanım koşulları, kota, hata yönetimi ve resmi kaynak doğrulaması kontrol edilmelidir.
Dinî metinlerin yayına alınmadan önce ehil bir ilahiyat danışmanı tarafından son kontrolden geçirilmesi önerilir.
