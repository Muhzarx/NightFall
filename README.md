# NIGHTFALL — The Last Light

Prototype game horror 3D berbasis Three.js. Dapat dimainkan melalui browser desktop dan browser Android.

## Fitur prototype
- Lingkungan hutan 3D prosedural, kabut, pencahayaan, reruntuhan, dan gerbang.
- Karakter third-person dan first-person (tekan C).
- Senter (F), lari (Shift), kontrol keyboard WASD.
- Joystick dan tombol sentuh untuk Android.
- Tiga segel koleksi, objektif membuka gerbang, monster pengejar, kondisi menang/kalah.
- Hak cipta: © Muhammad Hafizd Anshari.

## Menjalankan secara lokal
Karena menggunakan JavaScript module, jalankan melalui server lokal (jangan membuka index.html dengan file://).

Python:
```bash
python -m http.server 8000
```
Lalu buka http://localhost:8000

Atau gunakan VS Code Live Server.

## Publikasi live demo gratis di GitHub Pages
1. Buat repository GitHub, misalnya `Nightfall-3D-Horror`.
2. Unggah `index.html` dan `README.md` ke root repository.
3. Buka Settings → Pages.
4. Pada Build and deployment, pilih Deploy from a branch → `main` → `/ (root)` → Save.
5. Setelah deployment selesai, demo tersedia di `https://USERNAME.github.io/Nightfall-3D-Horror/`.

## Android
Prototype ini responsif dan menyediakan joystick/tombol layar. Untuk menjadikannya aplikasi Android APK, bungkus versi web ini menggunakan Capacitor atau porting ke Godot/Unity. Koneksi internet diperlukan untuk memuat Three.js dari CDN pada versi ini.

## Catatan
Ini adalah vertical-slice/prototype awal, bukan game final. Model karakter, animasi, audio, AI monster, collision map, optimasi perangkat rendah, dan packaging APK masih perlu dikembangkan.
