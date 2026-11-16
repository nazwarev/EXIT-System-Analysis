# PRODUCT REQUIREMENTS DOCUMENT (PRD)
# EXIT — Early Investment Take-over

**Versi:** 1.1 — Revised Draft  
**Status:** Draft untuk Review dan Persetujuan Tim  
**Produk:** Platform Perantara Pengalihan Posisi Pendanaan  
**Fokus Prototype:** P2P Lending dengan Data Dummy

---

## 1. LATAR BELAKANG

Investasi pada instrumen pendanaan, khususnya Peer-to-Peer (P2P) Lending, memiliki jangka waktu pendanaan tertentu. Dalam kondisi tertentu, lender dapat membutuhkan likuiditas sebelum periode pendanaan berakhir. Namun, posisi pendanaan yang sedang berjalan belum tentu dapat dicairkan atau dialihkan secara langsung.

EXIT (Early Investment Take-over) dikembangkan sebagai konsep platform perantara yang memfasilitasi pengalihan posisi pendanaan dari lender lama kepada lender baru. Platform ini bertujuan mempertemukan lender yang ingin menawarkan posisi pendanaannya dengan calon lender yang berminat mengambil alih posisi tersebut.

EXIT menyediakan fasilitas informasi posisi pendanaan, pengajuan penawaran, pemeriksaan kelayakan awal, pencarian dan pencocokan calon investor, negosiasi, pengajuan permintaan take-over, serta pemantauan status proses pengalihan.

EXIT tidak bertindak sebagai borrower, tidak membeli seluruh posisi yang ditawarkan, dan tidak menjamin setiap penawaran akan memperoleh pengambil alih.

Dalam pengembangan prototype, EXIT menggunakan data dummy untuk menggambarkan mekanisme pengalihan posisi pendanaan tanpa melibatkan transaksi atau perpindahan dana secara nyata.

## 2. TUJUAN PRODUK

Pengembangan EXIT memiliki beberapa tujuan:

1. Membantu lender menawarkan posisi pendanaan yang ingin dialihkan sebelum jatuh tempo.
2. Memudahkan lender lain menemukan dan mengevaluasi posisi pendanaan yang tersedia.
3. Meningkatkan transparansi informasi mengenai nilai posisi, sisa tenor, status pembayaran, potensi imbal hasil, dan risiko.
4. Menyediakan proses pengajuan penawaran dan permintaan take-over yang terstruktur.
5. Memfasilitasi pencocokan antara lender yang menawarkan posisi dan calon lender yang berminat.
6. Menyediakan fasilitas komunikasi dan negosiasi antara lender lama dan lender baru.
7. Memberikan informasi mengenai perkembangan status pengajuan dan riwayat aktivitas pengguna.
8. Mengembangkan prototype inovasi keuangan digital yang dapat diuji menggunakan data simulasi.

## 3. TARGET PENGGUNA

### 3.1 Selling Lender (Lender Lama)

Selling Lender merupakan pengguna yang memiliki posisi pendanaan berjalan dan ingin menawarkan pengalihan posisi tersebut kepada lender lain sebelum jatuh tempo.

Aktivitas utama:
- Melihat dashboard dan aktivitas penawaran.
- Mengajukan posisi pendanaan untuk ditawarkan.
- Memasukkan informasi posisi pendanaan.
- Memeriksa status dan kelayakan pengajuan.
- Mengubah atau membatalkan penawaran sesuai ketentuan status.
- Melihat rekomendasi calon lender.
- Menerima dan meninjau permintaan take-over.
- Melakukan negosiasi dengan calon lender.
- Memantau perkembangan proses pengalihan.

### 3.2 Buying Lender (Lender Baru)

Buying Lender merupakan pengguna yang ingin mencari dan mempertimbangkan pengambilalihan posisi pendanaan yang sedang berjalan berdasarkan informasi dan risiko yang tersedia.

Aktivitas utama:
- Melihat dashboard dan aktivitas investasi.
- Mengeksplorasi posisi pendanaan yang tersedia.
- Melakukan pencarian dan filter posisi.
- Melihat detail informasi posisi pendanaan.
- Melihat informasi risiko dan ketentuan pengalihan.
- Membandingkan beberapa posisi pendanaan.
- Memperoleh rekomendasi posisi berdasarkan kriteria yang tersedia.
- Mengajukan permintaan take-over.
- Melakukan negosiasi dengan Selling Lender.
- Memantau status permintaan dan riwayat aktivitas.

