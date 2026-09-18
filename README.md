# বাঁশকান্দি মাদ্রাসা আযান

Flutter Android prayer/azan app with a simple KW Prayer-style home screen.

## Included
- বাংলা UI
- Silchar/Cachar preset
- Kuwait (Salmiya/Hawally) preset
- GPS location
- Karachi + Hanafi for India
- Umm al-Qura + Hanafi for Kuwait
- Fajr, Sunrise, Dhuhr, Asr, Maghrib, Isha
- Next-prayer countdown
- Individual azan ON/OFF
- Per-prayer ±10 minute adjustment
- Optional before-azan reminder (5/10/15 minutes)
- Sehri and Iftar reminders
- 7-day exact local notifications
- Boot/replacement notification receiver
- Azan MP3 asset
- Approximate civil Hijri date display

## Build
Run:

```bash
flutter pub get
flutter build apk --release --no-tree-shake-icons
```

The release APK will be under `build/app/outputs/flutter-apk/`.
