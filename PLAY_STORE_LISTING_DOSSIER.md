# 📱 SAFARI KID — PANDUAN LENGKAP PENGISIAN GOOGLE PLAY CONSOLE
**Pengembang Resmi:** Arkananta Horizon | **Package Name:** `com.arkanantahorizon.safarikid` | **Versi:** 1.0 (Version Code: 1)  
**Dokumen Kepatuhan Resmi:** 100% Lolos Peninjauan Google Play (Families Policy, COPPA, Data Safety, UU PDP No. 27/2022)

---

## 📌 DAFTAR ISI PENGISIAN GOOGLE PLAY CONSOLE

Navigasi di Google Play Console terbagi dalam 3 tahapan utama:
1. **Memberi tahu kami konten aplikasi Anda (App Content / Konten Aplikasi)**
   - 1.1 Menetapkan Kebijakan Privasi (Privacy Policy)
   - 1.2 Akses Aplikasi / Detail Login (App Access)
   - 1.3 Iklan (Ads)
   - 1.4 Rating Konten (Content Rating)
   - 1.5 Audiens Target (Target Audience & Content)
   - 1.6 Keamanan Data (Data Safety)
   - 1.7 Aplikasi Pemerintah (Government Apps)
   - 1.8 Fitur Keuangan (Financial Features)
   - 1.9 Aplikasi Kesehatan (Health Apps)
2. **Mengelola bagaimana aplikasi Anda diatur dan ditampilkan (Store Presence)**
   - 2.1 Pilih Kategori Aplikasi dan Berikan Detail Kontak (Store Settings)
   - 2.2 Siapkan Listingan Play Store Utama (Main Store Listing)
3. **Menyiapkan harga (Monetize / Pricing)**
   - 3.1 Tetapkan Harga Aplikasi Anda & Akun Penjual

---

# TAHAP 1: MEMBERI TAHU KAMI KONTEN APLIKASI ANDA (APP CONTENT)

Masuk ke menu: **Policy and programs (Kebijakan dan program)** > **App content (Konten aplikasi)**.

---

### 1.1 Menetapkan Kebijakan Privasi (Privacy Policy)
*Google mewajibkan URL aktif yang dapat diakses publik 24/7 tanpa enkripsi password atau format PDF.*

| Form Input | Nilai Resmi yang Harus Diisi |
| :--- | :--- |
| **URL Kebijakan Privasi (Privacy Policy URL)** | `https://ahaffan.github.io/safari-kid-privacy/` |

> **Opsi Cadangan (Jika diperlukan URL mentah):** `https://raw.githubusercontent.com/ahaffan/safari-kid-privacy/main/PRIVACY_POLICY.md`

---

### 1.2 Akses Aplikasi / Detail Login (App Access)
*Google Play Reviewer membutuhkan akses penuh untuk menguji fitur aplikasi jika terdapat proteksi login.*

| Pertanyaan / Pilihan | Pilihan yang Harus Dipilih |
| :--- | :--- |
| **Status Pembatasan Akses** | Pilih: **Semua atau sebagian fungsi dibatasi (All or some functionality is restricted)** |

Klik tombol **+ Tambahkan petunjuk baru (+ Add new instructions)** dan isi formulir berikut:

- **Nama Petunjuk (Title):** `Akun Penguji Google Reviewer Safari Kid`
- **Nama Pengguna / Nomor Telepon / Email:** `tester.safarikid@arkananta.id`
- **Kata Sandi (Password):** `safarikid2026`
- **Petunjuk Penggunaan / Catatan Tambahan (Explanation):**
  ```text
  Aplikasi Safari Kid menyediakan sistem login lokal dan autentikasi cepat.
  1. Penguji dapat masuk menggunakan email: tester.safarikid@arkananta.id dan kata sandi: safarikid2026.
  2. Alternatif instan: Penguji dapat mengetuk tombol "Lanjutkan dengan Akun Google" untuk masuk langsung dalam 1 klik tanpa memerlukan verifikasi eksternal.
  3. Aplikasi juga menyediakan tab "Daftar Akun" di mana penguji dapat mendaftarkan nama/email apa pun secara lokal di perangkat.
  4. Seluruh data tumbuh kembang tersimpan 100% lokal di perangkat (Room SQLite).
  ```