### 3.3 Administrator Demo

Administrator Demo merupakan pengelola prototype yang membantu mengelola data simulasi dan mendukung pengujian aplikasi.

Aktivitas utama:
- Melihat data simulasi.
- Memeriksa kelengkapan penawaran untuk kebutuhan demo.
- Membantu pengelolaan status simulasi.
- Mendukung pengujian dan demonstrasi prototype.

**Catatan:** Kewenangan dan tampilan khusus Administrator Demo masih perlu dirinci dalam pengembangan kebutuhan sistem.

## 4. VALUE PROPOSITION

### 4.1 Bagi Selling Lender
Memberikan alternatif untuk menawarkan posisi pendanaan yang sedang berjalan sebelum jatuh tempo melalui mekanisme pengalihan kepada lender lain.

### 4.2 Bagi Buying Lender
Memberikan akses untuk menemukan dan mengevaluasi posisi pendanaan yang telah berjalan berdasarkan informasi nilai, tenor, status pembayaran, potensi imbal hasil, dan risiko.

### 4.3 Bagi Kedua Pihak
Menyediakan informasi yang lebih terstruktur, proses pengajuan yang jelas, fasilitas pencocokan dan negosiasi, serta pemantauan status proses take-over.

## 5. RUANG LINGKUP PRODUK

Pengembangan prototype EXIT mencakup beberapa kelompok fitur.

### 5.1 Landing Page dan Informasi Platform

Fitur ini ditujukan untuk calon pengguna agar dapat memahami platform EXIT sebelum menggunakan aplikasi.

Cakupan:
- Informasi pengenalan EXIT.
- Penjelasan tujuan dan manfaat platform.
- Penjelasan mekanisme take-over.
- Informasi fitur utama EXIT.
- Frequently Asked Questions (FAQ).
- Identitas visual dan branding platform.

### 5.2 User Authentication

Fitur autentikasi digunakan untuk mengelola akses pengguna ke aplikasi.

Cakupan:
- Registrasi akun.
- Pengisian identitas dasar pengguna.
- Verifikasi OTP sesuai rancangan prototype.
- Login.
- Logout.
- Validasi kredensial.
- Informasi kesalahan apabila login gagal.

### 5.3 Dashboard dan Dual Activity

Dashboard menyajikan ringkasan aktivitas pengguna setelah berhasil masuk ke aplikasi.

Cakupan:
- Overview dashboard.
- My Activity.
- Recent Activity.
- Akses aktivitas sebagai Selling Lender.
- Akses aktivitas sebagai Buying Lender.

Satu akun pengguna dapat mengakses aktivitas penawaran maupun permintaan take-over sesuai kebutuhan pengguna.

### 5.4 Explore Investment

Fitur Explore Investment digunakan oleh Buying Lender untuk menemukan dan mengevaluasi posisi pendanaan yang tersedia.

Cakupan:
- Daftar posisi pendanaan yang tersedia.
- Detail posisi pendanaan.
- Pencarian berdasarkan kata kunci.
- Filter berdasarkan kategori yang tersedia.
- Informasi nilai posisi.
- Informasi tenor dan sisa tenor.
- Informasi status pembayaran.
- Informasi potensi imbal hasil.
- Informasi risiko dan riwayat pembayaran.
- Ketentuan pengalihan posisi.
- Perbandingan beberapa posisi pendanaan.

### 5.5 Offer Position Management

Fitur ini digunakan Selling Lender untuk mengajukan dan mengelola posisi pendanaan yang ingin ditawarkan.

Cakupan:
- Form pengajuan posisi.
- Pengisian informasi posisi pendanaan.
- Validasi kelengkapan informasi.
- Pemeriksaan kelayakan awal.
- Informasi hasil pemeriksaan kelayakan.
- Notifikasi kekurangan informasi.
- Pemantauan status penawaran.
- Perubahan informasi penawaran.
- Pembatalan penawaran sesuai status yang diperbolehkan.

### 5.6 Investor Matching

Fitur matching digunakan untuk membantu mempertemukan Selling Lender dengan calon Buying Lender yang sesuai berdasarkan kriteria yang ditentukan.

Cakupan:
- Pencocokan berdasarkan karakteristik posisi pendanaan.
- Pertimbangan profil risiko calon investor.
- Rekomendasi beberapa calon investor.
- Informasi hasil matching.
- Kondisi ketika tidak ditemukan calon investor yang sesuai.
- Informasi jumlah permintaan yang masuk dan tindak lanjut yang dapat dilakukan Selling Lender.

