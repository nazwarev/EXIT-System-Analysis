
# PRODUCT REQUIREMENTS DOCUMENT (PRD)

# EXIT — Early Investment Take-over

**Versi:** 1.0 — Draft untuk Diskusi Tim  
**Status:** Usulan awal, belum disepakati kelompok  
**Produk:** Platform perantara pengalihan posisi pendanaan  
**Fokus MVP:** P2P Lending dengan data dummy

---

## 1. Latar Belakang

EXIT dikembangkan dari kebutuhan investor untuk memperoleh alternatif pengalihan posisi pendanaan sebelum jatuh tempo. Pada kondisi tertentu, lender dapat membutuhkan likuiditas lebih awal, sedangkan posisi pendanaan yang sedang berjalan belum tentu dapat dicairkan atau dialihkan secara langsung.

EXIT dirancang sebagai platform perantara yang mempertemukan lender yang ingin menawarkan posisi pendanaannya dengan lender lain yang berminat mengambil alih posisi tersebut. Platform menyediakan informasi posisi pendanaan, pemeriksaan kelayakan awal, fasilitas penawaran, pencocokan calon pengambil alih, serta pemantauan status proses.

EXIT tidak bertindak sebagai borrower, tidak membeli seluruh posisi yang ditawarkan, dan tidak menjamin setiap penawaran akan berhasil dialihkan.

## 2. Tujuan Produk

1. Membantu lender menawarkan posisi pendanaan yang ingin dialihkan.
2. Memudahkan lender lain menemukan dan mengevaluasi posisi pendanaan yang tersedia.
3. Meningkatkan transparansi informasi mengenai nilai posisi, sisa tenor, status pembayaran, potensi imbal hasil, dan risiko.
4. Menyediakan proses pengajuan dan pemantauan take-over yang terstruktur.
5. Menjadi prototype inovasi keuangan digital yang dapat diuji menggunakan data dummy.

## 3. Target Pengguna

### A. Selling Lender

Lender yang ingin menawarkan pengalihan posisi pendanaan sebelum jatuh tempo, apabila diperbolehkan oleh ketentuan yang berlaku.

### B. Buying Lender

Lender yang ingin mempertimbangkan pengambilalihan posisi pendanaan yang telah berjalan berdasarkan informasi dan risiko yang tersedia.

### C. Administrator Demo

Pengelola prototype yang dapat melihat data simulasi, memeriksa kelengkapan penawaran, dan membantu pengujian alur aplikasi.

## 4. Value Proposition

- **Bagi Selling Lender:** alternatif untuk menawarkan posisi pendanaan sebelum jatuh tempo.
- **Bagi Buying Lender:** akses untuk menemukan posisi pendanaan yang sudah berjalan.
- **Bagi kedua pihak:** informasi terstruktur, proses pengajuan yang jelas, dan pemantauan status yang transparan.

## 5. Ruang Lingkup MVP

### Fitur Wajib

1. Login demo dan pemilihan peran.
2. Dashboard pengguna.
3. Daftar posisi pendanaan yang ditawarkan.
4. Detail posisi pendanaan dan informasi risiko.
5. Pengajuan penawaran take-over oleh Selling Lender.
6. Pencarian dan filter posisi oleh Buying Lender.
7. Pengajuan minat untuk mengambil alih posisi.
8. Konfirmasi atau penolakan permintaan oleh Selling Lender.
9. Status pengajuan dan riwayat aktivitas.
10. Panel admin sederhana untuk mengelola data dummy dan status demo.

### Fitur Tambahan Jika Waktu Memungkinkan

- Notifikasi perubahan status.
- Simulasi perbandingan harga penawaran dengan sisa pokok.
- Ringkasan statistik aktivitas take-over.
- Pencocokan rekomendasi berdasarkan preferensi tenor dan nilai investasi.

## 6. Di Luar Ruang Lingkup MVP

- Pemindahan uang atau penyelesaian transaksi riil.
- Integrasi dengan API platform P2P eksternal.
- Integrasi rekening bank dan payment gateway.
- Verifikasi identitas resmi atau KYC produksi.
- Algoritma penilaian kredit borrower.
- Jaminan bahwa penawaran akan memperoleh pengambil alih.
- Otomatisasi perpindahan hak investasi tanpa persetujuan pihak terkait.
- Operasional pasar sekunder yang siap melayani masyarakat.

## 7. Alur Utama Produk

1. Pengguna masuk ke aplikasi.
2. Pengguna memilih peran Selling Lender atau Buying Lender.
3. Selling Lender mengisi data posisi pendanaan dan mengajukan penawaran.
4. Sistem menampilkan informasi dan status pemeriksaan awal.
5. Jika memenuhi kriteria simulasi, penawaran muncul pada daftar posisi tersedia.
6. Buying Lender melihat detail, memahami risiko, dan mengajukan minat.
7. Selling Lender meninjau permintaan dan memilih menerima atau menolak.
8. Sistem memperbarui status pengajuan dan menyimpan riwayat.
9. Untuk prototype, status selesai hanya merupakan simulasi, bukan bukti perpindahan hak atau dana secara nyata.

## 8. Kebutuhan Nonfungsional

- Antarmuka mudah dipahami pengguna pemula.
- Data dummy tidak boleh disamarkan sebagai data investasi nyata.
- Pengguna hanya dapat mengakses fungsi sesuai perannya.
- Informasi risiko dan peringatan simulasi ditampilkan dengan jelas.
- Data penting divalidasi sebelum disimpan.
- Status transaksi dan perubahan data tercatat untuk keperluan demo.
- Aplikasi dapat dijalankan dan didemonstrasikan melalui browser.

## 9. Indikator Keberhasilan

- Pengguna dapat masuk dan mengakses dashboard sesuai peran.
- Selling Lender dapat membuat penawaran yang valid.
- Buying Lender dapat mencari posisi dan mengajukan minat.
- Selling Lender dapat menerima atau menolak permintaan.
- Status dan riwayat diperbarui dengan benar.
- QA dapat menyelesaikan pengujian seluruh alur utama.
- Tidak terjadi perpindahan dana riil selama demonstrasi.

## 10. Asumsi dan Risiko

MVP menggunakan data dummy dan berfungsi sebagai demonstrasi mekanisme. Kelayakan pengalihan posisi P2P Lending pada implementasi nyata belum diasumsikan berlaku untuk seluruh platform. Mekanisme harga, persetujuan, penyelesaian, dan integrasi dengan penyelenggara asal harus dikaji sebelum produk dikembangkan lebih lanjut.

## 11. Prioritas Pengembangan

Prioritas pertama adalah alur inti penawaran dan permintaan take-over. Fitur yang tidak diperlukan untuk mendemonstrasikan alur tersebut ditunda sampai MVP utama berfungsi dengan baik.
