# UF-02: User Authentication

**Product:** EXIT — Early Investment Take-over  
**Feature:** User Authentication  
**Actor:** Pengguna baru dan pengguna terdaftar  
**Related User Stories:** US-05, US-06, US-07, US-08  
**Access:** Public dan Registered User

## 1. Deskripsi

User Flow ini menjelaskan proses autentikasi pengguna pada platform EXIT, mulai dari registrasi akun, verifikasi OTP, login, penanganan kegagalan login, hingga logout.

Proses ini dirancang agar pengguna baru dapat membuat akun dan pengguna terdaftar dapat mengakses aplikasi menggunakan kredensial yang valid.

## 2. Rincian User Stories

### US-05: Registrasi Pengguna

**User Story:**

Sebagai pengguna baru, saya ingin melakukan registrasi agar dapat memiliki akun EXIT.

**Acceptance Criteria:**
- Form registrasi tersedia dan dapat digunakan.
- Pengguna dapat mengisi nama lengkap, tanggal lahir, nomor telepon, dan email.
- Pengguna dapat membuat password dan mengonfirmasi password.
- Sistem memvalidasi kelengkapan dan format data.
- Sistem menyediakan proses verifikasi OTP.
- Registrasi berhasil apabila data valid dan verifikasi berhasil.

**Rancangan field registrasi:**

| Field | Keterangan |
|---|---|
| Nama lengkap | Nama pengguna |
| Tanggal lahir | Tanggal lahir pengguna |
| Nomor telepon | Nomor telepon aktif |
| Email | Email aktif dan unik |
| Password | Minimal 8 karakter (usulan awal) |
| Konfirmasi password | Harus sesuai dengan password |
| OTP | Kode verifikasi akun |

### US-06: Login Pengguna

**User Story:**

Sebagai pengguna terdaftar, saya ingin login agar dapat mengakses aplikasi EXIT.

**Acceptance Criteria:**
- Halaman login tersedia.
- Pengguna dapat memasukkan email dan password.
- Sistem memvalidasi kredensial pengguna.
- Pengguna dapat masuk apabila kredensial yang dimasukkan valid.
- Sistem mengarahkan pengguna ke halaman aplikasi setelah login berhasil.

### US-07: Logout Pengguna

**User Story:**

Sebagai pengguna, saya ingin logout agar dapat mengakhiri sesi penggunaan dengan aman.

**Acceptance Criteria:**
- Fungsi logout tersedia setelah pengguna berhasil login.
- Pengguna dapat memilih tombol atau menu Logout.
- Sistem mengakhiri sesi pengguna.
- Pengguna diarahkan kembali ke halaman login atau halaman publik.

### US-08: Penanganan Login Gagal

**User Story:**

Sebagai pengguna, saya ingin memperoleh informasi apabila login gagal agar dapat mengetahui penyebabnya.

**Acceptance Criteria:**
- Sistem memvalidasi email dan password yang dimasukkan.
- Sistem menampilkan pesan kesalahan apabila kredensial tidak sesuai.
- Pesan kesalahan ditampilkan dengan jelas.
- Pengguna dapat memperbaiki input dan mencoba login kembali.

## 3. User Flow Diagram



## 4. Output

Hasil dari proses User Authentication meliputi:
- Akun pengguna berhasil dibuat melalui proses registrasi.
- Verifikasi OTP sebagai bagian dari proses registrasi.
- Pengguna terdaftar dapat login menggunakan email dan password.
- Sistem memberikan informasi ketika login gagal.
- Pengguna dapat mengakhiri sesi melalui fitur logout.

## 5. Catatan dan Asumsi

- Registrasi dan login dapat diakses melalui integrasi dari Landing Page EXIT.
- Password dan konfirmasi password merupakan tambahan rancangan untuk kebutuhan autentikasi.
- Ketentuan minimal password 8 karakter merupakan usulan awal yang perlu disepakati tim.
- Kanal pengiriman OTP (email atau nomor telepon) perlu ditentukan pada tahap perancangan teknis.
- Prototype menggunakan data dummy dan proses autentikasi simulasi.
- Pengelolaan sesi dan keamanan autentikasi perlu diperhatikan pada implementasi.