Matching merupakan fasilitas rekomendasi dan tidak menjamin bahwa setiap penawaran memperoleh calon pengambil alih.

### 5.7 Negotiation dan Take-Over Request

Fitur ini memfasilitasi komunikasi dan pengajuan permintaan pengambilalihan posisi pendanaan.

Cakupan:
- Halaman Negotiations.
- Fasilitas negosiasi antara Selling Lender dan Buying Lender.
- Pengajuan permintaan take-over.
- Penyampaian minat Buying Lender kepada Selling Lender.
- Informasi hasil simulasi berdasarkan input pengguna.
- Informasi status permintaan.

### 5.8 Activity dan Take-Over Tracking

Fitur ini digunakan untuk memantau aktivitas dan perkembangan proses take-over.

Cakupan:
- Activity History.
- Riwayat aktivitas pengguna.
- Status penawaran.
- Status permintaan take-over.
- Pemantauan perkembangan proses.
- Informasi perubahan status.
- Informasi hasil proses pengajuan.

### 5.9 Branding dan Identitas Visual

EXIT memiliki identitas visual yang diterapkan secara konsisten pada seluruh tampilan aplikasi.

Cakupan:
- Logo.
- Warna utama dan pendukung.
- Tipografi.
- Komponen antarmuka.
- Konsistensi identitas visual pada landing page dan aplikasi.

### 5.10 Dokumentasi dan Pengelolaan Proyek

Pengembangan EXIT didukung oleh dokumentasi kebutuhan produk dan repository untuk mengelola source code.

Cakupan:
- Product Requirements Document (PRD).
- User Stories.
- User Flow.
- Wireframe dan mockup.
- Dokumentasi teknis.
- Repository GitHub.
- README dan dokumentasi proyek.

### 5.11 Quality Assurance

Pengujian dilakukan untuk memastikan prototype berjalan sesuai kebutuhan yang telah ditentukan.

Cakupan:
- Penyusunan test plan.
- Penyusunan test cases.
- Pengujian fitur.
- Identifikasi bug.
- Pembuatan bug report.
- Perbaikan source code.
- Pengujian ulang (retesting).
- Penyusunan hasil pengujian.

## 6. RUANG LINGKUP PENGEMBANGAN PROTOTYPE

### 6.1 Fitur Inti

Prioritas utama pengembangan adalah mekanisme pengalihan posisi pendanaan yang mencakup:

1. Registrasi dan login pengguna.
2. Dashboard dan akses aktivitas pengguna.
3. Eksplorasi posisi pendanaan.
4. Pengajuan penawaran oleh Selling Lender.
5. Pemeriksaan kelayakan dan kelengkapan data.
6. Matching antara Selling Lender dan calon Buying Lender.
7. Negosiasi dan pengajuan permintaan take-over.
8. Pemantauan status dan riwayat aktivitas.

### 6.2 Fitur Pendukung

Fitur pendukung untuk melengkapi pengalaman pengguna dan demonstrasi prototype meliputi:

1. Landing page dan informasi pengenalan EXIT.
2. FAQ.
3. Identitas visual dan branding.
4. Perbandingan posisi pendanaan.
5. Informasi kondisi no-match.
6. Notifikasi perubahan status.
7. Pengelolaan data simulasi.
8. Dokumentasi dan pengujian prototype.

### 6.3 Di Luar Ruang Lingkup Prototype

- Pemindahan uang atau penyelesaian transaksi riil.
- Integrasi dengan API platform P2P eksternal.
- Integrasi rekening bank dan payment gateway.
- Verifikasi identitas resmi atau KYC produksi.
- Algoritma penilaian kredit borrower.
- Jaminan bahwa setiap penawaran memperoleh pengambil alih.
- Otomatisasi perpindahan hak investasi tanpa persetujuan pihak terkait.
- Operasional pasar sekunder yang siap melayani masyarakat.

## 7. ALUR UTAMA PRODUK

Secara umum, proses penggunaan EXIT terdiri dari beberapa tahapan berikut.

### 7.1 Akses Platform

1. Calon pengguna membuka landing page EXIT.
2. Pengguna mempelajari informasi platform, cara kerja, dan fitur yang tersedia.
3. Pengguna dapat melakukan registrasi atau login.
4. Pengguna baru mengisi informasi registrasi dan menjalani proses verifikasi sesuai mekanisme prototype.
5. Sistem memvalidasi informasi dan menampilkan hasil proses registrasi.
6. Pengguna yang berhasil masuk diarahkan ke aplikasi.

