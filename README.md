<div align="center">

<img src="assets/logo.webp" alt="AquCopy Logo" width="80"/>
<img src="assets/aqu.webp" alt="AquCopy" width="160"/>

# 🖨️ AQU Copy Center

**Solusi Terpercaya untuk Kebutuhan Kantor Anda**

[![Deploy to VPS](https://github.com/nasrulaminmuis/aqucopy/actions/workflows/deploy.yml/badge.svg)](https://github.com/nasrulaminmuis/aqucopy/actions/workflows/deploy.yml)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.3-7952B3?style=flat&logo=bootstrap&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)

</div>

---

## 📋 Deskripsi

**AQU Copy Center** adalah website bisnis profesional yang menyediakan layanan fotokopi dan pengadaan alat tulis kantor (ATK) di Indonesia. Website ini dibangun sebagai landing page modern dengan tampilan yang responsif dan ramah pengguna.

> *"AQU, Solusi untuk kebutuhan kantormu — Jasa fotokopi profesional dan pengadaan peralatan alat tulis kantor."*

---

## ✨ Fitur Utama

| Fitur | Deskripsi |
|-------|-----------|
| 🏠 **Beranda** | Hero section dengan banner menarik dan call-to-action |
| 🖨️ **Layanan** | Showcase layanan fotokopi dan pengadaan ATK |
| 💬 **Testimonial** | Ulasan pelanggan puas dari berbagai kalangan |
| 🎯 **Visi & Misi** | Komitmen perusahaan terhadap kualitas dan kepuasan pelanggan |
| 🤝 **Partner** | Daftar mitra terpercaya AQU Copy Center |
| 📝 **Formulir Saran** | Form kritik & saran langsung dari pelanggan |
| 📱 **Responsif** | Tampilan optimal di semua ukuran layar (mobile, tablet, desktop) |
| 📊 **Analytics** | Integrasi Google Analytics untuk pemantauan trafik |

---

## 🛠️ Teknologi yang Digunakan

<div align="center">

| Teknologi | Versi | Kegunaan |
|-----------|-------|----------|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) | 5 | Struktur halaman web |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) | 3 | Styling & animasi |
| ![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white) | 5.3.3 | Framework CSS responsif |
| ![Google Analytics](https://img.shields.io/badge/Google%20Analytics-E37400?style=flat&logo=google-analytics&logoColor=white) | GA4 | Analitik & pemantauan |
| ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=github-actions&logoColor=white) | — | CI/CD otomatis |
| ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white) | — | Web server (VPS) |

</div>

---

## 📁 Struktur Proyek

```
aqucopy/
├── 📄 index.html              # Halaman utama website
├── 📂 assets/                 # Aset gambar
│   ├── 🖼️ logo.webp           # Logo perusahaan
│   ├── 🖼️ aqu.webp            # Nama brand AQU
│   ├── 🖼️ banner.webp         # Gambar hero/banner
│   ├── 🖼️ 1.webp              # Gambar layanan ATK
│   ├── 🖼️ 2.webp              # Gambar layanan fotokopi
│   ├── 🖼️ kaca.webp           # Ikon pencarian
│   ├── 🖼️ Vector.webp         # Ikon panah CTA
│   └── 🖼️ amikom.webp        # Logo partner AMIKOM
├── 📂 .github/
│   └── 📂 workflows/
│       └── ⚙️ deploy.yml      # Workflow CI/CD deployment
└── 📂 .vscode/
    └── ⚙️ settings.json       # Konfigurasi editor
```

---

## 🚀 Menjalankan Secara Lokal

Website ini adalah **static HTML** — tidak membutuhkan instalasi dependensi apapun!

### Cara 1: Buka Langsung di Browser
```bash
# Clone repositori
git clone https://github.com/nasrulaminmuis/aqucopy.git

# Masuk ke folder proyek
cd aqucopy

# Buka index.html di browser favorit Anda
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

### Cara 2: Menggunakan Live Server (VS Code)
1. Install ekstensi **Live Server** di VS Code
2. Klik kanan pada `index.html`
3. Pilih **"Open with Live Server"**

### Cara 3: Menggunakan Python HTTP Server
```bash
# Python 3
python -m http.server 8000

# Kemudian buka browser dan akses:
# http://localhost:8000
```

---

## ⚙️ Deployment Otomatis (CI/CD)

Proyek ini menggunakan **GitHub Actions** untuk deployment otomatis ke VPS setiap kali ada push ke branch `main`.

```
Push ke main
     │
     ▼
GitHub Actions Workflow
     │
     ├── 1️⃣  Checkout repository
     │
     ├── 2️⃣  Hapus file lama di VPS
     │       (SSH ke /usr/share/nginx/html/)
     │
     └── 3️⃣  Upload file baru via SCP
             (ke /usr/share/nginx/html/)
```

### Secrets yang diperlukan:

| Secret | Deskripsi |
|--------|-----------|
| `VPS_HOST` | IP address atau hostname VPS |
| `VPS_USER` | Username SSH VPS |
| `VPS_PW` | Password SSH VPS |

> Konfigurasikan secrets di: **Repository Settings → Secrets and Variables → Actions**

---

## 🌟 Layanan Kami

### 📦 Pengadaan Alat Tulis Kantor (ATK)
Menyediakan berbagai kebutuhan alat tulis kantor berkualitas tinggi dengan harga kompetitif untuk mendukung produktivitas kerja Anda.

### 🖨️ Jasa Fotokopi
Layanan fotokopi profesional dengan teknologi terkini, menghasilkan cetakan berkualitas tinggi dengan pengerjaan cepat dan tepat waktu.

---

## 🎯 Visi & Misi

### 🔭 Visi
> Menjadi penyedia layanan fotokopi dan alat tulis kantor **terpercaya di Indonesia**, dengan fokus pada kualitas, efisiensi, dan kepuasan pelanggan.

### 🚀 Misi

1. ✅ Menyediakan layanan fotokopi berkualitas tinggi dengan teknologi terkini
2. ✅ Menawarkan berbagai produk ATK berkualitas untuk memenuhi kebutuhan perkantoran
3. ✅ Memberikan pelayanan yang cepat, ramah, dan profesional kepada setiap pelanggan
4. ✅ Terus berinovasi dalam layanan online untuk kemudahan akses pelanggan

---

## 💬 Testimoni Pelanggan

> *"AQU Copy Center selalu memberikan layanan terbaik. Kualitas cetakan mereka sangat bagus dan pengiriman selalu tepat waktu."*
> — **Najwa Shihab**

> *"Saya sangat puas dengan layanan pengadaan ATK dari AQU. Produk berkualitas dengan harga yang kompetitif."*
> — **Cania Cita**

> *"Pelayanan online AQU sangat memudahkan kami dalam memesan kebutuhan kantor. Proses cepat dan efisien."*
> — **Irwandi Ferry**

---

## 🤝 Partner

<div align="center">
  <img src="assets/amikom.webp" alt="AMIKOM" width="120"/>
</div>

---

## 📄 Lisensi

Copyright © 2024 **AQU Copy Center**. All rights reserved.

---

<div align="center">

Dibuat dengan ❤️ oleh tim **AQU Copy Center**

⭐ Jangan lupa beri **star** jika proyek ini bermanfaat!

</div>
