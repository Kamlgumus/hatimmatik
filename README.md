# 🕌 Hatimmatik

## HEMEN KULLANMAK ICIN (APK'siz)
`hatimmatik_pwa/index.html` dosyasini telefonda Chrome ile ac, ust menu > "Ana ekrana ekle".
Uygulama gibi calisir: seri sayaci, sayfa isaretleme, hoca sesi, bildirim izni.

## APK DERLEME (Android Studio bilgisayarda)
1. https://docs.flutter.dev/get-started/install adresinden Flutter SDK kur.
2. `flutter doctor` ile dogrula, Android Studio + SDK kur.
3. Bu klasorde: `flutter pub get`
4. `flutter build apk --release`
5. APK yolu: `build/app/outputs/flutter-apk/app-release.apk` -> telefona kopyala, kur.

## Ozellikler
- Ilk acilista Android bildirim izni ister, sonra "kac gunde bir" sorar.
- Belirlenen gunde bildirim gonderir (saat 20:00, cihaz acikken).
- Okuma yapilmazsa seri sifirlanir.
- Ana ekran widget'i: seri + sayfa (yesil-altin tasarim).
- Sayfa numarasi girilir, mushaf'taki sure bulunur, Alafasy seslendirir.
- Diyanet resmi mushaf PDF'i tek tikla acilir.
