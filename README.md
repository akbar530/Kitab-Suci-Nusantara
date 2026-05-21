# 📖 Kitab Suci Nusantara

> Platform digital untuk membaca kitab suci dari seluruh agama yang diakui di Indonesia — dalam satu tampilan yang elegan dan modern.

---

## ✨ Tentang Proyek

**Kitab Suci Nusantara** adalah website single-page (satu file HTML) yang menyajikan kitab suci dari 5 agama resmi Indonesia secara bersih, cepat, dan nyaman dibaca di perangkat apapun — mobile maupun desktop.

---

## 🕌 Agama yang Tersedia

| Agama | Kitab | Sumber Data |
|---|---|---|
| ☪ Islam | Al-Qur'an Al-Karim (114 Surat · 6.236 Ayat) | API equran.id |
| ✝ Kristen | Alkitab Terjemahan Baru (66 Kitab · 31.102 Ayat) | API Sabda |
| 🕉 Hindu | Bhagavad Gita (18 Bab · 700 Sloka) | Teks Publik Domain |
| ☸ Buddha | Dhammapada (26 Bab · 423 Syair) | Teks Publik Domain |
| ☯ Konghucu | Da Xue / Ajaran Besar (10 Bab) | Teks Publik Domain |

---

## 🚀 Fitur Utama

- **Halaman beranda** — menampilkan 5 kartu agama dengan deskripsi lengkap
- **Daftar surat / kitab / bab** — navigasi mudah dengan fitur pencarian realtime
- **Baca ayat lengkap** — teks Arab, transliterasi Latin, dan terjemahan Indonesia (Al-Qur'an)
- **Audio murottal** — pemutar audio dengan progress bar dan highlight ayat otomatis (Al-Qur'an)
- **Navigasi antar surat/pasal** — tombol Sebelumnya & Selanjutnya
- **Dark mode & Light mode** — dengan transisi smooth, tersimpan di localStorage
- **Navbar dinamis** — logo & nama di kiri saat beranda, pindah ke tengah saat membaca
- **Tombol back** — muncul otomatis di pojok kiri atas saat masuk halaman dalam
- **Skeleton loading** — placeholder elegan saat konten dimuat
- **Toast notification** — notifikasi aksi ringan di pojok kanan bawah
- **Scroll to top** — tombol kembali ke atas muncul saat scroll
- **Loading screen** — animasi elegant saat website pertama dibuka
- **Responsive** — nyaman di mobile, tablet, dan desktop

---

## 🛠 Teknologi

| Teknologi | Keterangan |
|---|---|
| HTML5 | Struktur halaman |
| CSS3 | Styling, animasi, dark/light theme |
| Vanilla JavaScript | Logika tanpa framework |
| Font Awesome 6 | Ikon profesional |
| Google Fonts | Lora, Inter, Amiri Quran |
| equran.id API | Data Al-Qur'an (surat, ayat, audio) |
| Sabda / Beeble API | Data Alkitab Terjemahan Baru |

---

## 📁 Struktur File

```
kitab-suci-nusantara.html   ← satu file, semua fitur di dalamnya
README.md                   ← dokumentasi ini
```

---

## 🌐 Cara Pakai

### Opsi 1 — Buka langsung
Download file `kitab-suci-nusantara.html`, lalu buka di browser. Pastikan ada koneksi internet untuk memuat data Al-Qur'an dan Alkitab dari API.

### Opsi 2 — Deploy ke hosting
Upload file ke hosting statis manapun:
- [Netlify Drop](https://app.netlify.com/drop) — drag & drop file HTML
- [Vercel](https://vercel.com) — deploy dari folder
- [GitHub Pages](https://pages.github.com) — push ke repo

---

## 🔌 API yang Digunakan

### Al-Qur'an
```
GET https://equran.id/api/v2/surat
GET https://equran.id/api/v2/surat/{nomor}
```
Mengembalikan daftar surat, detail ayat (Arab, Latin, Terjemahan), dan URL audio murottal.

### Alkitab (Terjemahan Baru)
```
GET https://beeble.vercel.app/api/v1/passage/{abbr}/{pasal}?ver=tb
```
Mengembalikan ayat-ayat per pasal dari Alkitab versi Terjemahan Baru Indonesia.

---

## 🎨 Desain

- **Dark theme** — hitam doff `#09090b` dengan aksen emas `#c8a870`
- **Light theme** — perkamen/krem `#f5f0e6` dengan aksen emas tua `#9a7030`
- **Tipografi** — Lora (serif) untuk judul, Inter untuk teks, Amiri Quran untuk Arab
- **Animasi** — smooth fade, skeleton loading, hover effects, scale transitions
- **Layout** — full width, mobile-first, tanpa celah

---

## 📜 Sumber Data Statis

Untuk Hindu (Bhagavad Gita), Buddha (Dhammapada), dan Konghucu (Da Xue), teks yang ditampilkan merupakan terjemahan dari sumber publik domain. Teks lengkap per ayat/sloka tersedia dalam cetakan resmi masing-masing kitab.

---

## 📄 Lisensi

Proyek ini dibuat untuk keperluan edukasi dan informasi. Data kitab suci mengikuti ketentuan sumber masing-masing:
- Al-Qur'an © equran.id
- Alkitab © Lembaga Alkitab Indonesia (LAI) via API Sabda
- Hindu, Buddha, Konghucu — teks publik domain

---

## 🙏 Kontribusi

Dibuat dengan ❤️ untuk mempermudah akses bacaan kitab suci bagi seluruh masyarakat Indonesia.

> *"Bhinneka Tunggal Ika — Berbeda-beda tetapi tetap satu."*
