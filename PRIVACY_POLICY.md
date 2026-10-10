# Kebijakan Privasi / Privacy Policy — Safari Kid

**Terakhir Diperbarui / Last Updated:** 10 Oktober 2026  
**Pengembang Resmi / Official Developer:** Arkananta Horizon  
**Nama Aplikasi / Application Name:** Safari Kid (dahulu GrowTrack Kids)  
**ID Aplikasi / Application ID:** `com.arkanantahorizon.safarikid` (dan alias paket preservasi `com.example.growtrackkids`)  
**Kontak Resmi / Official Contact:** affan@arkananta.id | support@arkananta.id  

---

## 🇮🇩 Bahasa Indonesia

Selamat datang di **Safari Kid** ("Aplikasi"), platform terpadu pemantauan pertumbuhan antropometri anak berbasis standar baku World Health Organization (WHO 2006) dan Kementerian Kesehatan Republik Indonesia (Permenkes No. 2 Tahun 2020), yang dilengkapi dengan suite permainan edukatif ramah anak.

Kebijakan Privasi ini menjelaskan bagaimana **Arkananta Horizon** mengelola, menjaga, dan melindungi informasi pribadi pengguna, khususnya privasi anak dan keluarga saat menggunakan aplikasi Safari Kid. Dokumen ini disusun untuk mematuhi secara penuh:
1. **Google Play Families Policy** (Kebijakan Keluarga Google Play).
2. **Children's Online Privacy Protection Act (COPPA)** (16 C.F.R. Part 312).
3. **Undang-Undang Republik Indonesia No. 27 Tahun 2022 tentang Perlindungan Data Pribadi (UU PDP)**.
4. **General Data Protection Regulation (GDPR / GDPR-K)** terkait perlindungan data anak.

---

### 1. Komitmen Perlindungan Privasi Anak (Families Policy & COPPA Compliance)
- Aplikasi Safari Kid dirancang khusus untuk anak usia **0–5 tahun (balita)** dan orang tua/wali pengasuh.
- **TIDAK ADA PENGUMPULAN DATA PRIBADI IDENTIFIKATIF DARI ANAK**: Kami tidak secara sadar mengumpulkan, melacak, atau meminta informasi identitas pribadi (seperti nama lengkap, alamat fisik, nomor telepon, atau data geolokasi presisi) dari anak di bawah usia 13 tahun.
- Seluruh interaksi edukasi dan permainan di dalam aplikasi berjalan tanpa membutuhkan identitas anak atau pembuatan akun anak independen.

---

### 2. Informasi yang Dikelola & Cara Penyimpanannya

#### a. Data Pertumbuhan & Antropometri (Dikelola Secara Lokal)
- **Data yang dimasukkan orang tua/pengasuh**: Nama panggilan atau inisial anak, tanggal lahir, jenis kelamin, serta parameter fisik (berat badan, panjang/tinggi badan, lingkar kepala).
- **Tujuan Penggunaan**: Data ini digunakan **semata-mata** untuk menghitung persentil pertumbuhan dan Z-score antropometri baku WHO (BB/U, TB/U, BB/TB) serta menampilkan riwayat kurva pertumbuhan.
- **Metode Penyimpanan**: **100% DISIMPAN SECARA LOKAL** di database internal perangkat Anda (SQLite/Room storage terenkripsi). Data ini **TIDAK PERNAH DIUNGGAH, DISIMPAN, ATAU DIBAGIKAN** ke server cloud Arkananta Horizon maupun server pihak ketiga mana pun.

#### b. Foto Kenangan & Scrapbook
- Pengguna dapat memilih foto dari perangkat untuk melengkapi scrapbook atau background tema anak.
- Aplikasi memanfaatkan sistem resmi **Android Photo Picker** (zero-permission media picker) yang hanya mengakses berkas gambar yang dipilih secara sadar oleh pengguna tanpa memerlukan izin akses menyeluruh ke galeri atau kartu memori.
- Foto-foto ini disimpan secara eksklusif di direktori penyimpanan lokal terisolasi milik aplikasi (*app-specific internal storage*).

#### c. Akun Pengguna & Otentikasi (Opsional)
- Jika pengguna memilih untuk menggunakan akun orang tua (misalnya melalui autentikasi Google Sign-In atau email orang tua), kredensial otentikasi diproses secara aman menggunakan protokol standar industri untuk memverifikasi hak akses orang tua.

---

### 3. Izin Akses Perangkat (Device Permissions)

Safari Kid meminimalkan izin akses perangkat sesuai prinsip privasi *Data Minimization*:

