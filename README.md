# 🎓 ALIF Dashboard
**Dashboard Persiapan Asesmen Lapangan - Informatika**

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://micro-boy.github.io/ALIF/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?logo=chart.js&logoColor=white)](https://www.chartjs.org/)

> **Sistem panduan interaktif yang komprehensif untuk membantu Program Studi Informatika mempersiapkan Asesmen Lapangan LAM-INFOKOM dengan pendekatan berbasis outcome dan framework PPEPP.**

---

## 📖 Tentang Project

**ALIF Dashboard** adalah aplikasi web Single Page Application (SPA) yang dikembangkan khusus untuk membantu Program Studi Informatika dalam mempersiapkan proses **Asesmen Lapangan (AL) LAM-INFOKOM**. Dashboard ini menggabungkan konten edukatif yang mendalam dengan interface interaktif dan user-friendly.

### 🎯 Tujuan Utama
- Memberikan panduan komprehensif persiapan akreditasi LAM-INFOKOM
- Mengimplementasikan paradigma shift dari **input-process** ke **output-outcome**
- Menerapkan **framework PPEPP** (Penetapan-Pelaksanaan-Evaluasi-Pengendalian-Peningkatan)
- Menyediakan strategi triangulasi untuk wawancara asesor

---

## ✨ Fitur Utama

### 🗂️ **Navigasi Terstruktur**
- **Beranda**: Filosofi dan paradigma asesmen
- **9 Kriteria Akreditasi** (C1-C9) dengan sistem tab interaktif
- **Persiapan Akhir**: Panduan wawancara, checklist, dan strategi hari-H
- **Referensi**: Daftar pustaka lengkap dari sumber resmi

### 🔍 **Pencarian Canggih**
- **Real-time search** dengan hasil instan
- **Full-text indexing** dari seluruh konten
- **Search highlighting** pada hasil pencarian
- **Auto-complete dropdown** dengan navigasi langsung

### 📊 **Visualisasi Data**
Dashboard mengintegrasikan **Chart.js** untuk 7 tipe visualisasi:
- **Bar Charts**: Komposisi kerja sama tridarma, prestasi mahasiswa
- **Doughnut Charts**: Kualifikasi DTPS, partisipasi MBKM, komposisi HKI
- **Pie Charts**: Sumber pendanaan PkM
- **Horizontal Bar Charts**: Kelulusan Tepat Waktu (KTW)

### ✅ **Interactive Checklist**
- Progress tracking real-time dengan visual progress bar
- 16 item checklist terorganisir dalam 4 kategori
- Strike-through styling untuk item completed
- Persistent state management

### 📱 **Responsive Design**
- Mobile-first approach dengan hamburger menu
- Adaptive layout menggunakan Tailwind CSS
- Optimal viewing pada semua ukuran layar

---

## 🚀 Cara Menjalankan

### Method 1: Online (Recommended)
Akses dashboard langsung melalui GitHub Pages:
```
https://micro-boy.github.io/ALIF/
```

### Method 2: Local Setup
1. **Clone repository:**
   ```bash
   git clone https://github.com/micro-boy/ALIF.git
   cd ALIF
   ```

2. **Buka file:**
   - Double-click `index.html`, atau
   - Klik kanan → "Open with" → pilih browser
   - Atau gunakan local server:
   ```bash
   python -m http.server 8000
   # Akses: http://localhost:8000
   ```

### ⚡ Setup Offline (Tanpa Koneksi Internet)
Dashboard menggunakan CDN untuk optimal performance. Untuk penggunaan offline:
1. Download Tailwind CSS dan Chart.js libraries
2. Ganti CDN links dengan file lokal di `index.html`

---

## 🏗️ Struktur Project

```
ALIF/
├── 📄 index.html          # Main dashboard file (self-contained)
├── 📄 _config.yml         # Jekyll configuration untuk GitHub Pages
├── 📄 CLAUDE.md          # Development instructions
├── 📄 README.md          # Project documentation
└── 🗂️ tasks/            # Development tasks (excluded dari deployment)
    └── todo.md
```

---

## 🛠️ Teknologi yang Digunakan

| Teknologi | Versi | Fungsi |
|-----------|--------|--------|
| **HTML5** | - | Semantic structure dan accessibility |
| **Tailwind CSS** | Latest | Utility-first CSS framework |
| **Vanilla JavaScript** | ES6+ | Interactive functionality |
| **Chart.js** | Latest | Data visualization |
| **GitHub Pages** | - | Hosting dan deployment |

