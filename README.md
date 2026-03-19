# 📋 Form Pendaftaran HIMATIK
> Formulir Pendaftaran Anggota Baru — Himpunan Mahasiswa Teknologi Informatika & Komputer

---

## 📌 Deskripsi

Project ini adalah **Form Pendaftaran Calon Anggota HIMATIK** berbasis HTML, CSS, dan JavaScript murni (Vanilla JS) — tanpa framework, tanpa library eksternal. Dibuat sebagai tugas mata kuliah **Pemrograman Web** semester 1.

Form ini mencakup hampir **seluruh elemen HTML Form** yang ada, mulai dari input teks biasa hingga tanda tangan digital menggunakan Canvas API.

---

## 🚀 Demo

Buka file `form_himatik.html` langsung di browser — tidak perlu server.

```
Klik kanan file → Open with → Browser (Chrome / Firefox / Edge)
```

---

## 📁 Struktur File

```
📦 form-himatik/
├── 📄 form_himatik.html       ← File utama (semua-in-one)
├── 📁 src/
│   └── 🖼️ Logo-Himatik.png   ← Logo HIMATIK
└── 📄 README.md               ← Dokumentasi ini
```

---

## ✅ Fitur & Element yang Digunakan

### 🔤 Input Elements
| Element | Kegunaan |
|---|---|
| `input[type="text"]` | Nama, NIM, Tempat Lahir, Instagram |
| `input[type="email"]` | Alamat Email |
| `input[type="tel"]` | Nomor HP |
| `input[type="number"]` | IPK |
| `input[type="date"]` | Tanggal Lahir |
| `input[type="url"]` | Link Portofolio / GitHub |
| `input[type="radio"]` | Jenis Kelamin, Kelas, Ukuran Kaos |
| `input[type="checkbox"]` | Bidang Minat, Pernyataan |
| `input[type="file"]` | Upload Foto, KTM, Portofolio |
| `input[type="range"]` | Komitmen Waktu (jam/minggu) |
| `input[type="color"]` | Warna Favorit |
| `input[type="password"]` | — |
| `<select>` + `<option>` | Agama, Prodi, Divisi, Semester |
| `<textarea>` | Alamat, Motivasi |
| `<datalist>` | Autocomplete Kota Lahir |
| `<fieldset>` + `<legend>` | Grouping Data Kesehatan |
| `<output>` | Tampilkan nilai dari range input |
| `<progress>` | Progress bar kelengkapan form |
| `button[type="submit"]` | Kirim Pendaftaran |
| `button[type="reset"]` | Reset seluruh form |

### 🎨 Canvas API
- Tanda tangan digital yang bisa digambar langsung di browser
- Pilih warna tinta & ketebalan garis
- Tombol hapus / reset kanvas
- Data signature disimpan sebagai base64 via hidden input

### 🖼️ SVG
- **Logo HIMATIK** — dibuat dari scratch dengan SVG (hexagon + circuit lines)
- **Infografis Divisi** — diagram node interaktif yang menampilkan seluruh struktur divisi HIMATIK

---

## 🛠️ Teknologi yang Digunakan

- **HTML5** — Struktur & semantik form
- **CSS3** — Styling, CSS Variables, Flexbox, animasi
- **Vanilla JavaScript** — Canvas drawing, progress bar, form validation, modal
- **Google Fonts** — Syne (heading) + DM Sans (body)
- **Canvas API** — Tanda tangan digital
- **SVG** — Logo & infografis

> ⚠️ Tidak menggunakan framework apapun (no Bootstrap, no Tailwind, no jQuery)

---

## 📸 Tampilan

```
┌────────────────────────────────────────┐
│  [Logo SVG]  HIMATIK — Himpunan TIK   │
│  Pendaftaran Anggota Baru 2024/2025   │
├────────────────────────────────────────┤
│  [Progress Bar Kelengkapan Form]       │
│                                        │
│  👤 Data Pribadi                       │
│  🎓 Data Akademik                      │
│  ⚡ Minat & Divisi                     │
│  📋 Informasi Tambahan                 │
│  📎 Upload Dokumen                     │
│  ✍️  Tanda Tangan Digital (Canvas)     │
│  🌐 Struktur Divisi (SVG Diagram)      │
│                                        │
│  [Reset]           [Kirim Pendaftaran] │
└────────────────────────────────────────┘
```

---

## ⚙️ Cara Menjalankan

**1. Clone repository ini**
```bash
git clone https://github.com/username/form-himatik.git
cd form-himatik
```

**2. Buka di browser**
```bash
# Langsung buka file HTML
open form_himatik.html

# Atau pakai Live Server di VS Code (Ctrl+Shift+P → Live Server)
```

> Tidak perlu `npm install` atau setup apapun. Langsung jalan! 🎉

---

## 📚 Konteks Akademik

| Info | Detail |
|---|---|
| **Mata Kuliah** | Pemrograman Web |
| **Semester** | 1 |
| **Tugas** | Form HTML dengan seluruh atribut form |
| **Topik** | HTML Form Elements, Canvas API, SVG |

---

## 🧠 Hal yang Dipelajari

- Penggunaan seluruh tipe `<input>` dalam HTML5
- Perbedaan `radio` vs `checkbox` dan kapan menggunakannya
- Cara kerja **Canvas API** untuk menggambar di browser
- Membuat grafik / ilustrasi dengan **SVG inline**
- CSS Variables (`--var`) untuk theming yang konsisten
- Form validation dengan JavaScript sederhana
- Responsive design dengan media query

---

## 👤 Author

**Farkhan Abdilah**  
Mahasiswa Semester 2 — Prodi Teknik Informatika  
NIM: 2507411012
📧 farkhanabdilah@gmail.com  
🐙 [github.com/h3rwthme](https://github.com/h3rwthme)

---

## 📄 Lisensi

Project ini dibuat untuk keperluan **tugas akademik**. Bebas digunakan sebagai referensi belajar.

---

<div align="center">
  <sub>Dibuat dengan ❤️ untuk tugas Pemrograman Web</sub><br/>
  <sub>⭐ Star repo ini kalau bermanfaat!</sub>
</div>
