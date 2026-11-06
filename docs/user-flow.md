# EXIT — USER FLOW

## 1. Overview

Dokumen ini menjelaskan alur interaksi pengguna dengan platform EXIT (Early Investment Take-over), mulai dari proses registrasi atau login, pemilihan aktivitas, pengajuan penawaran posisi investasi, pencarian posisi investasi, hingga proses permintaan take-over dan pemantauan status aktivitas.

User Flow ini menggambarkan dua alur utama pengguna, yaitu **Selling Lender** sebagai investor yang menawarkan posisi investasi dan **Buying Lender** sebagai calon investor yang ingin mengambil alih posisi investasi.

## 2. User Flow Diagram

Diagram berikut menggambarkan alur penggunaan prototype EXIT beserta proses, keputusan, validasi data, dan kemungkinan hasil dari setiap aktivitas pengguna.

![EXIT User Flow Diagram](../assets/user-flow.png)

## 3. User Flow Description

### 3.1 Registration & Login
- Pengguna mengakses halaman utama EXIT.
- Pengguna melakukan registrasi apabila belum memiliki akun.
- Registrasi mencakup nama lengkap, nomor telepon, email, tanggal lahir, password, dan konfirmasi password.
- Pengguna melakukan verifikasi OTP sesuai mekanisme prototype.
- Pengguna yang telah memiliki akun dapat langsung melakukan login.

### 3.2 Role Selection
Setelah berhasil masuk, pengguna dapat memilih aktivitas berdasarkan kebutuhan:

- **Selling Lender:** Menawarkan posisi investasi yang ingin dialihkan.
- **Buying Lender:** Menelusuri dan mengajukan permintaan take-over terhadap posisi investasi yang tersedia.

Satu akun dapat menggunakan kedua fungsi tersebut.

### 3.3 Selling Lender Flow
- Mengakses dashboard penjual.
- Mengisi informasi posisi investasi.
- Melakukan validasi kelengkapan data.
- Mengajukan penawaran.
- Menjalani pemeriksaan awal.
- Memperoleh status dan alasan apabila penawaran belum memenuhi kriteria.
- Melihat penawaran yang telah memenuhi kriteria demo.

### 3.4 Buying Lender Flow
- Mengakses dashboard calon pengambil alih.
- Menelusuri penawaran melalui pencarian dan filter.
- Melihat detail posisi dan informasi risiko.
- Mengajukan minat take-over.
- Melakukan diskusi atau negosiasi nilai pengalihan.

### 3.5 Take-over Decision & Finalization
- Selling Lender meninjau permintaan take-over.
- Selling Lender memberikan keputusan menerima atau menolak.
- Jika ditolak, sistem menampilkan status penolakan.
- Jika diterima, sistem melanjutkan ke konfirmasi simulasi.
- Sistem menampilkan status selesai dalam konteks demo.

### 3.6 Activity History
Pengguna dapat melihat riwayat aktivitas yang mencakup penawaran, permintaan take-over, proses negosiasi, dan perubahan status aktivitas.

## 4. Flow Constraints

- EXIT memfasilitasi penawaran dan permintaan take-over, bukan menjamin keberhasilan pengalihan.
- Pemeriksaan posisi dalam prototype merupakan pemeriksaan awal kelengkapan data.
- Status selesai merupakan hasil simulasi prototype, bukan bukti transaksi investasi aktual.
- Pengalihan aktual tetap bergantung pada ketentuan instrumen, perjanjian, persetujuan penyelenggara, dan regulasi yang berlaku.