---

## 👥 Target Pengguna

Dashboard ini dirancang untuk multiple stakeholders dalam ekosistem akreditasi:

| Stakeholder | Use Case |
|-------------|----------|
| **👔 Kaprodi & Pimpinan UPPS** | Memahami strategi dan narasi besar akreditasi |
| **📋 Tim Taskforce Akreditasi** | Persiapan dokumen dan bukti pendukung |
| **👨‍🏫 Dosen DTPS** | Persiapan wawancara dan pemahaman triangulasi |
| **🎓 Mahasiswa** | Understanding expectation dalam sesi wawancara |
| **🏢 Staff Admin/Tendik** | Persiapan layanan dan fasilitas pendukung |

---

## 📚 Konten dan Educational Value

### 🔄 **PPEPP Framework Integration**
- Visual circular flow diagram dengan interactive tooltips
- Penerapan siklus penjaminan mutu yang systematic
- Contoh implementasi nyata dalam setiap kriteria

### 💡 **Practical Guidance**
- Template jawaban ideal untuk wawancara asesor
- Strategi triangulasi dengan breakdown per stakeholder
- Checklist operasional yang actionable
- Tips komunikasi dan etika profesional

### 📖 **9 Kriteria Akreditasi Lengkap**
Setiap kriteria dilengkapi dengan 4 tab komprehensif:
- **Fokus Asesor**: Apa yang dicari asesor
- **Indikator Kunci**: Metrics dan visualisasi data
- **Pertanyaan & Jawaban**: FAQ dengan accordion interface
- **Bukti Pendukung**: Dokumentasi yang diperlukan

---

## 🔧 Development

### Prerequisites
- Web browser modern (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime, dll.)
- Git untuk version control

### Local Development
```bash
# Clone repository
git clone https://github.com/micro-boy/ALIF.git

# Masuk ke directory
cd ALIF

# Buka dengan live server atau langsung double-click index.html
```

### Contribution Guidelines
1. Fork repository
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open Pull Request

---

## 📊 Performance & Features

### ⚡ **Technical Excellence**
- **Single-file deployment** (fully self-contained)
- **Offline-capable** operation
- **Lazy chart initialization** untuk performa optimal
- **Efficient memory management** dengan chart destruction
- **Mobile-first responsive design**

### 🎨 **User Experience**
- **Smooth animations** dan transitions
- **Intuitive navigation** dengan active states
- **Accessibility features** dengan ARIA labels
- **Search highlighting** untuk better visibility

### 🔄 **Maintainability**
- **Modular content structure** dalam JavaScript objects
- **Easy content addition** melalui `appData.pages`
- **Extensible chart system** dengan `initFunctions`
- **Clean separation of concerns**

---

## 📄 License

Project ini menggunakan [MIT License](LICENSE). Bebas digunakan untuk keperluan pendidikan dan pengembangan.

---

## 🤝 Contributing

Kontribusi sangat diterima! Silakan baca [contributing guidelines](CONTRIBUTING.md) untuk detail lebih lanjut.

### Ways to Contribute:
- 🐛 Report bugs
- 💡 Suggest new features
- 📖 Improve documentation
- 🔧 Submit pull requests
- ⭐ Star the repository

---

## 📞 Support & Contact

- **GitHub Issues**: [Create an issue](https://github.com/micro-boy/ALIF/issues)
- **Documentation**: [GitHub Wiki](https://github.com/micro-boy/ALIF/wiki)
- **Live Demo**: [https://micro-boy.github.io/ALIF/](https://micro-boy.github.io/ALIF/)

---

## 🙏 Acknowledgments

- **LAM-INFOKOM** untuk standar dan panduan akreditasi
- **Chart.js** untuk library visualisasi data yang excellent
- **Tailwind CSS** untuk utility-first CSS framework
- **GitHub Pages** untuk hosting yang reliable

---

<div align="center">

**⭐ Jika project ini bermanfaat, jangan lupa berikan star!**

[![GitHub stars](https://img.shields.io/github/stars/micro-boy/ALIF?style=social)](https://github.com/micro-boy/ALIF/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/micro-boy/ALIF?style=social)](https://github.com/micro-boy/ALIF/network)

</div>

---

*Dashboard ini dikembangkan dengan ❤️ untuk mendukung excellence dalam pendidikan tinggi Informatika di Indonesia.*