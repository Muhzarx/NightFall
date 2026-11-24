<div align="center">

# 🌑 NIGHTFALL — THE LAST LIGHT

### A 3D Survival Horror Experience

**The forest is quiet. That doesn't mean you're alone.**

[![Play Game](https://img.shields.io/badge/PLAY%20GAME-LIVE%20DEMO-8b2e24?style=for-the-badge&logo=googlechrome&logoColor=white)](https://muhzarx.github.io/NightFall/)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github)](https://github.com/Muhzarx/NightFall)
[![Three.js](https://img.shields.io/badge/Three.js-WebGL-black?style=for-the-badge&logo=threedotjs)](https://threejs.org/)

**Explore the forest. Find the seals. Escape before it finds you.**

</div>

---

## 🎮 About the Game

**NIGHTFALL: The Last Light** adalah game survival horror 3D berbasis browser yang membawa pemain ke sebuah hutan gelap, berkabut, dan dipenuhi sesuatu yang tidak seharusnya ada di sana.

Pemain harus menjelajahi lingkungan, menemukan tiga segel misterius, menghindari makhluk yang berkeliaran di dalam hutan, lalu membuka gerbang untuk melarikan diri.

Game dibuat menggunakan **Three.js** dan dirancang agar dapat dimainkan melalui browser desktop maupun browser Android.

> ⚠️ **Prototype notice:** NIGHTFALL saat ini merupakan prototype/vertical slice yang masih dalam pengembangan. Fitur dan kualitas visual dapat berubah pada pembaruan berikutnya.

## 🚀 Live Demo

<div align="center">

### [▶ PLAY NIGHTFALL NOW](https://muhzarx.github.io/NightFall/)

Mainkan langsung melalui browser tanpa mengunduh installer.

**Desktop · Android Browser · WebGL**

</div>

> Jika demo belum terbuka, aktifkan GitHub Pages terlebih dahulu melalui **Repository → Settings → Pages → Deploy from a branch → main → /(root) → Save**. Tunggu proses deployment selesai, lalu buka kembali tautan Live Demo di atas.

## 📖 Story

Kamu terbangun di tengah hutan yang asing. Kabut menutupi jalan, pepohonan berdiri seperti bayangan, dan sebuah gerbang tua terlihat samar di kejauhan.

Ada tiga segel yang harus ditemukan untuk membuka gerbang tersebut.

Namun, kamu tidak sendirian.

Sesuatu sedang mengawasimu dari balik pepohonan. Semakin dekat ia datang, semakin besar peluangmu tidak akan pernah meninggalkan hutan itu.

**Find the seals. Keep your light alive. Get out.**

## ✨ Current Features

| Feature | Description |
|---|---|
| 🌲 3D Forest Environment | Lingkungan hutan dengan pepohonan, batu, reruntuhan, dan kabut |
| 🌫️ Atmospheric Fog | Kabut dan pencahayaan malam untuk membangun suasana horror |
| 👁️ Dual Camera | Beralih antara First Person dan Third Person |
| 🔦 Flashlight | Nyalakan atau matikan senter untuk menerangi area sekitar |
| 🏃 Sprint | Berlari untuk menjauh dari ancaman |
| 👹 Monster Pursuit | Makhluk akan mendekati dan mengejar pemain ketika berada dalam jangkauan |
| 🔮 Collectible Seals | Temukan tiga segel tersembunyi |
| 🚪 Escape Objective | Buka gerbang setelah semua segel terkumpul |
| 📱 Mobile Controls | Joystick virtual dan tombol aksi untuk layar sentuh |
| 🏆 Win / Lose State | Selesaikan objektif atau tertangkap oleh monster |

## 🕹️ Controls

### Desktop

| Key | Action |
|---|---|
| `W` / `↑` | Move forward |
| `A` / `←` | Move left |
| `S` / `↓` | Move backward |
| `D` / `→` | Move right |
| `SHIFT` | Sprint |
| `F` | Toggle flashlight |
| `C` | Switch camera |
| `E` | Interact / collect seal |
| Mouse | Look around (First Person / pointer lock) |

### Android / Touchscreen

| Control | Action |
|---|---|
| Virtual Joystick | Move character |
| RUN | Sprint |
| FLASHLIGHT | Toggle flashlight |
| CAMERA | Switch camera |
| INTERACT | Collect seal / interact |

**Recommended:** Gunakan browser modern dengan dukungan WebGL. Pada desktop, klik area permainan untuk mengaktifkan kontrol mouse. Tekan `ESC` untuk melepaskan pointer lock.

## 🎯 How to Play

1. Tekan **ENTER THE FOREST** untuk memulai.
2. Jelajahi hutan dan perhatikan cahaya segel.
3. Dekati segel, lalu tekan `E` atau tombol **INTERACT**.
4. Kumpulkan ketiga segel.
5. Pergilah menuju gerbang di bagian utara hutan.
6. Dekati gerbang dan tekan tombol interaksi.
7. Hindari monster. Jika tertangkap, permainan berakhir.

**Objective:** Collect 3 seals and escape the forest.

## 🛠️ Built With

- **HTML5** — Struktur halaman game.
- **CSS3** — Antarmuka, overlay, dan kontrol responsif.
- **JavaScript (ES Modules)** — Logika permainan.
- **Three.js** — Rendering dan lingkungan 3D.
- **WebGL** — Akselerasi grafis melalui browser.

Three.js dimuat melalui CDN. Koneksi internet diperlukan saat membuka game.

## 💻 Run Locally

Pastikan sudah memiliki browser modern dan Python atau VS Code.

### 1. Clone repository

```bash
git clone https://github.com/Muhzarx/NightFall.git
cd NightFall
```

### 2. Jalankan local server

Dengan Python:

```bash
python -m http.server 8000
```

Atau gunakan ekstensi **Live Server** di Visual Studio Code.

### 3. Buka game

Kunjungi:

```text
http://localhost:8000
```

> Jangan membuka `index.html` langsung menggunakan `file://`. Game menggunakan JavaScript ES Modules sehingga perlu dijalankan melalui local server.

## 🌐 Deploy to GitHub Pages

Repository ini dapat dipublikasikan sebagai website game gratis menggunakan GitHub Pages.

1. Buka repository [Muhzarx/NightFall](https://github.com/Muhzarx/NightFall).
2. Masuk ke **Settings**.
3. Pilih menu **Pages**.
4. Pada bagian **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main`.
6. Pilih folder `/ (root)`.
7. Klik **Save**.
8. Tunggu proses deployment selesai.

Setelah berhasil, game dapat diakses melalui:

**https://muhzarx.github.io/NightFall/**

Setiap perubahan yang di-push ke branch yang dipublikasikan akan diperbarui melalui proses deployment GitHub Pages.

## 📱 Android Compatibility

NIGHTFALL dapat dimainkan melalui browser Android yang mendukung WebGL dan kontrol sentuh.

**Cara bermain di Android:**
1. Buka tautan Live Demo menggunakan Chrome atau browser modern.
2. Tunggu game selesai dimuat.
3. Tekan tombol mulai.
4. Gunakan joystick dan tombol di layar untuk bermain.

> Versi saat ini adalah game web responsif, bukan APK native. Pembuatan APK Android dapat menjadi tahap pengembangan selanjutnya menggunakan Capacitor atau engine game khusus.

## 🗺️ Development Roadmap

Berikut rencana pengembangan NIGHTFALL:

- [x] Prototype lingkungan 3D
- [x] Karakter pemain dan kontrol gerakan
- [x] First Person dan Third Person camera
- [x] Sistem flashlight
- [x] Sistem sprint
- [x] Tiga collectible seals
- [x] Monster pursuit sederhana
- [x] Objektif membuka gerbang
- [x] Kontrol sentuh Android
- [ ] Model karakter dan monster yang lebih detail
- [ ] Animasi karakter dan monster
- [ ] Sistem collision dan navigasi lingkungan yang lebih baik
- [ ] Efek suara lingkungan dan musik latar
- [ ] Jumpscare dan event horror
- [ ] Inventory dan sistem item
- [ ] Beberapa area eksplorasi
- [ ] Save / load progress
- [ ] Pengaturan grafis dan sensitivitas
- [ ] Optimasi performa untuk perangkat Android
- [ ] Build APK Android

## 📂 Project Structure

```text
NightFall/
├── index.html      # Main game, UI, CSS, and Three.js logic
└── README.md       # Project documentation
```

## ⚙️ System Requirements

| Component | Requirement |
|---|---|
| Platform | Desktop / Android browser |
| Browser | Chrome, Edge, Firefox, or other modern browser |
| Graphics | WebGL compatible GPU |
| Internet | Required for Three.js CDN |
| Input | Keyboard + mouse or touchscreen |

Performa aktual bergantung pada perangkat, browser, dan kemampuan GPU.

## 🤝 Contributions

Contributions, suggestions, and bug reports are welcome.

1. Fork this repository.
2. Create a new branch.
3. Make your changes.
4. Submit a Pull Request.

## 👨‍💻 Developer

<div align="center">

**Muhammad Hafizd Anshari**

Game Developer · Web Developer

[GitHub @Muhzarx](https://github.com/Muhzarx)

</div>

## 📜 License & Copyright

**© 2026 Muhammad Hafizd Anshari. All Rights Reserved.**

NIGHTFALL — The Last Light and its original project materials are the work of Muhammad Hafizd Anshari.

No copying, redistribution, modification, or commercial use of this project or its original materials is permitted without prior written permission from the copyright holder, except where otherwise permitted by applicable law.

---

<div align="center">

**NIGHTFALL — THE LAST LIGHT**

*You are not alone in the dark.*

[PLAY GAME](https://muhzarx.github.io/NightFall/) · [SOURCE CODE](https://github.com/Muhzarx/NightFall)

</div>