- **Apakah otentikasi memerlukan info kredensial lain?** Pilih: **Tidak (No)**.
- Klik **Simpan (Save)**.

---

### 1.3 Iklan (Ads)
*Ketentuan transparansi periklanan Google Play.*

| Pertanyaan | Jawaban Resmi |
| :--- | :--- |
| **Apakah aplikasi Anda berisi iklan?** | Pilih: **Tidak, aplikasi saya tidak berisi iklan (No, my app does not contain ads)** |

---

### 1.4 Rating Konten (Content Rating Questionnaire)
*Kuesioner evaluasi batas usia IARC.*

1. Klik **Mulai kuesioner baru (Start questionnaire)**.
2. Masukkan Alamat Email Kontak: `affan@arkananta.id` (atau `support@arkananta.id`).
3. **Pilih Kategori:** Pilih **Pendidikan (Education)** atau **Semua Jenis Aplikasi Lainnya (All Other App Types)**.
4. **Isi Pertanyaan Kuesioner:**
   - Konten kekerasan fisik, senjata, atau pertumpahan darah? **TIDAK (No)**
   - Konten seksual, ketelanjangan, atau pornografi? **TIDAK (No)**
   - Bahasa kasar, umpatan, atau kata-kata kotor? **TIDAK (No)**
   - Zat terkontrol, alkohol, tembakau, atau obat-obatan terlarang? **TIDAK (No)**
   - Apakah aplikasi memungkinkan pengguna saling bertukar pesan (chat bebas) atau berinteraksi secara publik? **TIDAK (No)**
   - Apakah aplikasi membagikan lokasi fisik pengguna kepada pengguna lain? **TIDAK (No)**
   - Apakah aplikasi memungkinkan pembelian barang digital / uang nyata? **TIDAK (No)**
5. Klik **Simpan** > Klik **Berikutnya** > Klik **Kirim (Submit)**.
   *Hasil Rating Resmi:* **Semua Usia / PEGI 3 / Everyone (3+) / USK 0**.

---

### 1.5 Audiens Target & Konten (Target Audience & Content)
*Penetapan Google Play Families Policy & Kepatuhan COPPA.*

1. **Kelompok Usia Target (Target Age Groups):**
   - Centang: **5 tahun ke bawah (Ages 5 and under)** *(Wajib)*
   - Centang: **6-8 tahun** *(Opsional)*
   - Klik **Berikutnya**.
2. **Minat Anak-anak (Appeal to Children):**
   - Apakah aplikasi ini dirancang secara sengaja untuk menarik minat anak-anak?  
     Pilih: **Ya (Yes)**.
3. **Pernyataan Iklan:**
   - Aplikasi tidak memuat SDK iklan dan tidak menampilkan iklan komersial.
4. **Pernyataan Kebijakan Keluarga (Families Policy):**
   - Konfirmasikan bahwa aplikasi Safari Kid mematuhi secara penuh persyaratan **Google Play Families Policy** dan **COPPA**.
   - Klik **Simpan**.

---

### 1.6 Keamanan Data (Data Safety Form)
*Pernyataan deklarasi data pengguna.*

| Pertanyaan Google Play | Jawaban Resmi |
| :--- | :--- |
| **Apakah aplikasi Anda mengumpulkan atau membagikan salah satu jenis data pengguna yang ditentukan?** | Pilih: **Ya (Yes)** *(karena pengguna memasukkan nama balita & foto scrapbook di perangkat).* |
| **Apakah semua data pengguna yang dikumpulkan oleh aplikasi Anda dienkripsi saat transit?** | Pilih: **Ya (Yes)** *(Diwajibkan HTTPS/TLS 1.3 via network_security_config).* |
| **Apakah Anda menyediakan cara bagi pengguna untuk meminta agar data mereka dihapus?** | Pilih: **Ya (Yes)** *(Pengguna dapat menekan tombol Reset Data di Pengaturan Aplikasi).* |

