# Pulsa Multi Cabang (Android)

Pencatatan untuk konter pulsa skala kecil dengan beberapa cabang. Data tersimpan lokal di perangkat.
PIN awal pemilik: **1234** (ganti di menu Atur).

Jenis produk: pulsa elektrik, paket data elektrik, voucher gesek pulsa, voucher gesek data,
SIM fresh (non-registrasi), SIM perdana berpaket, aksesori (kabel & batok charger).
Operator: Telkomsel, by.U, IM3, Tri, XL, Axis, Smartfren (bisa ditambah).
Harga produk di aplikasi hanyalah CONTOH — ubah di menu Atur.

## Build debug APK lewat GitHub
1. Push seluruh isi folder ini ke repo GitHub (branch `main`).
2. Tab **Actions** -> **Build Debug APK** (otomatis saat push, atau *Run workflow*).
3. Unduh artifact **PulsaMulti-debug-apk** (`app-debug.apk`).

## Build lokal
JDK 17 + Android SDK + Gradle 8.7: `gradle assembleDebug`
