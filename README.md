# 🚗 Yakıt Takibim

**Akıllı Yakıt Tüketimi Takip Uygulaması**

Modern tasarım ve güçlü özellikleriyle araç yakıt masraflarınızı profesyonel şekilde yönetin.

## 🌟 Özellikler

- **Çoklu Araç Desteği**: İstediğiniz kadar araç ekleyin ve ayrı ayrı takip edin
- **Detaylı İstatistikler**: Aylık, haftalık ve günlük tüketim analizleri
- **Akıllı Hatırlatmalar**: Yakıt dolumu ve bakım hatırlatmaları
- **Bulut Yedekleme**: Supabase ile güvenli veri saklama
- **Modern UI**: Material 3 tasarım dili ve smooth animasyonlar
- **AdMob Entegrasyonu**: Gelir elde etme imkanı

## 📱 Platform Desteği

- ✅ iOS 16.0+
- ✅ Android API 21+
- 🌐 Web (GitHub Pages)

## 🛠 Teknolojiler

### Frontend
- **Flutter 3.35+** - Cross-platform uygulama geliştirme
- **Riverpod** - State management
- **Google Fonts** - Typography
- **Material 3** - Design system

### Backend
- **Supabase** - Authentication & Database
- **PostgreSQL** - Veritabanı
- **Row Level Security (RLS)** - Güvenlik

### Services
- **Flutter Local Notifications** - Push bildirimleri
- **Google Mobile Ads** - Reklam entegrasyonu
- **Image Picker** - Profil fotoğrafı
- **Share Plus** - Veri paylaşımı
- **URL Launcher** - Harici linkler

## 🚀 Kurulum

### Gereksinimler
- Flutter SDK 3.35+
- Dart 3.9+
- Xcode 15+ (iOS için)
- Android Studio (Android için)

### Adımlar
1. **Repository'yi klonlayın:**
```bash
git clone https://github.com/emrhncfc/yakittakibi.git
cd yakittakibi
```

2. **Dependencies'leri yükleyin:**
```bash
flutter pub get
```

3. **Supabase Konfigürasyonu:**
   - `lib/config/supabase_config.dart` dosyasını düzenleyin
   - Supabase URL ve Anon Key'inizi ekleyin
   - Database setup için `complete_database_setup.sql` scripti çalıştırın

4. **AdMob Konfigürasyonu:**
   - Google AdMob hesabı oluşturun
   - `lib/services/admob_service.dart` dosyasında Production Ad Unit ID'leri güncelleyin
   - Android: `android/app/src/main/AndroidManifest.xml` - AdMob App ID
   - iOS: `ios/Runner/Info.plist` - GADApplicationIdentifier

5. **Native Splash Screen:**
```bash
flutter pub run flutter_native_splash:create
```

6. **Uygulamayı çalıştırın:**
```bash
flutter run
```

## 📊 Database Schema

### Tables
- **profiles** - Kullanıcı profilleri
- **vehicles** - Araç bilgileri
- **fuel_records** - Yakıt kayıtları

### Features
- Row Level Security (RLS)
- Automatic timestamps
- Foreign key constraints
- Indexes for performance

## 🔧 Geliştirme

### Debugging
```bash
# Debug mode ile çalıştır
flutter run --debug

# Profile mode ile çalıştır  
flutter run --profile

# Release build
flutter build apk --release
flutter build ios --release
```

### Testing
```bash
# Unit tests
flutter test

# Widget tests
flutter test test/widget_test.dart
```

## 🌐 Web Demo

Uygulamanın web versiyonunu buradan deneyebilirsiniz:
**[https://emrhncfc.github.io/yakittakibi/](https://emrhncfc.github.io/yakittakibi/)**

## 📱 İndirme Linkleri

### App Store
🔗 [App Store'dan İndir](https://apps.apple.com/app/yakittakibim)

### Google Play
🔗 [Google Play'den İndir](https://play.google.com/store/apps/details?id=com.emrhncfc.yakittakibi)

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakın.

## 👤 Geliştirici

**Emirhan Çiftçi**
- 📧 Email: info@yakittakibim.com
- 🌐 Website: [yakittakibim.com](https://emrhncfc.github.io/yakittakibi/)

## 🤝 Katkıda Bulunma

1. Fork edin
2. Feature branch oluşturun (`git checkout -b feature/AmazingFeature`)
3. Commit yapın (`git commit -m 'Add some AmazingFeature'`)
4. Branch'e push edin (`git push origin feature/AmazingFeature`)
5. Pull Request açın

## 📸 Screenshots

<div align="center">
  <img src="screenshots/login.png" width="200" alt="Login Screen"/>
  <img src="screenshots/dashboard.png" width="200" alt="Dashboard"/>
  <img src="screenshots/vehicles.png" width="200" alt="Vehicles"/>
  <img src="screenshots/fuel_records.png" width="200" alt="Fuel Records"/>
</div>

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=emrhncfc/yakittakibi&type=Date)](https://star-history.com/#emrhncfc/yakittakibi&Date)

## 📊 Stats

![GitHub stars](https://img.shields.io/github/stars/emrhncfc/yakittakibi?style=social)
![GitHub forks](https://img.shields.io/github/forks/emrhncfc/yakittakibi?style=social)
![GitHub issues](https://img.shields.io/github/issues/emrhncfc/yakittakibi)
![GitHub license](https://img.shields.io/github/license/emrhncfc/yakittakibi)

---

**🚗 Yakıt Takibim ile akıllı sürüş deneyimi! ⛽**