# time-boxing

# ⏳ TimeBox — Time Boxing & Productivity App

**TimeBox** adalah aplikasi manajemen waktu dan produktivitas berbasis teknik **Time Boxing**, dibangun dalam satu file HTML/CSS/JS tanpa dependensi backend. Semua data tersimpan aman di `localStorage` browser kamu — cepat, privat, dan bisa langsung dipakai offline.

> Kelola tugas, atur fokus dengan Pomodoro, pantau kebiasaan harian, dan lihat progres produktivitasmu — semuanya dalam satu dashboard yang rapi.

![status](https://img.shields.io/badge/status-active-brightgreen)
![license](https://img.shields.io/badge/license-MIT-blue)
![made with](https://img.shields.io/badge/made%20with-HTML%20%7C%20CSS%20%7C%20JavaScript-orange)

---

## ✨ Fitur

- **📊 Dashboard** — ringkasan tugas hari ini, grafik penyelesaian 7 hari terakhir, dan tingkat penyelesaian tugas.
- **🎯 Manajemen Tugas** — buat, edit, pin, filter (status/project/prioritas), cari, urutkan, lengkap dengan **pagination** (page size & page range) untuk daftar tugas yang panjang.
- **🧩 Kanban Board** — seret-lepas (drag & drop) tugas antar kolom To Do → In Progress → Done.
- **🚦 Eisenhower Matrix** — prioritaskan tugas berdasarkan urgensi dan kepentingan.
- **📅 Kalender** — lihat deadline tugas per bulan.
- **🌱 Habit Tracker** — bangun kebiasaan harian/mingguan dengan streak counter.
- **🍅 Mode Fokus** — Pomodoro timer, countdown timer, dan stopwatch dengan lap.
- **📈 Statistik & Gamifikasi** — sistem Level & XP, streak harian, progres per project.
- **🌗 Dark/Light Mode** — tema gelap & terang yang bisa diganti kapan saja.
- **💾 Backup & Restore** — export/import seluruh data ke/dari file JSON.
- **🖨️ Print/Export PDF** — cetak daftar tugas aktif langsung dari browser.
- **🔔 Notifikasi Browser** — pengingat saat sesi fokus atau timer selesai.
- **📱 Responsif** — nyaman digunakan di desktop maupun mobile.

## 🖥️ Demo

Buka langsung file `index.html` di browser, atau aktifkan **GitHub Pages** pada repo ini untuk demo online.

## 🚀 Cara Menjalankan

Tidak perlu instalasi apa pun — TimeBox adalah aplikasi *single-file*, 100% berjalan di sisi klien (client-side).

```bash
# Clone repository
git clone https://github.com/username/timebox.git
cd timebox

# Buka langsung di browser
open index.html      # macOS
start index.html      # Windows
xdg-open index.html   # Linux
```

Atau cukup drag file `index.html` ke tab browser mana pun.

## 🧱 Struktur Proyek

```
timebox/
├── index.html      # Seluruh aplikasi (markup, style, dan logic)
├── README.md        # Dokumentasi proyek
└── LICENSE           # Lisensi MIT
```

## 🛠️ Tumpukan Teknologi

- **HTML5** & **CSS3** (custom properties / CSS variables untuk theming)
- **Vanilla JavaScript** (tanpa framework, tanpa build step)
- **Web Storage API** (`localStorage`) untuk penyimpanan data lokal
- **Google Fonts**: Fraunces, Inter, JetBrains Mono

## 📦 Data & Privasi

Seluruh data (tugas, habit, statistik, pengaturan) disimpan **hanya di browser kamu** melalui `localStorage`. Tidak ada data yang dikirim ke server mana pun. Gunakan fitur **Export/Import JSON** di halaman Pengaturan untuk mencadangkan atau memindahkan data antar perangkat.

## 🗺️ Roadmap

- [ ] Sinkronisasi cloud opsional (Google Drive / Dropbox)
- [ ] Sub-tugas (checklist) di dalam setiap tugas
- [ ] Notifikasi push melalui Service Worker (PWA)
- [ ] Multi-bahasa (i18n)

## 🤝 Kontribusi

Kontribusi sangat terbuka! Silakan buat *issue* untuk melaporkan bug atau mengusulkan fitur, atau langsung ajukan *pull request*.

1. Fork repository ini
2. Buat branch baru (`git checkout -b fitur-baru`)
3. Commit perubahan (`git commit -m 'Menambahkan fitur baru'`)
4. Push ke branch (`git push origin fitur-baru`)
5. Buka Pull Request

## 📄 Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

---

<p align="center">Dibuat dengan ❤️ untuk siapa pun yang ingin lebih produktif, satu time box sekaligus.</p>