### 7.2 Dashboard dan Pemilihan Aktivitas

1. Pengguna berhasil login.
2. Sistem menampilkan dashboard.
3. Pengguna dapat melihat ringkasan aktivitas.
4. Pengguna memilih aktivitas sebagai Selling Lender atau Buying Lender sesuai kebutuhannya.

### 7.3 Proses Penawaran Posisi Pendanaan

1. Selling Lender membuka fitur Offer Your Position.
2. Selling Lender memilih untuk membuat penawaran.
3. Sistem menampilkan formulir pengajuan.
4. Selling Lender mengisi informasi posisi pendanaan.
5. Sistem memvalidasi kelengkapan data.
6. Sistem melakukan pemeriksaan kelayakan awal berdasarkan kriteria simulasi.
7. Sistem menampilkan hasil pemeriksaan.
8. Apabila memenuhi kriteria, penawaran dapat dilanjutkan ke proses berikutnya.
9. Apabila terdapat kekurangan atau posisi tidak memenuhi kriteria, sistem menampilkan informasi dan tindak lanjut yang diperlukan.
10. Selling Lender dapat memantau status penawaran.

### 7.4 Proses Eksplorasi dan Matching

1. Buying Lender membuka Explore Investment.
2. Sistem menampilkan daftar posisi pendanaan yang tersedia.
3. Buying Lender dapat melakukan pencarian dan filter.
4. Buying Lender membuka detail posisi pendanaan.
5. Sistem menampilkan informasi nilai, tenor, status pembayaran, potensi imbal hasil, risiko, dan ketentuan pengalihan.
6. Sistem dapat menampilkan rekomendasi berdasarkan kriteria matching.
7. Buying Lender dapat membandingkan beberapa posisi pendanaan.
8. Buying Lender menentukan posisi yang diminati.

### 7.5 Proses Negosiasi dan Permintaan Take-Over

1. Buying Lender memilih posisi pendanaan yang diminati.
2. Buying Lender dapat memasuki proses negosiasi sesuai mekanisme yang disediakan.
3. Buying Lender mengajukan permintaan take-over.
4. Sistem mencatat permintaan dan menampilkan informasi kepada Selling Lender.
5. Selling Lender meninjau permintaan yang masuk.
6. Selling Lender dapat memberikan respons sesuai mekanisme yang ditentukan.
7. Sistem memperbarui informasi status dan riwayat aktivitas.

### 7.6 Proses Monitoring

1. Pengguna membuka halaman Activity.
2. Sistem menampilkan riwayat aktivitas pengguna.
3. Pengguna dapat melihat status penawaran atau permintaan take-over.
4. Sistem memperbarui informasi perkembangan proses.
5. Apabila tidak ditemukan kecocokan, sistem memberikan informasi kondisi no-match dan tindak lanjut yang tersedia.

**Catatan:** Urutan detail negosiasi, persetujuan, penolakan, dan status akhir perlu dirinci dalam dokumen User Flow dan business rules. Status selesai dalam prototype hanya merupakan simulasi, bukan bukti perpindahan dana atau hak investasi secara nyata.

## 8. KEBUTUHAN FUNGSIONAL

Kebutuhan fungsional EXIT dirangkum berdasarkan kelompok fitur berikut:

