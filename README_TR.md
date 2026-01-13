# Harcama Takip Uygulaması

Kullanıcılarının harcamalarını girerek günlük, haftalık ve aylık olarak kontrol edebilecekleri profesyonel bir Flutter mobil uygulaması.

## Özellikler

✨ **Şık ve Modern Arayüz**
- Profesyonel renk şeması ve gradient tasarımlar
- Material Design 3 tasarım dili
- Responsive ve kullanıcı dostu interface

📊 **Harcama Yönetimi**
- Kolay harcama ekleme ve silme
- 7 kategori (Yiyecek, Ulaşım, Eğlence, Alışveriş, Faturalar, Sağlık, Diğer)
- Her harcama için açıklama ve tarih ekleme

📈 **İstatistikler**
- Günlük, haftalık ve aylık harcama görünümü
- Kategori bazlı dağılım grafiği (Pie Chart)
- Gerçek zamanlı hesaplamalar

💾 **Veri Yönetimi**
- SQLite veritabanı ile yerel depolama
- Harcama geçmişi kaydetme
- Verilerin güvenli tutulması

## Teknolojiler

- **Flutter**: UI framework
- **Dart**: Programlama dili
- **Provider**: State management
- **SQLite**: Yerel veritabanı
- **FL Chart**: Grafik gösterimi
- **Intl**: Uluslararasılaştırma

## Başlangıç

### Gereksinimler
- Flutter 3.9.2 ve üzeri
- Dart 3.0 ve üzeri
- Android SDK (Android çalıştırma için)
- Xcode (iOS çalıştırma için)

### Kurulum

1. Bağımlılıkları yükleyin:
```bash
flutter pub get
```

2. Uygulamayı çalıştırın:

**Android:**
```bash
flutter run
```

**Web:**
```bash
flutter run -d chrome
```

**iOS:**
```bash
flutter run
```

## Proje Yapısı

```
lib/
├── main.dart                 # Uygulama giriş noktası
├── models/
│   └── expense.dart         # Harcama veri modeli
├── providers/
│   └── expense_provider.dart # State management
├── screens/
│   ├── home_screen.dart     # Ana ekran
│   └── add_expense_screen.dart # Harcama ekleme ekranı
├── services/
│   └── database_service.dart # Veritabanı işlemleri
├── theme/
│   └── app_theme.dart       # Tema ve stil ayarları
└── widgets/
    ├── expense_card.dart     # Harcama kartı widget
    ├── category_chart.dart   # Kategori grafiği
    └── statistics_card.dart  # İstatistik kartı
```

## Kullanım

### Harcama Ekleme
1. + düğmesine tıklayın
2. Kategoriyi seçin
3. Miktarı girin
4. Açıklama yazın
5. Tarihi seçin (varsayılan: bugün)
6. "Harcama Ekle" düğmesine tıklayın

### Harcama Silme
Harcama kartını sola kaydırın ve sil simgesine tıklayın

### İstatistikleri Görüntüleme
Üstteki tab butonlarında (Günlük/Haftalık/Aylık) seçin

## Renkler

| Kategori | Renk |
|----------|------|
| Yiyecek | 🟠 #EA580C |
| Ulaşım | 🔵 #0891B2 |
| Eğlence | 🟣 #7C3AED |
| Alışveriş | 🩷 #EC4899 |
| Faturalar | 🟡 #EAB308 |
| Sağlık | 🩵 #06B6D4 |
| Diğer | ⚫ #6B7280 |

## Ana Renk Şeması

- **Birincil**: #5B61E3 (İndigo)
- **Vurgu**: #00D4FF (Cyan)
- **Arka Plan**: #F8F9FA (Açık Gri)

## Özellikleri

- ✅ Yerel SQLite veritabanı
- ✅ Provider kullanarak state management
- ✅ Pie chart görünümü
- ✅ Türkçe dil desteği
- ✅ Tarih seçme arayüzü
- ✅ Harcama silme animasyonu
- ✅ Kategori filtreleme
- ✅ Responsive tasarım

## Geliştirilmiş Özellikler

Gelecek sürümlerde eklenebilir:
- 📌 Bütçe hedefi belirleme
- 📌 Bildirim ve uyarılar
- 📌 Harcama raporları (PDF, Excel)
- 📌 Bulut senkronizasyonu
- 📌 Çok kullanıcı desteği
- 📌 Grafik eğilimleri analizi

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır.

## Yazarlar

Harcama Takip Uygulaması - 2024

---

Sorularınız veya önerileriniz için iletişim kurunuz!
