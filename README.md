# Invenio IMS - Landing Page & Demo Dashboard

Selamat datang di repositori proyek desain UI/UX **Invenio IMS** (Inventory Management System). Proyek ini merupakan tugas semester 4 untuk mata kuliah Desain UI/UX yang dikembangkan oleh **Kelompok 1**.

Invenio IMS adalah aplikasi manajemen inventaris gudang modern yang berfokus pada digitalisasi serta otomatisasi siklus rantai pasok (Supply Chain Management / SCM) secara real-time, transparan, dan akurat.

---

## 🚀 Fitur Utama

Aplikasi web ini dirancang dalam format **Landing Page** interaktif yang mencakup:

1. **Latar Belakang Masalah (Reviews)**: Menyajikan keluhan nyata dari pengguna aplikasi kompetitor (seperti Zoho & Odoo) dengan kartu interaktif. Pengguna bisa mengklik kartu untuk membaca detail ulasan secara penuh.
2. **Tujuan Utama (Goals)**: Visualisasi grid modern yang merinci 4 tujuan utama pengembangan Invenio IMS (Otomatisasi P2P, Akurasi Inbound, Visibilitas Real-time, Efisiensi Operasional).
3. **Fitur Utama (Interactive Tabs)**: Panel tab interaktif untuk menjelajahi keunggulan Invenio seperti:
   - Antarmuka berbasis peran (*Role-based UI*)
   - Analitik Prediktif berbasis Data
   - Pemindaian QC & GRN (*Mobile-First*)
   - Sistem Notifikasi Push Proaktif
4. **Simulasi Dashboard Analitik**: Demo interaktif menggunakan **Chart.js** yang memungkinkan pengguna melihat simulasi pergerakan stok (Inbound vs Outbound) secara Mingguan/Bulanan dan visualisasi peningkatan efisiensi operasional (Pick & Pack).
5. **Scrollspy & Smooth Navigation**: Navigasi sticky yang secara otomatis menyoroti tautan menu aktif berdasarkan posisi scroll layar pengguna.

---

## 🛠️ Teknologi yang Digunakan

Proyek ini dibangun menggunakan teknologi web modern berkinerja tinggi tanpa framework berat:

- **HTML5**: Kerangka semantik halaman web.
- **Tailwind CSS (via CDN)**: Framework CSS berbasis utility-first untuk desain yang bersih, responsif, dan premium.
- **Chart.js (via CDN)**: Pustaka JavaScript untuk merender bagan garis (*line chart*) dan bagan batang (*bar chart*) yang interaktif.
- **Vanilla JavaScript**: Untuk menangani logika interaktif (Tab switching, Reviews expansion, filter grafik, dan navigasi Scrollspy).

---

## 📁 Struktur Proyek

```text
Project SCM-UI.UX/Web-PPT/
│
├── assets/                  # Folder aset gambar yang diekstrak dari PDF
├── index.html               # Halaman utama aplikasi (HTML + JS)
├── style.css                # Kustomisasi stylesheet eksternal (Animasi & Flourish)
├── package.json             # Konfigurasi dependensi project npm
├── README.md                # Dokumentasi proyek (file ini)
└── Invenio IMS - Kel. 1...  # File presentasi PDF referensi utama
```

---

## 💻 Cara Menjalankan Proyek Secara Lokal

Karena proyek ini menggunakan HTML murni dengan pustaka berbasis CDN, Anda tidak perlu melakukan instalasi yang rumit:

1. **Klon atau Unduh** repositori ini ke komputer Anda.
2. Pastikan Anda memiliki koneksi internet aktif (karena proyek mengambil Tailwind dan Chart.js secara online).
3. Klik dua kali (double-click) pada file **`index.html`** untuk membukanya langsung di peramban web (browser) pilihan Anda (Chrome, Edge, Firefox, Safari).
4. Tekan tombol **F11** di peramban untuk melihat tampilan dalam mode presentasi penuh (*Full-Screen*).

---

## 👥 Tim Pengembang (Kelompok 1)

Proyek ini dikembangkan oleh mahasiswa Semester 4:

* **M. Zhafran Fawwaz** (NIM: 023124046)
* **Dito Ibrahim** (NIM: 023124067)
* **Aldefal Izzy Raiseuki** (NIM: 023124169)
* **Raihan Hanif Firdaus** (NIM: 023124157)

**Dosen Pengampu**: Gustian Rama Putra, S.Kom., MMSI