| Kode | Kelompok Fitur | Kebutuhan |
|---|---|---|
| FR-01 | Landing Page | Menampilkan informasi pengenalan EXIT |
| FR-02 | Platform Information | Menampilkan cara kerja, fitur utama, dan FAQ |
| FR-03 | Authentication | Registrasi, verifikasi OTP, login, logout, dan validasi |
| FR-04 | Dashboard | Menampilkan ringkasan aktivitas pengguna |
| FR-05 | Dual Activity | Mendukung aktivitas Selling Lender dan Buying Lender |
| FR-06 | Explore Investment | Menampilkan daftar posisi pendanaan |
| FR-07 | Search & Filter | Menyediakan pencarian dan filter posisi |
| FR-08 | Position Detail | Menampilkan informasi posisi dan risiko |
| FR-09 | Offer Submission | Memfasilitasi pengajuan penawaran |
| FR-10 | Position Data | Menyediakan input dan validasi informasi posisi |
| FR-11 | Eligibility | Memeriksa kelayakan awal posisi |
| FR-12 | Offer Management | Memfasilitasi monitoring, perubahan, dan pembatalan penawaran |
| FR-13 | Investor Matching | Memberikan rekomendasi calon investor |
| FR-14 | No-Match | Menampilkan informasi ketika matching tidak ditemukan |
| FR-15 | Negotiation | Memfasilitasi negosiasi antara kedua pihak |
| FR-16 | Take-Over Request | Memfasilitasi pengajuan permintaan take-over |
| FR-17 | Comparison | Menyediakan perbandingan beberapa posisi |
| FR-18 | Activity History | Menyimpan dan menampilkan riwayat aktivitas |
| FR-19 | Status Tracking | Memantau status penawaran dan permintaan |
| FR-20 | Demo Administration | Mendukung pengelolaan data dan status simulasi |
| FR-21 | Quality Assurance | Mendukung pengujian dan perbaikan prototype |

## 9. KEBUTUHAN NONFUNGSIONAL

1. **Usability:** Antarmuka mudah dipahami oleh pengguna pemula.
2. **Security:** Informasi akun dan akses pengguna dilindungi sesuai kebutuhan prototype.
3. **Role Access:** Pengguna hanya dapat mengakses fungsi sesuai hak akses yang diberikan.
4. **Data Validation:** Informasi penting divalidasi sebelum disimpan.
5. **Transparency:** Informasi posisi, risiko, dan status proses ditampilkan secara jelas.
6. **Data Integrity:** Perubahan data dan status tercatat secara konsisten.
7. **Prototype Disclosure:** Data dummy tidak boleh disamarkan sebagai data investasi nyata.
8. **Accessibility:** Aplikasi dapat dijalankan dan didemonstrasikan melalui browser.

## 10. INDIKATOR KEBERHASILAN

Prototype EXIT dinyatakan berhasil memenuhi kebutuhan awal apabila:

1. Pengguna dapat mengakses landing page dan memahami informasi dasar EXIT.
2. Pengguna dapat melakukan registrasi dan login sesuai mekanisme prototype.
3. Pengguna dapat mengakses dashboard sesuai aktivitasnya.
4. Pengguna dapat menggunakan fitur Selling Lender dan Buying Lender.
5. Selling Lender dapat mengajukan posisi pendanaan dengan informasi yang diperlukan.
6. Sistem dapat melakukan validasi dan pemeriksaan kelayakan awal.
7. Buying Lender dapat mencari, memfilter, melihat, dan membandingkan posisi pendanaan.
8. Sistem dapat menampilkan rekomendasi matching atau kondisi no-match.
9. Pengguna dapat melakukan negosiasi dan mengajukan permintaan take-over sesuai mekanisme prototype.
10. Selling Lender dapat memberikan respons terhadap permintaan.
11. Pengguna dapat memantau status dan riwayat aktivitas.
12. QA dapat melakukan pengujian dan mengidentifikasi bug pada fitur prototype.
13. Tidak terjadi perpindahan dana riil selama demonstrasi.

## 11. ASUMSI DAN RISIKO

### 11.1 Asumsi

1. Prototype menggunakan data dummy untuk seluruh simulasi posisi pendanaan.
2. Pengguna prototype berperan sebagai Selling Lender atau Buying Lender.
3. Satu akun dapat mengakses kedua jenis aktivitas sesuai rancangan sistem.
4. Informasi nilai, imbal hasil, dan risiko merupakan data simulasi.
5. Pemeriksaan kelayakan merupakan pemeriksaan awal berdasarkan kriteria prototype.
6. Matching merupakan rekomendasi dan bukan jaminan keberhasilan pengalihan.
7. Proses take-over memerlukan persetujuan pihak terkait sesuai ketentuan instrumen dan platform asal.

### 11.2 Risiko

1. Mekanisme pengalihan posisi pendanaan dapat berbeda antarplatform P2P.
2. Tidak semua posisi pendanaan dapat dialihkan sebelum jatuh tempo.
3. Calon Buying Lender belum tentu ditemukan untuk setiap penawaran.
4. Informasi risiko dan histori pembayaran harus tersedia dan dapat dipahami pengguna.
5. Mekanisme harga, persetujuan, dan penyelesaian pengalihan memerlukan kajian lebih lanjut.
6. Perbedaan pemahaman kebutuhan antara System Analyst, UI/UX Designer, Vibe Coder, dan QA dapat menimbulkan ketidaksesuaian implementasi.

