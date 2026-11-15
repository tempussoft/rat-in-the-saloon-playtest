# Rat in the Saloon — Playtest

Kapalı test sürümleri. Her sürüm sınırlı bir süre çalışır, süresi dolunca açılmaz.
Closed test builds. Each build runs for a limited time and stops opening after that.

## İndir / Download

En son sürüm: **[Releases](../../releases/latest)** sayfasından işletim sistemine uygun zip'i indir.
Latest build: grab the zip for your system from **[Releases](../../releases/latest)**.

| Sistem | Dosya |
| --- | --- |
| Windows 10/11 (64-bit) | `RatInTheSaloon-Windows-test-<tarih>.zip` |
| macOS 12+, Apple Silicon (M1 ve sonrası) | `RatInTheSaloon-Mac-test-<tarih>.zip` |
| Android 8+ (64-bit telefon) | `RatInTheSaloon-Android-test-<tarih>.apk` |

## Kurulum

**Windows:** Zip'i bir klasöre çıkar, `RatInTheSaloon.exe`'yi çalıştır. Mavi "Windows bilgisayarınızı korudu" uyarısında *Ek bilgi → Yine de çalıştır*.

**Mac:** Uygulamayı *Uygulamalar* klasörüne taşı ve aç. Apple uyarısında *Bitti* de, sonra *Sistem Ayarları → Gizlilik ve Güvenlik → Yine de Aç*. "Hasarlı" derse Terminal'de:

```
xattr -dr com.apple.quarantine /Applications/RatInTheSaloon.app
```

**Android:** APK dosyasını telefondan indir ve aç. "Bilinmeyen uygulamalar" uyarısında, indirdiğin tarayıcıya (Chrome vb.) *Bu kaynaktan izin ver* de, sonra *Yükle*. Play Protect uyarı verirse *Yine de yükle*.

Intel işlemcili Mac desteklenmiyor. Oyun internet ve mikrofon ister. 4–8 kişi, sesli sohbetle oynanır; biri masa kurar, diğerleri 6 karakterli oda koduyla katılır.

## Setup (English)

**Windows:** extract the zip, run `RatInTheSaloon.exe`; on the SmartScreen warning pick *More info → Run anyway*.
**Mac:** move the app to *Applications*; on Apple's warning click *Done*, then *System Settings → Privacy & Security → Open Anyway*. If it says the app is damaged, run the `xattr` line above.
**Android:** download the APK on the phone, allow installs from your browser when asked, then *Install* (on a Play Protect prompt: *Install anyway*).

---
Tempus Soft Studio
