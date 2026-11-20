# QR & Barcode Toolbox

QR kod ve barkod oluşturma, tarama, toplu üretim ve şablon yönetimini bir araya getiren, mağazalarda yayınlanmak üzere geliştirilen Flutter mobil uygulaması.

> Bu depo bir proje vitrinidir. Kaynak kod paylaşılmamaktadır.

## Özellikler

- **Üretim:** URL, metin, Wi-Fi, vCard, e-posta, SMS, telefon, konum, takvim etkinliği, **IBAN ile ödeme**, sosyal medya profilleri ve 1D barkodlar (EAN, UPC, Code128…)
- **Stüdyo:** Renk, logo, köşe stili gibi görünüm ayarları. PNG, SVG ve PDF dışa aktarma.
- **Toplu üretim:** CSV veya Excel'den yüzlerce kodu tek seferde üretme
- **Tarayıcı:** Kamera ve galeriden okuma. İçerik tipine göre akıllı sonuç kartı (Wi-Fi'ye bağlan, kişiyi kaydet…)
- **Geçmiş, favoriler ve şablonlar**
- **Doğrulama:** IBAN (mod-97), barkod kontrol haneleri, içerik kaçış kuralları
- **Pro sürüm:** Uygulama içi abonelik ve özellik kilitleri
- Türkçe ve İngilizce, açık ve koyu tema (Material 3)

## Mimari

Feature-first klasör yapısı (`data / domain / presentation`). Domain katmanı saf Dart'tır. Bu sayede üreticiler, içerik ayrıştırıcı ve doğrulayıcılar Flutter'dan bağımsız olarak birim testiyle doğrulanır.

## Teknolojiler

`Flutter` · `Dart` · `Riverpod` · `go_router` · `drift (SQLite)` · `RevenueCat` · `mobile_scanner` · `pdf/printing` · `Material 3` · `flutter gen-l10n`
