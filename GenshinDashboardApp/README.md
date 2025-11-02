# Genshin Dashboard (Android 10–15)

WebView app untuk menampilkan Battle Chronicle / Diary / Abyss / Imaginarium Theater dari HoYoLAB dengan cookies milikmu.

## Fitur
- Import `genshin.txt` (ltuid/ltoken dsb) → set cookie otomatis
- Shortcut halaman: Overview, Traveler’s Diary, Spiral Abyss, Imaginarium Theater
- Live auto-refresh (15/30/45 detik)
- Export HTML dari halaman yang terlihat (bisa dibuka di Chrome)
- Tanpa Rust/Termux; langsung APK

## Build via GitHub Actions
1. Push proyek ini ke repo GitHub (branch `main`).
2. Actions → Android CI (APK) → unduh artifact `app-debug.apk`.

## Build lokal (Android Studio)
- Buka proyek → Build > Build APK(s) → install `app-debug.apk` ke HP.

## Cara pakai
1. Siapkan `genshin.txt` berisi:
   ```
   ltuid=123456; ltoken=xxxxx
   uid=7xxxxxxx
   ```
2. Buka app → ikon folder → pilih `genshin.txt`.
3. Pilih halaman di menu Link.
4. (Opsional) aktifkan Live dan export HTML.