| Izin (Permission) | Status | Keterangan & Rasionil |
| :--- | :--- | :--- |
| `android.permission.INTERNET` | **Aktif** | Digunakan hanya untuk memuat streaming katalog video edukasi parenting resmi Kemenkes/WHO dan pemeriksaan update resmi aplikasi. |
| Izin Lokasi (`ACCESS_FINE_LOCATION`, `ACCESS_COARSE_LOCATION`) | **TIDAK DIGUNAKAN** | Kami tidak pernah melacak lokasi pengguna atau anak. |
| Izin Kamera (`CAMERA`) | **TIDAK DIGUNAKAN** | Aplikasi tidak meminta akses sensor kamera secara langsung. |
| Izin Mikrofon (`RECORD_AUDIO`) | **TIDAK DIGUNAKAN** | Suara instrumen piano dan fonik diproses melalui synthesizer audio lokal (`AudioTrack`), tanpa merekam audio pengguna. |
| Izin Penyimpanan Invasif (`READ_EXTERNAL_STORAGE`, `MANAGE_EXTERNAL_STORAGE`) | **TIDAK DIGUNAKAN** | Akses media sepenuhnya menggunakan Android Photo Picker modern. |

---

### 4. Bebas Iklan & Pelacak Komersial (Zero Ads & Zero Commercial Trackers)

- **100% Bebas Iklan**: Safari Kid tidak menampilkan iklan banner, iklan interstisial, pop-up, atau iklan berhadiah.
- **Tanpa SDK Iklan**: Aplikasi tidak menyertakan SDK periklanan pihak ketiga apa pun (seperti Google AdMob, Unity Ads, AppLovin, Facebook Audience Network, dll.).
- **Tanpa Pelacakan Lintas Aplikasi (No Behavioral Profiling)**: Kami tidak mengumpulkan Pengenal Iklan Google (AAID - Android Advertising ID) dan tidak membuat profil perilaku anak untuk keperluan pemasaran.

---

### 5. Keamanan Data (Data Security)

Arkananta Horizon menerapkan standar keamanan teknis yang ketat untuk melindungi data pengguna:
1. **Enkripsi Saat Transit**: Semua komunikasi jaringan (seperti pemuatan metadata video edukasi) diwajibkan menggunakan protokol aman **HTTPS/TLS 1.3** yang ditegakkan melalui `network_security_config.xml`.
2. **Isolasi Sandbox Aplikasi**: Data lokal dilindungi oleh mekanisme sandbox sistem operasi Android, sehingga aplikasi lain tidak dapat membaca data pertumbuhan anak Anda.
3. **Verifikasi Integritas Runtime**: Dilengkapi dengan modul `AppSecurityGuard` untuk memastikan keaslian paket aplikasi dan melindungi dari modifikasi tidak sah.

---

### 6. Hak Pengguna & Prosedur Penghapusan Data (Data Retention & Deletion)

Sesuai dengan ketentuan Google Play Data Safety dan UU PDP:
- **Hak Akses & Koreksi**: Orang tua dapat melihat, mengubah, atau memperbarui data profil anak kapan saja secara langsung di dalam aplikasi.
- **Hak Penghapusan Seketika (Instant Data Erasure)**:
  - Pengguna dapat menghapus seluruh data anak, riwayat kurva, dan foto scrapbook kapan saja dengan menekan tombol **"Reset Data"** di menu Pengaturan Aplikasi.
  - Menghapus data aplikasi melalui **Pengaturan Android > Aplikasi > Safari Kid > Hapus Data / Clear Storage** akan melenyapkan 100% data lokal secara permanen.
  - Menghapus (uninstall) aplikasi dari perangkat akan secara otomatis menghapus seluruh basis data dan berkas yang disimpan oleh aplikasi.
- **Permintaan Bantuan**: Jika Anda memiliki pertanyaan atau ingin memastikan penghapusan data, silakan hubungi kami melalui email di `affan@arkananta.id` atau `support@arkananta.id`.

---

### 7. Perubahan pada Kebijakan Privasi

Kami dapat memperbarui Kebijakan Privasi ini dari waktu ke waktu untuk menyesuaikan dengan pengembangan fitur atau regulasi hukum yang berlaku. Setiap perubahan akan diumumkan dengan memperbarui tanggal "Terakhir Diperbarui" di bagian atas dokumen ini. Kami menyarankan pengguna untuk memeriksa halaman ini secara berkala.

---

### 8. Informasi Kontak

Jika Anda memiliki pertanyaan, keluhan, atau masukan mengenai Kebijakan Privasi ini atau pengelolaan data anak di Safari Kid, silakan hubungi tim pengembang kami:

