YOZZ STORE - proyek Android (WebView)

Cara bikin APK:
1. Install Android Studio (gratis) lalu File > Open > pilih folder ini.
2. Tunggu Gradle sync selesai (butuh internet).
3. Build > Build Bundle(s) / APK(s) > Build APK(s).
4. APK ada di app/build/outputs/apk/debug/app-debug.apk

Mengubah isi toko: edit app/src/main/assets/index.html lalu build ulang.
Nama app: app/src/main/AndroidManifest.xml (android:label).

TANPA Android Studio (lewat GitHub, bisa dari HP):
1. Buat repo baru di github.com, upload SEMUA isi folder ini (termasuk folder .github).
2. Buka tab Actions > "Build APK" > Run workflow (atau otomatis jalan setelah upload).
3. Tunggu ~3-5 menit, buka hasil run > bagian Artifacts > unduh "YozzStore-apk".
4. Ekstrak zip-nya, di dalamnya ada app-debug.apk, lalu install di HP.