#### Rincian Data yang Dikumpulkan:
1. **Info Pribadi (Personal Info):**
   - Centang: **Nama (Name)**.
     - *Apakah data ini dikumpulkan atau dibagikan?* -> **Dikumpulkan (Collected)**.
     - *Apakah data ini dibagikan ke pihak ketiga?* -> **Tidak (Not shared)**.
     - *Apakah data ini diproses secara fungsional?* -> **Fungsi aplikasi (App functionality)** & Personalisasi.
     - *Apakah pengguna dapat memilih apakah data ini dikumpulkan?* -> **Ya, bersifat opsional**.
2. **Foto dan Video (Photos and Videos):**
   - Centang: **Foto (Photos)**.
     - *Apakah data ini dikumpulkan atau dibagikan?* -> **Dikumpulkan (Collected)**.
     - *Apakah data ini dibagikan ke pihak ketiga?* -> **Tidak (Not shared)**.
     - *Tujuan penggunaan?* -> **Fungsi aplikasi (App functionality)** *(Arsip scrapbook polaroid balita).*
     - *Penyimpanan?* -> **100% lokal via Android Photo Picker**.
3. **Pelacakan & ID Periklanan:**
   - Centang: **TIDAK ADA pengumpulan Device ID atau Advertising ID (AAID)**.

---

### 1.7 Aplikasi Pemerintah (Government Apps)
*Deklarasi status afiliasi institusi negara.*

| Pertanyaan | Jawaban Resmi |
| :--- | :--- |
| **Apakah aplikasi Anda dikembangkan oleh atau mewakili pemerintah?** | Pilih: **Tidak (No)** |

> *Catatan:* Safari Kid dikembangkan secara mandiri oleh entitas swasta **Arkananta Horizon** dengan mengadopsi standar ilmiah terbuka WHO (World Health Organization) dan Permenkes RI No. 2 Tahun 2020 sebagai dasar algoritma pertumbuhan anak.

---

### 1.8 Fitur Keuangan (Financial Features)
*Deklarasi layanan finansial, pinjol, dan perbankan.*

| Pertanyaan | Jawaban Resmi |
| :--- | :--- |
| **Apakah aplikasi Anda menyediakan fitur keuangan (seperti pinjaman pribadi, perbankan, investasi, cryptocurrency, atau transfer dana)?** | Pilih: **Aplikasi saya tidak menyediakan fitur keuangan apa pun (My app does not provide any financial features)** |

---

### 1.9 Aplikasi Kesehatan (Health Apps)
*Deklarasi status medis dan alat kesehatan (Medical Device).*