- **Entitas Pengembang:** Arkananta Horizon
- **Email Tim Pengembang:** `affan@arkananta.id` / `support@arkananta.id`
- **Situs Resmi / Repositori Publik:** [https://github.com/ahaffan/safari-kid-privacy](https://github.com/ahaffan/safari-kid-privacy)

---
---

## 🇬🇧 English Version

Welcome to **Safari Kid** ("the Application"), an integrated child growth and anthropometric monitoring platform adhering to the official standards of the World Health Organization (WHO 2006) and the Indonesian Ministry of Health (Permenkes No. 2 Year 2020), combined with a suite of 100% offline child-friendly educational games.

This Privacy Policy explains how **Arkananta Horizon** ("we", "us", or "our") manages, maintains, and protects user information, specifically prioritizing child and family privacy when using Safari Kid. This document is formulated in full compliance with:
1. **Google Play Families Policy**.
2. **Children's Online Privacy Protection Act (COPPA)** (16 C.F.R. Part 312).
3. **Indonesian Personal Data Protection Law (UU PDP No. 27 of 2022)**.
4. **General Data Protection Regulation (GDPR / GDPR-K)** for children's data.

---

### 1. Child Privacy Commitment (Families Policy & COPPA Compliance)
- Safari Kid is designed specifically for children aged **5 and under** as well as parents and caregivers.
- **NO COLLECTION OF PERSONAL IDENTIFIABLE INFORMATION FROM CHILDREN**: We do not knowingly collect, track, or solicit personally identifiable information (such as full names, physical addresses, telephone numbers, or precise geolocation) from children under the age of 13.
- All educational mini-games and interactive features operate without requiring a child account or identity verification.

---

### 2. Information Handled & Storage Methodology

#### a. Child Growth & Anthropometric Data (Stored Locally)
- **Data entered by parents/caregivers**: Child's nickname or initials, date of birth, gender, and physical parameters (weight, length/height, head circumference).
- **Purpose**: Exclusively used to calculate WHO Z-score growth percentiles (WAZ, HAZ, WHZ) and render growth curve trajectories.
- **Storage**: **100% STORED LOCALLY** within the device's sandboxed SQLite/Room database. This data is **NEVER UPLOADED, STORED, OR TRANSMITTED** to Arkananta Horizon servers or any external third-party servers.

#### b. Scrapbook Photographs
- Parents may select photographs to customize their child's scrapbook or app background.
- Safari Kid uses the official **Android Photo Picker** (zero-permission media picker), accessing only the specific images explicitly chosen by the user without requiring broad gallery permissions.
- Photos are stored strictly within the app's sandboxed private storage directory.

#### c. Parental Authentication (Optional)
- If parents choose to authenticate via Google Sign-In or parental email, credentials are handled securely using industry-standard protocols solely to confirm parental access.

---

### 3. Device Permissions

Safari Kid adheres strictly to the principle of Data Minimization:

| Permission | Status | Rationale |
| :--- | :--- | :--- |
| `android.permission.INTERNET` | **Active** | Exclusively used to load curated official parenting education video catalogs from Ministry of Health/WHO and verify app update availability. |
| Geolocation (`ACCESS_FINE_LOCATION`, `ACCESS_COARSE_LOCATION`) | **NOT USED** | We never track user or child locations. |
| Camera (`CAMERA`) | **NOT USED** | Direct hardware camera access is not requested. |
| Microphone (`RECORD_AUDIO`) | **NOT USED** | Musical audio is generated locally via `AudioTrack` synthesizer; no audio recording occurs. |
| Storage Access (`READ_EXTERNAL_STORAGE`, `MANAGE_EXTERNAL_STORAGE`) | **NOT USED** | Media selection is handled via the modern Android Photo Picker. |

---

### 4. Zero Advertising & Zero Behavioral Tracking

- **100% Ad-Free**: Safari Kid contains no banner ads, interstitial pop-ups, or rewarded video advertisements.
- **No Advertising SDKs**: The application does not integrate any third-party ad networks (e.g., AdMob, Unity Ads, AppLovin).
- **No Cross-App Tracking**: We do not collect Google Advertising IDs (AAID) and do not perform behavioral profiling.

---

### 5. Data Security

1. **Encryption in Transit**: All outbound network communication is enforced via **HTTPS / TLS 1.3** through `network_security_config.xml`.
2. **App Sandboxing**: Local growth databases are isolated by Android OS sandboxing rules, preventing unauthorized app access.
3. **Runtime Integrity Verification**: Equipped with `AppSecurityGuard` to verify genuine package signatures and thwart unauthorized tampering.

---

### 6. User Rights & Data Deletion

- **Access & Correction**: Parents can inspect, edit, or update child measurements at any time directly in the app.
- **Instant Data Erasure**:
  - Tapping **"Reset Data"** in the app Settings instantly purges all child records and scrapbook entries.
  - Clearing application data via **Android System Settings > Apps > Safari Kid > Clear Storage** permanently destroys all local databases.
  - Uninstalling Safari Kid automatically deletes all app databases and local cached assets.
- **Data Erasure Assistance**: To request data assistance, contact `affan@arkananta.id` or `support@arkananta.id`.

---

### 7. Changes to this Policy

We may update our Privacy Policy periodically. Any updates will be reflected with a revised "Last Updated" date at the top of this document.

---

### 8. Contact Information

For any inquiries, feedback, or concerns regarding this Privacy Policy or your child's data privacy:

- **Developer:** Arkananta Horizon
- **Email:** `affan@arkananta.id` / `support@arkananta.id`
- **Official Public Repository:** [https://github.com/ahaffan/safari-kid-privacy](https://github.com/ahaffan/safari-kid-privacy)
