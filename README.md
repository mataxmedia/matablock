# Tutorial MATABLOCK v.0.1
**Pencatat Blocking Pertunjukan** — oleh Matax Media

Aplikasi web: https://mataxmedia.github.io/matablock/

> **Catatan keakuratan:** Tutorial ini disusun dari antarmuka halaman aplikasi (menu, tombol, formulir, pintasan keyboard, dan keterangan dialog). Bagian yang fungsinya hanya bisa disimpulkan dari nama tombol ditandai **(perlu diverifikasi)**. Silakan dicek langsung di aplikasi.

---

## Daftar Isi
1. [Apa itu MATABLOCK?](#1-apa-itu-matablock)
2. [Mengenal Tampilan](#2-mengenal-tampilan)
3. [Mulai Cepat](#3-mulai-cepat)
4. [Mengatur Proyek dan Panggung](#4-mengatur-proyek-dan-panggung)
5. [Menambah dan Mengatur Objek di Panggung](#5-menambah-dan-mengatur-objek-di-panggung)
6. [Bekerja dengan Adegan (Timeline)](#6-bekerja-dengan-adegan-timeline)
7. [Info Adegan: Babak, Durasi, Cue, Catatan](#7-info-adegan-babak-durasi-cue-catatan)
8. [Memutar Animasi Adegan](#8-memutar-animasi-adegan)
9. [Menyimpan dan Membuka Proyek](#9-menyimpan-dan-membuka-proyek)
10. [Mencetak ke PDF](#10-mencetak-ke-pdf)
11. [Pintasan Keyboard](#11-pintasan-keyboard)
12. [Contoh Alur Kerja](#12-contoh-alur-kerja)
13. [Tips dan Pemecahan Masalah](#13-tips-dan-pemecahan-masalah)

---

## 1. Apa itu MATABLOCK?

MATABLOCK adalah aplikasi berbasis browser untuk **mencatat blocking pertunjukan**, yaitu posisi dan perpindahan aktor serta properti di panggung dari adegan ke adegan. Aplikasi ini berguna bagi sutradara, penata panggung, *stage manager*, dan kelompok teater.

Fungsi utamanya:

- Menggambar denah panggung sesuai bentuk dan ukuran sebenarnya (dalam meter).
- Menempatkan **aktor** dan **properti** sebagai penanda berwarna dan berlabel.
- Menyusun urutan **adegan** pada *timeline*, lengkap dengan babak, durasi, judul, cue teknis, dan catatan naskah.
- **Memutar animasi** perpindahan antar adegan.
- **Mencetak dokumen PDF** (lanskap, A4 atau A3) berisi metadata produksi, kanvas adegan, catatan, dan legenda.
- **Menyimpan dan mengimpor** proyek untuk dilanjutkan kemudian.

---

## 2. Mengenal Tampilan

Antarmuka terdiri dari beberapa area:

| Area | Isi |
|---|---|
| **Bilah atas** | Judul aplikasi, **Import Proyek**, **Simpan Proyek**, tombol **Undo** (⤺) dan **Redo** (⤻) |
| **Bilah alat** | Pengalih **Grid** dan **Bayangan**; tombol **Tambah Aktor**, **Tambah Properti**, **Atur Proyek**, **Cetak PDF** |
| **Kanvas panggung** | Denah panggung tempat objek ditempatkan dan digeser |
| **Timeline Adegan** | Daftar adegan, tombol **+ Adegan Baru**, dan tombol **▶ Putar Adegan** |
| **Panel Info Adegan** | Babak, Durasi, Judul Adegan, Cue Teknis, Catatan Naskah/Instruksi |
| **Panel Pengaturan Objek** | Nama Label, Warna Penanda, Hapus Objek (aktif saat ada objek terpilih) |
| **Kotak Pintasan Keyboard** | Daftar pintasan (lihat [bagian 11](#11-pintasan-keyboard)) |

---

## 3. Mulai Cepat

1. Buka https://mataxmedia.github.io/matablock/
2. Klik **Atur Proyek**, isi identitas produksi, pilih **Bentuk Panggung** dan ukurannya, lalu **Simpan & Terapkan**.
3. Klik **Tambah Aktor** dan **Tambah Properti** untuk menempatkan penanda di panggung. Geser ke posisi awal.
4. Pilih objek, lalu beri **Nama Label** dan **Warna Penanda** di panel *Pengaturan Objek*.
5. Isi **Info Adegan** (babak, durasi, judul, cue, catatan).
6. Klik **+ Adegan Baru**, lalu atur ulang posisi objek untuk adegan berikutnya.
7. Klik **▶ Putar Adegan** untuk melihat perpindahannya.
8. **Simpan Proyek** secara berkala, lalu **Cetak PDF** bila siap.

---

## 4. Mengatur Proyek dan Panggung

Klik **Atur Proyek** untuk membuka dialog **Pengaturan Proyek & Panggung**. Klik **Simpan & Terapkan** untuk menerapkan, atau **Batal** untuk menutup tanpa perubahan.

### 4.1 Identitas Produksi

| Kolom | Isi yang disarankan |
|---|---|
| **Judul Pertunjukan** | Nama lakon/pertunjukan |
| **Penggarap** | Sutradara atau penggarap |
| **Produksi / Kelompok** | Nama kelompok atau komunitas teater |
| **Penata Panggung / Artistik** | Penata artistik yang bertanggung jawab |

### 4.2 Pementasan

| Kolom | Isi yang disarankan |
|---|---|
| **Lokasi / Venue** | Nama gedung atau tempat pentas |
| **Kota** | Kota pementasan |
| **Tanggal Pentas** | Tanggal pertunjukan |

### 4.3 Versi Desain

| Kolom | Penjelasan |
|---|---|
| **Draf Desain Ke-** | Nomor urut draf (1, 2, 3, ...) |
| **Status Draf** | **Draf**, **Revisi**, atau **Final** |
| **Tanggal Draf** | Tanggal dokumen ini dibuat |

Bagian ini membantu melacak versi desain blocking antar latihan.

### 4.4 Panggung

| Kolom | Penjelasan |
|---|---|
| **Bentuk Panggung** | **Prosenium** (penonton 1 sisi), **Thrust** (penonton 3 sisi), **Arena** (penonton 4 sisi) |
| **Lebar (Meter)** | Lebar panggung sebenarnya |
| **Kedalaman (Meter)** | Kedalaman panggung sebenarnya |

Panduan memilih bentuk:

- **Prosenium**: panggung gedung pertunjukan konvensional, penonton menghadap dari satu sisi.
- **Thrust**: panggung menjorok ke penonton, dilihat dari tiga sisi.
- **Arena**: penonton mengelilingi panggung dari empat sisi.

Masukkan ukuran sesuai panggung nyata agar posisi dan jarak pada denah akurat.

---

## 5. Menambah dan Mengatur Objek di Panggung

### 5.1 Jenis objek

- **Aktor**: ditambahkan dengan **Tambah Aktor**
- **Properti**: ditambahkan dengan **Tambah Properti**

### 5.2 Memilih objek

| Cara | Fungsi |
|---|---|
| Klik objek | Memilih satu objek |
| `Shift` + klik | **Multi seleksi** (menambah/mengurangi objek terpilih) |
| Seret area kosong (`Drag Area`) | **Seleksi kotak**, memilih semua objek di dalam area |

### 5.3 Panel Pengaturan Objek

Saat satu atau lebih objek terpilih, panel *Pengaturan Objek* aktif:

| Pengaturan | Penjelasan |
|---|---|
| **Nama Label** | Teks pada penanda (misalnya nama tokoh seperti "Hamlet" atau nama properti seperti "Kursi") |
| **Warna Penanda** | Warna objek, berguna untuk membedakan tokoh/kelompok |
| **Hapus Objek** | Menghapus objek terpilih (juga lewat `Del` / `Backspace`) |

Jika belum ada objek terpilih, panel menampilkan petunjuk: *"Pilih satu atau lebih objek pada panggung untuk mengubah propertinya."*

### 5.4 Grid dan Bayangan

- **Grid**: pengalih untuk menampilkan atau menyembunyikan garis bantu pada kanvas, membantu penempatan yang rapi dan terukur.
- **Bayangan**: pengalih tampilan bayangan objek. **(perlu diverifikasi)** Pada aplikasi blocking, fitur ini biasanya menampilkan posisi objek pada adegan sebelumnya sebagai acuan perpindahan. Coba aktifkan dan geser objek untuk memastikan.

### 5.5 Undo dan Redo

- **⤺** atau `Ctrl+Z`: urungkan tindakan terakhir
- **⤻**: ulangi tindakan yang diurungkan

---

## 6. Bekerja dengan Adegan (Timeline)

**Timeline Adegan** berisi daftar adegan berurutan. Setiap adegan menyimpan satu "potret" posisi objek di panggung.

**Menambah adegan:** klik **+ Adegan Baru**.

**Berpindah adegan:** klik adegan pada timeline, atau tekan `←` / `→` pada keyboard.

**Menyusun blocking:**
1. Pada Adegan 1, tempatkan semua aktor dan properti pada posisi awal.
2. Klik **+ Adegan Baru**.
3. Geser objek ke posisi baru sesuai perpindahan (entrance, exit, crossing).
4. Ulangi untuk setiap perubahan blocking.

> **(perlu diverifikasi)** Apakah adegan baru menyalin posisi adegan sebelumnya atau mulai kosong. Cobalah dengan satu objek lebih dulu agar Anda tahu perilakunya.

---

## 7. Info Adegan: Babak, Durasi, Cue, Catatan

Panel **Info Adegan** menyimpan data tiap adegan (isi berbeda untuk setiap adegan):

| Kolom | Penjelasan | Contoh |
|---|---|---|
| **Babak** | Babak tempat adegan berada | `Babak 1` |
| **Durasi** | Perkiraan lama adegan | `3 menit` |
| **Judul Adegan** | Nama singkat adegan | `Pertemuan di Taman` |
| **Cue Teknis** | Isyarat tata cahaya, suara, efek, atau perpindahan set | `LX 12 fade in; SFX hujan` |
| **Catatan Naskah / Instruksi** | Kutipan naskah, arahan sutradara, atau instruksi gerak | `A masuk dari kiri panggung, berhenti di tengah, lalu berbalik.` |

Isi bagian ini selengkap mungkin karena **kanvas adegan, catatan, dan legenda ikut tercetak** pada PDF.

---

## 8. Memutar Animasi Adegan

- Klik **▶ Putar Adegan** atau tekan `Space`.
- Aplikasi memperagakan perpindahan objek dari adegan ke adegan.
- Berguna untuk menunjukkan blocking kepada aktor atau kru tanpa harus latihan penuh.

> **(perlu diverifikasi)** Apakah animasi memutar seluruh adegan dari awal atau dari adegan terpilih, dan apakah `Space` kembali menghentikan putaran.

---

## 9. Menyimpan dan Membuka Proyek

| Tombol | Fungsi |
|---|---|
| **Simpan Proyek** | Menyimpan seluruh proyek (identitas, panggung, objek, adegan) agar bisa dilanjutkan nanti |
| **Import Proyek** | Memuat kembali proyek yang pernah disimpan |

Saran:
- Simpan setiap selesai sesi kerja dan sebelum menutup tab.
- Beri nama berkas yang jelas, misalnya `Hamlet_Draf2_Revisi_2026-11-04`.
- Simpan salinan di dua tempat (komputer dan penyimpanan awan/flashdisk).
- Gunakan **Draf Desain Ke-** dan **Status Draf** di pengaturan proyek untuk menandai versi.

> **(perlu diverifikasi)** Format berkas yang dihasilkan dan apakah aplikasi menyimpan otomatis di browser. Jangan bergantung pada penyimpanan otomatis; selalu gunakan **Simpan Proyek**.

---

## 10. Mencetak ke PDF

1. Klik **Cetak PDF** untuk membuka dialog **Cetak Dokumen PDF**.
2. Pilih **Ukuran Kertas PDF**:
   - **A4 (Standar)**
   - **A3 (Lebar)**
3. Klik **Unduh PDF**.
4. Tunggu indikator **"Menyiapkan dokumen…"** dan persentase hingga 100%.
5. Klik **Batal** bila ingin menutup tanpa mengunduh.

Ketentuan dokumen:
- Orientasi **Lanskap**.
- Resolusi setara **300 dpi**.
- Setiap halaman memuat: **kotak metadata** (identitas produksi dan versi), **kanvas adegan**, **catatan**, dan **legenda**.

Tips cetak:
- Lengkapi **Atur Proyek** dan **Info Adegan** sebelum mencetak.
- Gunakan **A3** untuk panggung besar atau banyak objek agar label mudah dibaca.
- Saat mencetak PDF, pilih **ukuran sebenarnya (100%)**.

---

## 11. Pintasan Keyboard

| Pintasan | Fungsi |
|---|---|
| `Shift` + Klik | Multi seleksi |
| `Drag Area` | Seleksi kotak |
| `Ctrl` + `Z` | Undo |
| `Space` | Mulai animasi |
| `←` / `→` | Pindah adegan |
| `Del` / `Backspace` | Hapus item |

---

## 12. Contoh Alur Kerja

### Menyusun blocking satu babak
1. **Atur Proyek**: isi judul lakon, sutradara, kelompok, venue, tanggal pentas. Pilih **Prosenium**, lebar `10` m, kedalaman `8` m.
2. **Tambah Aktor** sebanyak tokoh di adegan pembuka; beri nama label dan warna berbeda tiap tokoh.
3. **Tambah Properti**: meja, kursi, pintu, dan lainnya; beri label.
4. Isi **Info Adegan**: Babak 1, durasi, judul, cue teknis, catatan naskah.
5. **+ Adegan Baru** untuk tiap perubahan penting; geser objek ke posisi baru.
6. Gunakan `←` / `→` untuk meninjau, **▶ Putar Adegan** untuk melihat alurnya.
7. **Simpan Proyek**, lalu **Cetak PDF** untuk dibagikan saat latihan.

### Merevisi setelah latihan
1. **Import Proyek** untuk memuat berkas terakhir.
2. Perbaiki posisi dan catatan.
3. Di **Atur Proyek**, naikkan **Draf Desain Ke-**, ubah **Status Draf** menjadi *Revisi*, dan perbarui **Tanggal Draf**.
4. **Simpan Proyek** dengan nama berkas baru, lalu cetak ulang.

---

## 13. Tips dan Pemecahan Masalah

| Masalah | Solusi |
|---|---|
| Panel Pengaturan Objek tidak aktif | Klik objek lebih dulu di panggung |
| Salah memindahkan/menghapus objek | Tekan `Ctrl+Z` atau tombol ⤺ |
| Ingin menggeser beberapa objek sekaligus | `Shift`+klik atau seret area kosong untuk seleksi kotak |
| Posisi sulit diatur rapi | Aktifkan **Grid** |
| Ukuran objek terasa tidak sesuai skala | Periksa **Lebar** dan **Kedalaman** panggung di **Atur Proyek** |
| Label PDF terlalu kecil | Pilih **A3 (Lebar)** dan persingkat **Nama Label** |
| PDF lama dibuat | Resolusi 300 dpi dan banyak adegan memang memakan waktu; tunggu sampai 100% |
| Takut kehilangan pekerjaan | Gunakan **Simpan Proyek** berkala dan simpan salinan |

**Praktik terbaik:**
1. Isi ukuran panggung yang akurat sejak awal.
2. Pakai warna konsisten untuk tiap tokoh di seluruh adegan.
3. Satu adegan = satu perubahan blocking yang jelas.
4. Tulis cue teknis dan catatan secara ringkas agar muat di PDF.

---

*MATABLOCK v.0.1 dibuat oleh Matax Media. Tutorial ini disusun dari antarmuka versi 0.1; tampilan dan fitur dapat berubah pada versi berikutnya.*