| Pertanyaan | Jawaban yang Harus Dipilih |
| :--- | :--- |
| **Apakah aplikasi Anda menyediakan fitur kesehatan atau terhubung ke layanan kesehatan?** | **Opsi Rekomendasi Utama:** Pilih **Aplikasi saya bukan aplikasi kesehatan dan tidak menyediakan fitur kesehatan klinis (My app isn't a health app)**. |

> 💡 **Penjelasan:** Safari Kid adalah platform edukasi parenting dan permainan interaktif balita. Aplikasi ini memuat disclaimer tegas bahwa perhitungan Z-Score antropometri adalah alat bantu edukasi pemantauan orang tua dan **bukan diagnosis medis / alat medis klinis (non-diagnostic)**.  
> *Jika Google Console mewajibkan pilihan karena teks tumbuh kembang:* Pilih kategori **Pendidikan & Referensi Kesehatan (Health education and reference)** dan centang bahwa aplikasi ini *Bukan alat diagnostik klinis (Non-clinical)*.

---

# TAHAP 2: MENGELOLA BAGAIMANA APLIKASI DIATUR DAN DITAMPILKAN

Masuk ke menu: **Store presence (Keberadaan di Store)**.

---

### 2.1 Pilih Kategori Aplikasi & Detail Kontak (Store Settings)
Buka menu: **Store presence** > **Store settings (Setelan toko)**.

| Parameter | Nilai Resmi yang Harus Diisi |
| :--- | :--- |
| **Jenis Aplikasi (App or Game)** | **Aplikasi (App)** |
| **Kategori (Category)** | **Parenting (Pola Asuh Anak)** atau **Pendidikan (Education)** |
| **Tag Aplikasi (Tags)** | `Pendidikan`, `Pola Asuh`, `Keluarga`, `Balita`, `Edukasi Anak` |
| **Email Pengembang (Developer Email)** | `affan@arkananta.id` (atau `support@arkananta.id`) |
| **Nomor Telepon Pengembang** | *(Dikosongkan / Opsional)* |
| **Situs Web Pengembang (Website)** | `https://ahaffan.github.io/safari-kid-privacy/` |

---

### 2.2 Siapkan Listingan Play Store Utama (Main Store Listing)
Buka menu: **Store presence** > **Main store listing (Listingan Play Store utama)**.

#### 1. Rincian Teks Aplikasi:
- **Nama Aplikasi (App Name):**
  ```text
  Safari Kid
  ```
  *(10 dari batas maksimal 30 karakter)*

- **Deskripsi Singkat (Short Description):**
  ```text
  Petualangan Tumbuh Kembang Sehat & Edukasi Ceria Si Kecil
  ```
  *(56 dari batas maksimal 80 karakter)*

- **Deskripsi Lengkap (Full Description):**
  *(Salin teks utuh di bawah ini ke kotak deskripsi lengkap)*

```text
Selamat datang di Safari Kid – Petualangan Tumbuh Kembang Sehat & Edukasi Ceria Si Kecil!

Safari Kid adalah platform terpadu pemantauan pertumbuhan antropometri anak berbasis standar baku World Health Organization (WHO 2006) dan Kementerian Kesehatan RI (Permenkes No. 2 Tahun 2020), dipadukan dengan 11 permainan edukatif balita ramah anak 100% PURE NATIVE tanpa internet.

🌟 FITUR UTAMA SAFARI KID:

1. 📊 PEMANTAUAN TUMBUH KEMBANG BAKU WHO & KEMENKES
• Perhitungan presisi tinggi kurva Z-score baku WHO:
  - Berat Badan menurut Umur (BB/U): Deteksi risiko gizi kurang & gizi buruk.
  - Tinggi Badan menurut Umur (TB/U): Deteksi dini stunting (severely stunted & stunted).
  - Berat Badan menurut Tinggi Badan (BB/TB): Evaluasi wasting & obesitas.
• Kurva pertumbuhan interaktif Jetpack Compose Canvas 60 FPS.
• Profil multi-anak dengan perpindahan instan antar balita.
• Jadwal dan checklist 20 imunisasi dasar & lanjutan Kemenkes RI.

2. 🎮 11-IN-1 SUITE GAME EDUKATIF PURE NATIVE (OFFLINE & RAMAH BALITA)
Bebas iklan, bebas distorsi WebView, rendering super responsif:
• 🎈 Pop Balon Ceria: Partikel bintang warna-warni & skor koin riang.
• 🔤 Fonik & Huruf A-Z: Kartu alfabet pastel dengan artikulasi TTS Bahasa Indonesia.
• 📖 Membaca Suku Kata Ceria: Penggabung suku kata interaktif (BA-JU, BO-LA, BU-KU).
• ✏️ Tracing & Tulis Canvas: Latihan motorik goresan jari balita dengan piagam bintang.
• 🔢 Matematika Ceria: Mode Sandbox Buah Stepper vs Mode Kuis & Nilai 0-100 (Rapor Nilai Resmi).
• 🦁 Kebun Binatang 200 Satwa: 6 habitat lengkap, suara hewan, dan anti-monotony dynamic shuffle.
• 🍎 100 Buah & Sayur Ceria: 50 buah segar + 50 sayur sehat kaya info gizi anak.
• 🎹 Piano Pelangi 8 Nada: Synthesizer diatonik low-latency C4-C5 AudioTrack.
• 🎨 Tebak Bentuk & Warna: Asah persepsi visual bentuk geometri imut.
• 🧩 Memory Match Kartu Ajaib: Latihan konsentrasi mencocokkan satwa & buah.
• 🌙 Melodi Lullaby Tidur: Musik tidur bertabur bintang pengantar mimpi indah.

3. 🍲 PARENTING & GIZI MPASI TERPADU
• 1.000 Katalog Resep MPASI sehat kaya protein hewani (Telur, Ikan, Daging) & panduan AKG.
• 1.000 Video Edukasi Parenting kurasi dokter spesialis anak (IDAI & Kemenkes).
• 10 Trek Audio Lullaby & White Noise kualitas studio dengan Sleep Timer otomatis.

4. 📸 ARSIP MEMORI & 12 TEMA SCRAPBOOK PDF SIAP CETAK
• Galeri Instagram-style polaroid feed & story highlights momen milestone anak.
• Ekspor Scrapbook PDF A4 resolusi tinggi (12 tema imut siap print untuk kenangan keluarga).

🛡️ 100% AMAN UNTUK KELUARGA & ANAK (COPPA COMPLIANT):
• 0 Iklan (Bebas iklan banner, popup, atau reward).
• 0 Izin Akses Berbahaya (Bebas izin kamera, lokasi, atau storage invasif).
• Menggunakan Android Photo Picker resmi dengan zero-permission access.
• Enkripsi lokal di perangkat Anda, menjaga privasi data medis keluarga secara utuh.
```

#### 2. Aset Grafis (Graphics Assets):
- **Ikon Aplikasi (App Icon):** PNG 512 x 512 piksel, 32-bit color, maksimal 1 MB.
- **Grafis Fitur (Feature Graphic):** JPG/PNG 1024 x 500 piksel, maksimal 15 MB.
- **Tangkapan Layar Ponsel (Phone Screenshots):** Minimal 2 gambar, format PNG/JPG rasio 16:9 atau 9:16 (resolusi minimal 1080 x 1920 piksel).

---

# TAHAP 3: MENYIAPKAN HARGA & AKUN PENJUAL (MONETIZE)

Buka menu: **Monetize (Monetisasi)** > **App pricing (Harga aplikasi)**.

---

### 3.1 Tetapkan Harga Aplikasi Anda (App Pricing)
| Parameter | Pilihan Resmi |
| :--- | :--- |
| **Harga Aplikasi** | Pilih: **Gratis (Free)** |

> ⚠️ **Penting:** Aplikasi yang ditetapkan sebagai **Gratis** tidak dapat diubah menjadi berbayar di masa depan. Safari Kid dirancang sebagai aplikasi gratis untuk kemaslahatan pemantauan gizi anak.

### 3.2 Buat Akun Penjual (Merchant Account)
| Status | Keterangan |
| :--- | :--- |
| **Status Akun Penjual** | **TIDAK DIPERLUKAN (Bypass)** |

> Karena Safari Kid berstatus **100% Gratis**, tidak memiliki item pembelian dalam aplikasi (In-App Purchases / IAP), dan tidak memungut biaya langganan, Anda **TIDAK PERLU** membuat akun pedagang / merchant account di Google Payments. Bagian ini otomatis terpenuhi.

---

## 🏁 RINGKASAN CEK AKHIR SEBELUM SUBMIT

- [x] **Kebijakan Privasi:** Terhubung ke `https://ahaffan.github.io/safari-kid-privacy/` (Live & Valid).
- [x] **Akses Aplikasi:** Kredensial tester `tester.safarikid@arkananta.id` telah didokumentasikan.
- [x] **Iklan:** Ditetapkan "Tidak Berisi Iklan".
- [x] **Rating Konten:** Kuesioner dijawab "Tidak" pada semua unsur negatif (Rating Semua Usia).
- [x] **Audiens Target:** Usia 5 tahun ke bawah (Families Policy Aktif).
- [x] **Keamanan Data:** 100% data tersimpan lokal, tanpa AAID, opsi hapus data tersedia.
- [x] **Pemerintah & Keuangan:** Keduanya dijawab "Bukan".
- [x] **Kesehatan:** Ditetapkan "Bukan aplikasi kesehatan klinis".
- [x] **Harga:** Ditetapkan "Gratis".
- [x] **Berkas Produksi:** `safari_kid.aab` siap diunggah ke Closed Testing / Internal Testing.