## 12. PRIORITAS PENGEMBANGAN

Pengembangan prototype dilakukan secara bertahap dengan mempertimbangkan kebutuhan dan keterkaitan antarfitur.

Prioritas utama adalah memastikan mekanisme inti EXIT dapat didemonstrasikan dari sisi Selling Lender maupun Buying Lender.

Tahapan pengembangan mencakup:

1. **Foundation & User Access:** Persiapan informasi platform, identitas visual, autentikasi, dan dokumentasi proyek.
2. **Investment Dashboard & Exploration:** Pengembangan dashboard, akses aktivitas, dan eksplorasi posisi pendanaan.
3. **Position Submission & Eligibility:** Pengajuan posisi, input informasi, validasi, dan pemeriksaan kelayakan.
4. **Matching, Negotiation & Price Simulation:** Pencocokan investor, informasi risiko, negosiasi, permintaan take-over, dan perbandingan penawaran.
5. **Tracking, History & Finalization:** Pemantauan status, riwayat aktivitas, penanganan no-match, pengujian, dan penyempurnaan prototype.

## 13. PEMETAAN USER STORIES

Dokumentasi kebutuhan produk EXIT mengacu pada 32 User Stories yang telah disusun oleh tim.

| ID | Kebutuhan | Kelompok |
|---|---|---|
| US-01 | Informasi dasar EXIT | Landing Page |
| US-02 | Informasi cara kerja EXIT | Landing Page |
| US-03 | Informasi fitur utama | Landing Page |
| US-04 | FAQ | Landing Page |
| US-05 | Registrasi akun | Authentication |
| US-06 | Login | Authentication |
| US-07 | Logout | Authentication |
| US-08 | Informasi login gagal | Authentication |
| US-09 | Identitas visual platform | Branding |
| US-10 | Dokumentasi kebutuhan produk | Project Documentation |
| US-11 | Repository proyek | Project Documentation |
| US-12 | Dashboard investor | Dashboard |
| US-13 | Daftar posisi investasi | Explore Investment |
| US-14 | Detail posisi investasi | Explore Investment |
| US-15 | Pencarian posisi investasi | Explore Investment |
| US-16 | Filter posisi investasi | Explore Investment |
| US-17 | Akses aktivitas Selling dan Buying Lender | Dual Activity |
| US-18 | Pengajuan posisi investasi | Offer Management |
| US-19 | Input informasi posisi | Offer Management |
| US-20 | Pemeriksaan kelayakan | Eligibility |
| US-21 | Informasi kekurangan data | Data Validation |
| US-22 | Monitoring status penawaran | Offer Management |
| US-23 | Perubahan dan pembatalan penawaran | Offer Management |
| US-24 | Rekomendasi matching investor | Matching |
| US-25 | Informasi risiko dan ketentuan | Position Detail |
| US-26 | Negosiasi harga take-over | Negotiation |
| US-27 | Pengajuan permintaan take-over | Take-Over Request |
| US-28 | Perbandingan penawaran | Comparison |
| US-29 | Riwayat aktivitas | Activity History |
| US-30 | Monitoring status take-over | Tracking |
| US-31 | Informasi kondisi no-match | Matching |
| US-32 | Pengujian dan perbaikan prototype | Quality Assurance |

## 14. BATASAN IMPLEMENTASI

EXIT merupakan prototype inovasi keuangan digital yang berfungsi untuk mendemonstrasikan mekanisme pengalihan posisi pendanaan.

Seluruh penawaran, informasi nilai, imbal hasil, hasil matching, dan status pengajuan dalam prototype menggunakan data simulasi.

EXIT bukan bursa efek, bukan exchange, dan bukan penyelenggara transaksi investasi secara langsung. Platform ini tidak melakukan pemindahan dana atau perpindahan hak investasi secara nyata.

Implementasi nyata harus mempertimbangkan ketentuan instrumen pendanaan, persetujuan pihak terkait, dan kebijakan platform asal sebelum mekanisme pengalihan dapat dilaksanakan.

---

**Dokumen ini menjadi acuan awal bagi System Analyst, UI/UX Designer, Vibe Coder, dan QA dalam mengembangkan prototype EXIT.**

Perubahan kebutuhan, aturan bisnis, dan ruang lingkup produk harus dikomunikasikan dan disepakati bersama tim sebelum diterapkan dalam implementasi.
