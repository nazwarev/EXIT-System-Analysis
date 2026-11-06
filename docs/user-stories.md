# EXIT — USER STORIES

## 1. Overview

Dokumen ini berisi User Stories untuk pengembangan prototype EXIT (Early Investment Take-over). User Stories disusun berdasarkan kebutuhan pengguna dan enam fitur utama EXIT, yaitu Early Liquidity, Verifikasi Posisi, Transparansi Informasi, Investor Matching, Price Discovery, dan Fleksibilitas Pengelolaan.

Setiap User Story menjelaskan kebutuhan pengguna dengan format:

- **Sebagai:** Persona atau pihak yang membutuhkan fitur.
- **Saya ingin:** Tindakan atau kebutuhan yang ingin dilakukan.
- **Agar:** Manfaat yang ingin diperoleh.

Setiap User Story dilengkapi dengan prioritas MoSCoW, Sprint, Acceptance Criteria menggunakan format Given–When–Then, serta referensi Business Rules.

## 2. User Stories

# Sprint 1 — Foundation & User Access

### US-01 — Melihat Informasi Dasar EXIT

- **Prioritas:** Must
- **Sprint:** Sprint 1
- **Kategori:** Product Information

**User Story:**

Sebagai calon pengguna, saya ingin memperoleh informasi dasar mengenai EXIT, agar saya dapat memahami tujuan, fungsi, dan layanan yang ditawarkan oleh platform.

**Acceptance Criteria:**

1. **Given** pengguna mengakses halaman utama EXIT, **When** halaman berhasil dimuat, **Then** sistem menampilkan informasi pengenalan EXIT.
2. **Given** pengguna berada pada halaman utama, **When** pengguna membaca informasi produk, **Then** sistem menjelaskan konsep EXIT sebagai platform fasilitasi take-over posisi investasi sebelum jatuh tempo.
3. **Given** pengguna belum memiliki akun, **When** pengguna mengakses informasi EXIT, **Then** informasi produk tetap dapat dilihat tanpa harus login.

**Referensi BR:** Ketentuan penyajian informasi dan identitas produk EXIT.

### US-02 — Melihat Cara Kerja EXIT

- **Prioritas:** Must
- **Sprint:** Sprint 1
- **Kategori:** Product Information

**User Story:**

Sebagai calon pengguna, saya ingin mengetahui tahapan proses kerja EXIT, agar saya memahami bagaimana proses penawaran dan pengambilalihan posisi investasi dilakukan.

**Acceptance Criteria:**

1. **Given** pengguna berada pada halaman informasi EXIT, **When** pengguna memilih bagian cara kerja EXIT, **Then** sistem menampilkan penjelasan tahapan proses take-over.
2. **Given** pengguna melihat tahapan proses, **When** informasi ditampilkan, **Then** sistem menjelaskan proses penawaran posisi, pemeriksaan informasi, pencarian calon investor, negosiasi, dan pemantauan aktivitas.
3. **Given** pengguna membaca penjelasan proses, **When** informasi ditampilkan, **Then** sistem menjelaskan bahwa keberhasilan pengalihan bergantung pada minat dan kesepakatan pihak terkait.

**Referensi BR:** Ketentuan alur proses take-over EXIT.

### US-03 — Melihat Informasi Fitur Utama EXIT

- **Prioritas:** Must
- **Sprint:** Sprint 1
- **Kategori:** Product Information

**User Story:**

Sebagai calon pengguna, saya ingin melihat informasi fitur utama EXIT, agar saya memahami fungsi dan manfaat yang tersedia dalam platform.

**Acceptance Criteria:**

1. **Given** pengguna mengakses bagian fitur utama, **When** halaman fitur dibuka, **Then** sistem menampilkan enam fitur utama EXIT.
2. **Given** daftar fitur ditampilkan, **When** pengguna memilih salah satu fitur, **Then** sistem menampilkan penjelasan mengenai fungsi fitur tersebut.
3. **Given** pengguna membaca informasi fitur, **When** informasi ditampilkan, **Then** penjelasan sesuai dengan fungsi dan batasan produk EXIT.

**Referensi BR:** Ketentuan informasi fitur produk EXIT.

### US-04 — Melihat Frequently Asked Questions (FAQ)

- **Prioritas:** Should
- **Sprint:** Sprint 1
- **Kategori:** Product Information

**User Story:**

Sebagai calon pengguna, saya ingin melihat daftar pertanyaan dan jawaban mengenai EXIT, agar saya dapat memperoleh penjelasan atas hal-hal yang belum saya pahami mengenai platform.

**Acceptance Criteria:**

1. **Given** pengguna mengakses halaman FAQ, **When** halaman berhasil dibuka, **Then** sistem menampilkan daftar pertanyaan yang berkaitan dengan EXIT.
2. **Given** daftar pertanyaan tersedia, **When** pengguna memilih salah satu pertanyaan, **Then** sistem menampilkan jawaban yang sesuai.
3. **Given** pengguna membaca FAQ, **When** informasi ditampilkan, **Then** jawaban menjelaskan layanan dan batasan EXIT secara konsisten.

**Referensi BR:** Ketentuan penyediaan informasi dan edukasi pengguna.

### US-05 — Melakukan Registrasi Akun

- **Prioritas:** Must
- **Sprint:** Sprint 1
- **Kategori:** User Access

**User Story:**

Sebagai calon pengguna, saya ingin melakukan registrasi akun dengan mengisi informasi pribadi yang diperlukan, agar saya dapat memiliki akun dan mengakses fitur EXIT.

**Acceptance Criteria:**

1. **Given** pengguna belum memiliki akun, **When** pengguna memilih menu registrasi, **Then** sistem menampilkan formulir pendaftaran.
2. **Given** formulir registrasi ditampilkan, **When** pengguna mengisi data, **Then** sistem menyediakan kolom nama, tanggal lahir, nomor telepon, dan alamat email.
3. **Given** pengguna mengirimkan formulir registrasi, **When** terdapat data yang belum lengkap atau tidak sesuai format, **Then** sistem menampilkan informasi kesalahan.
4. **Given** data registrasi telah memenuhi validasi, **When** pengguna melanjutkan proses pendaftaran, **Then** sistem menjalankan tahapan verifikasi OTP sesuai mekanisme prototype.
5. **Given** proses registrasi berhasil diselesaikan, **When** sistem menerima hasil verifikasi yang valid, **Then** akun pengguna berhasil dibuat.

**Referensi BR:** Ketentuan registrasi, validasi data, dan verifikasi akun.

### US-06 — Melakukan Login

- **Prioritas:** Must
- **Sprint:** Sprint 1
- **Kategori:** User Access

**User Story:**

Sebagai pengguna yang telah memiliki akun, saya ingin melakukan login menggunakan informasi akun saya, agar saya dapat mengakses dashboard dan fitur EXIT.

**Acceptance Criteria:**

1. **Given** pengguna telah memiliki akun, **When** pengguna membuka halaman login, **Then** sistem menampilkan formulir login.
2. **Given** formulir login tersedia, **When** pengguna memasukkan email dan kata sandi yang benar, **Then** sistem memproses autentikasi pengguna.
3. **Given** autentikasi berhasil, **When** pengguna berhasil login, **Then** sistem mengarahkan pengguna ke halaman dashboard.
4. **Given** pengguna belum mengisi informasi login, **When** pengguna mencoba masuk, **Then** sistem memberikan informasi bahwa data login perlu dilengkapi.

**Referensi BR:** Ketentuan autentikasi dan akses akun pengguna.

### US-07 — Melakukan Logout

- **Prioritas:** Must
- **Sprint:** Sprint 1
- **Kategori:** User Access

**User Story:**

Sebagai pengguna yang sedang login, saya ingin melakukan logout dari akun saya, agar sesi penggunaan dapat diakhiri dengan aman.

**Acceptance Criteria:**

1. **Given** pengguna sedang login, **When** pengguna memilih menu logout, **Then** sistem menjalankan proses pengakhiran sesi.
2. **Given** proses logout berhasil, **When** sesi pengguna berakhir, **Then** sistem mengarahkan pengguna ke halaman login atau halaman utama.
3. **Given** pengguna telah logout, **When** pengguna mencoba mengakses halaman yang membutuhkan autentikasi, **Then** sistem meminta pengguna untuk login kembali.

**Referensi BR:** Ketentuan pengelolaan sesi pengguna.

### US-08 — Mendapatkan Notifikasi Kegagalan Login

- **Prioritas:** Must
- **Sprint:** Sprint 1
- **Kategori:** User Access

**User Story:**

Sebagai pengguna yang mencoba masuk ke akun, saya ingin memperoleh informasi apabila proses login gagal, agar saya mengetahui bahwa informasi autentikasi yang dimasukkan perlu diperiksa kembali.

**Acceptance Criteria:**

1. **Given** pengguna berada pada halaman login, **When** pengguna memasukkan email atau kata sandi yang tidak sesuai, **Then** sistem menampilkan notifikasi kegagalan login.
2. **Given** proses login gagal, **When** notifikasi ditampilkan, **Then** sistem memberikan informasi bahwa pengguna perlu memeriksa kembali data login.
3. **Given** pengguna telah memperbaiki informasi login, **When** pengguna mencoba login kembali dengan data yang benar, **Then** sistem memproses autentikasi ulang.

**Referensi BR:** Ketentuan autentikasi dan penanganan kegagalan login.

### US-09 — Melihat Branding dan Overview EXIT

- **Prioritas:** Should
- **Sprint:** Sprint 1
- **Kategori:** Product Information

**User Story:**

Sebagai calon pengguna, saya ingin melihat tampilan branding dan gambaran umum EXIT, agar saya dapat mengenali identitas platform serta memahami layanan yang ditawarkan.

**Acceptance Criteria:**

1. **Given** pengguna membuka halaman utama EXIT, **When** halaman berhasil dimuat, **Then** sistem menampilkan identitas visual dan nama EXIT.
2. **Given** pengguna berada pada halaman utama, **When** pengguna melihat bagian overview, **Then** sistem menampilkan gambaran umum layanan EXIT.
3. **Given** pengguna mengakses halaman utama melalui perangkat yang berbeda, **When** halaman ditampilkan, **Then** elemen utama tampilan tetap dapat diakses dan dibaca.

**Referensi BR:** Ketentuan identitas visual dan penyajian informasi produk.

### US-10 — Menyusun Dokumentasi Proyek

- **Prioritas:** Must
- **Sprint:** Sprint 1
- **Kategori:** Internal Development

**User Story:**

Sebagai System Analyst, saya ingin menyusun dokumentasi kebutuhan dan analisis sistem EXIT, agar seluruh anggota tim memiliki acuan yang jelas dalam proses pengembangan prototype.

**Acceptance Criteria:**

1. **Given** kebutuhan produk telah diidentifikasi, **When** System Analyst menyusun dokumentasi, **Then** dokumentasi mencakup kebutuhan produk dan analisis sistem yang relevan.
2. **Given** dokumentasi telah disusun, **When** dokumentasi ditinjau, **Then** isi dokumen diperiksa kesesuaiannya dengan ruang lingkup EXIT.
3. **Given** dokumentasi telah diperbarui, **When** hasil perubahan disimpan, **Then** versi dokumentasi terbaru dapat diakses oleh anggota tim.

**Referensi BR:** Tidak berlaku sebagai fitur pengguna. Mengacu pada standar dan kebutuhan dokumentasi internal proyek.

### US-11 — Mengelola Repository Proyek

- **Prioritas:** Must
- **Sprint:** Sprint 1
- **Kategori:** Internal Development

**User Story:**

Sebagai anggota tim pengembang, saya ingin menyimpan dan mengelola dokumentasi serta file proyek pada repository, agar seluruh anggota tim dapat mengakses dan menggunakan sumber pengembangan yang terorganisasi.

**Acceptance Criteria:**

1. **Given** repository proyek telah tersedia, **When** anggota tim mengakses repository, **Then** anggota tim dapat melihat struktur file sesuai hak aksesnya.
2. **Given** terdapat dokumentasi atau perubahan file proyek, **When** anggota tim melakukan commit, **Then** perubahan tersimpan pada repository.
3. **Given** terdapat pembaruan dokumen, **When** anggota tim membuka repository, **Then** versi dokumen terbaru dapat diakses.

**Referensi BR:** Tidak berlaku sebagai fitur pengguna. Mengacu pada tata kelola repository internal proyek.

---

# Sprint 2 — Investment Dashboard & Exploration

### US-12 — Melihat Dashboard Investasi

- **Prioritas:** Must
- **Sprint:** Sprint 2
- **Kategori:** Fleksibilitas Pengelolaan

**User Story:**

Sebagai pengguna EXIT, saya ingin melihat dashboard yang menampilkan ringkasan aktivitas investasi dan take-over saya, agar saya dapat mengetahui gambaran umum aktivitas yang sedang berlangsung.

**Acceptance Criteria:**

1. **Given** pengguna telah login, **When** pengguna membuka dashboard, **Then** sistem menampilkan halaman dashboard pengguna.
2. **Given** dashboard berhasil dimuat, **When** pengguna melihat bagian My Activity, **Then** sistem menampilkan ringkasan aktivitas pengguna.
3. **Given** terdapat aktivitas terbaru, **When** pengguna melihat bagian Recent Activity, **Then** sistem menampilkan informasi aktivitas terbaru yang relevan.
4. **Given** pengguna belum memiliki aktivitas, **When** dashboard ditampilkan, **Then** sistem menampilkan kondisi belum terdapat aktivitas.

**Referensi BR:** Ketentuan penyajian ringkasan aktivitas pengguna.

### US-13 — Mengeksplorasi Posisi Investasi

- **Prioritas:** Must
- **Sprint:** Sprint 2
- **Kategori:** Investor Matching

**User Story:**

Sebagai calon investor yang berminat mengambil alih posisi investasi, saya ingin mengeksplorasi daftar posisi investasi yang tersedia, agar saya dapat menemukan penawaran yang sesuai dengan kebutuhan saya.

**Acceptance Criteria:**

1. **Given** pengguna telah login, **When** pengguna membuka halaman Explore Investment, **Then** sistem menampilkan daftar posisi investasi yang tersedia.
2. **Given** terdapat beberapa penawaran, **When** pengguna melihat daftar posisi, **Then** sistem menampilkan informasi ringkas dari setiap penawaran.
3. **Given** pengguna memilih salah satu penawaran, **When** pengguna membuka detailnya, **Then** sistem menampilkan informasi lengkap posisi investasi.
4. **Given** belum terdapat penawaran yang tersedia, **When** pengguna membuka halaman Explore Investment, **Then** sistem menampilkan informasi bahwa belum terdapat posisi investasi yang tersedia.

**Referensi BR:** Ketentuan penayangan dan eksplorasi penawaran posisi investasi.

### US-14 — Melihat Detail Informasi Posisi Investasi

- **Prioritas:** Must
- **Sprint:** Sprint 2
- **Kategori:** Transparansi Informasi

**User Story:**

Sebagai calon investor, saya ingin melihat detail informasi posisi investasi yang ditawarkan, agar saya dapat memahami karakteristik, potensi imbal hasil, dan risiko posisi sebelum mempertimbangkan take-over.

**Acceptance Criteria:**

1. **Given** pengguna telah membuka daftar penawaran, **When** pengguna memilih salah satu posisi investasi, **Then** sistem menampilkan halaman detail posisi.
2. **Given** halaman detail posisi dibuka, **When** sistem menampilkan informasi penawaran, **Then** informasi mencakup nilai posisi dan sisa tenor.
3. **Given** informasi posisi tersedia, **When** pengguna melihat detail penawaran, **Then** sistem menampilkan status pembayaran dan potensi imbal hasil indikatif.
4. **Given** informasi risiko dan ketentuan pengalihan tersedia, **When** pengguna membuka detail posisi, **Then** sistem menampilkan informasi tersebut sebagai bahan pertimbangan.
5. **Given** terdapat informasi yang tidak tersedia, **When** detail posisi ditampilkan, **Then** sistem tidak menampilkan informasi yang tidak didukung oleh data penawaran.

**Referensi BR:** Ketentuan transparansi informasi posisi investasi.

### US-15 — Mencari Posisi Investasi

- **Prioritas:** Should
- **Sprint:** Sprint 2
- **Kategori:** Investor Matching

**User Story:**

Sebagai calon investor, saya ingin mencari posisi investasi menggunakan kata kunci, agar saya dapat menemukan penawaran berdasarkan instrumen atau platform yang saya minati.

**Acceptance Criteria:**

1. **Given** pengguna berada pada halaman Explore Investment, **When** pengguna menggunakan kolom pencarian, **Then** sistem menyediakan input kata kunci.
2. **Given** pengguna memasukkan kata kunci instrumen atau platform, **When** pencarian dijalankan, **Then** sistem menampilkan penawaran yang sesuai dengan kata kunci.
3. **Given** tidak terdapat penawaran yang sesuai, **When** pencarian selesai, **Then** sistem menampilkan informasi bahwa hasil pencarian tidak ditemukan.
4. **Given** pengguna menghapus kata kunci pencarian, **When** daftar diperbarui, **Then** sistem menampilkan kembali daftar penawaran yang tersedia.

**Referensi BR:** Ketentuan pencarian penawaran berdasarkan informasi instrumen atau platform.

### US-16 — Memfilter Posisi Investasi Berdasarkan Kategori

- **Prioritas:** Should
- **Sprint:** Sprint 2
- **Kategori:** Investor Matching

**User Story:**

Sebagai calon investor, saya ingin memfilter daftar posisi investasi berdasarkan kategori instrumen, agar saya dapat mempersempit pilihan penawaran sesuai dengan jenis investasi yang diminati.

**Acceptance Criteria:**

1. **Given** pengguna membuka halaman Explore Investment, **When** pengguna mengakses fitur filter, **Then** sistem menampilkan pilihan kategori instrumen.
2. **Given** pilihan kategori tersedia, **When** pengguna memilih kategori tertentu, **Then** sistem menampilkan penawaran yang termasuk dalam kategori tersebut.
3. **Given** pengguna memilih kategori All Instruments, **When** filter diterapkan, **Then** sistem menampilkan seluruh penawaran yang tersedia.
4. **Given** tidak terdapat penawaran pada kategori tertentu, **When** kategori dipilih, **Then** sistem menampilkan informasi bahwa tidak terdapat penawaran yang sesuai.

**Referensi BR:** Ketentuan pengelompokan dan filter instrumen investasi.

### US-17 — Mengakses Fungsi Penawaran dan Permintaan Take-over dalam Satu Akun

- **Prioritas:** Must
- **Sprint:** Sprint 2
- **Kategori:** Fleksibilitas Pengelolaan

**User Story:**

Sebagai pengguna EXIT, saya ingin dapat mengakses fungsi penawaran posisi investasi dan permintaan take-over menggunakan satu akun, agar saya dapat menjalankan kedua aktivitas sesuai kebutuhan tanpa harus memiliki akun yang berbeda.

**Acceptance Criteria:**

1. **Given** pengguna telah login, **When** pengguna mengakses dashboard atau navigasi utama, **Then** sistem menyediakan akses ke fungsi penawaran dan permintaan take-over.
2. **Given** pengguna ingin menawarkan posisi investasi, **When** pengguna memilih menu Offer Your Position, **Then** sistem mengarahkan pengguna ke halaman pengajuan penawaran.
3. **Given** pengguna ingin mengambil alih posisi investasi, **When** pengguna mengakses halaman Explore Investment, **Then** sistem memungkinkan pengguna menelusuri dan mengajukan permintaan take-over.
4. **Given** pengguna telah menggunakan salah satu fungsi, **When** pengguna ingin menggunakan fungsi lainnya, **Then** sistem tetap memungkinkan akses menggunakan akun yang sama.

**Referensi BR:** Ketentuan satu akun untuk fungsi penawaran dan permintaan take-over.

---

# Sprint 3 — Position Submission & Eligibility

### US-18 — Mengajukan Penawaran Posisi Investasi

- **Prioritas:** Must
- **Sprint:** Sprint 3
- **Kategori:** Early Liquidity

**User Story:**

Sebagai investor yang memiliki posisi investasi berjalan, saya ingin mengajukan penawaran posisi investasi melalui EXIT, agar saya memiliki alternatif untuk mengalihkan posisi sebelum jatuh tempo kepada calon investor yang berminat.

**Acceptance Criteria:**

1. **Given** pengguna telah login, **When** pengguna memilih menu Offer Your Position, **Then** sistem menampilkan halaman pengajuan penawaran.
2. **Given** pengguna berada pada halaman pengajuan, **When** pengguna memulai penawaran, **Then** sistem menyediakan proses pengisian informasi posisi investasi.
3. **Given** pengguna telah melengkapi informasi yang diperlukan, **When** pengguna mengirimkan pengajuan, **Then** sistem menerima data penawaran untuk diproses.
4. **Given** pengajuan berhasil dikirim, **When** sistem menyimpan pengajuan, **Then** sistem memberikan informasi bahwa penawaran telah diterima untuk pemeriksaan awal.

**Referensi BR:** Ketentuan penawaran posisi investasi sebelum jatuh tempo.

### US-19 — Mengisi Informasi Posisi Investasi

- **Prioritas:** Must
- **Sprint:** Sprint 3
- **Kategori:** Verifikasi Posisi

**User Story:**

Sebagai investor yang ingin menawarkan posisi investasi, saya ingin mengisi informasi posisi investasi secara lengkap, agar data penawaran dapat diperiksa dan dipahami oleh calon investor.

**Acceptance Criteria:**

1. **Given** pengguna berada pada formulir pengajuan penawaran, **When** pengguna mengisi data posisi investasi, **Then** sistem menyediakan kolom informasi yang diperlukan.
2. **Given** pengguna mengisi informasi posisi, **When** data dimasukkan, **Then** sistem menerima informasi nilai posisi investasi.
3. **Given** pengguna mengisi informasi posisi, **When** data dimasukkan, **Then** sistem menyediakan informasi sisa tenor dan status pembayaran.
4. **Given** pengguna belum melengkapi data wajib, **When** pengguna mencoba melanjutkan pengajuan, **Then** sistem memberikan informasi mengenai data yang belum lengkap.
5. **Given** seluruh data wajib telah diisi, **When** pengguna melanjutkan proses, **Then** sistem memungkinkan pengajuan untuk dikirimkan.

**Referensi BR:** Ketentuan kelengkapan data posisi investasi.

### US-20 — Mengirimkan Penawaran untuk Pemeriksaan

- **Prioritas:** Must
- **Sprint:** Sprint 3
- **Kategori:** Early Liquidity, Verifikasi Posisi

**User Story:**

Sebagai investor yang telah mengisi informasi posisi investasi, saya ingin mengirimkan penawaran untuk menjalani pemeriksaan awal, agar saya mengetahui apakah data posisi investasi telah memenuhi kelengkapan informasi yang diperlukan.

**Acceptance Criteria:**

1. **Given** pengguna telah melengkapi informasi posisi investasi, **When** pengguna memilih tombol pengiriman penawaran, **Then** sistem memproses pengajuan.
2. **Given** pengajuan berhasil dikirim, **When** sistem menyimpan data pengajuan, **Then** sistem mengubah status pengajuan menjadi Menunggu Pemeriksaan.
3. **Given** pengajuan telah dikirim, **When** pengguna melihat informasi pengajuan, **Then** sistem menampilkan informasi bahwa posisi sedang menunggu pemeriksaan.
4. **Given** terdapat data wajib yang belum lengkap, **When** pengguna mencoba mengirimkan penawaran, **Then** sistem memberikan informasi mengenai kekurangan data tersebut.

**Referensi BR:** Ketentuan pengiriman pengajuan dan status pemeriksaan posisi.

### US-21 — Mengetahui Hasil Pemeriksaan Kelayakan Posisi

- **Prioritas:** Must
- **Sprint:** Sprint 3
- **Kategori:** Verifikasi Posisi

**User Story:**

Sebagai investor yang telah mengajukan posisi investasi, saya ingin mengetahui hasil pemeriksaan awal terhadap kelengkapan data posisi, agar saya dapat mengetahui apakah pengajuan dapat dilanjutkan atau masih memerlukan perbaikan informasi.

**Acceptance Criteria:**

1. **Given** pengajuan telah dikirimkan, **When** pemeriksaan awal selesai dilakukan, **Then** sistem menampilkan hasil pemeriksaan.
2. **Given** informasi posisi telah memenuhi kelengkapan data yang diperlukan, **When** pemeriksaan selesai, **Then** sistem menampilkan status Layak.
3. **Given** informasi posisi belum memenuhi kelengkapan data, **When** pemeriksaan selesai, **Then** sistem menampilkan status Tidak Layak.
4. **Given** hasil pemeriksaan menunjukkan Tidak Layak, **When** pengguna melihat detail hasil pemeriksaan, **Then** sistem menampilkan informasi mengenai data yang masih perlu dilengkapi.
5. **Given** hasil pemeriksaan telah tersedia, **When** pengguna membuka detail pengajuan, **Then** pengguna dapat melihat hasil pemeriksaan tersebut.

**Referensi BR:** Ketentuan pemeriksaan awal kelengkapan informasi posisi.

### US-22 — Memantau Status Pengajuan Posisi

- **Prioritas:** Must
- **Sprint:** Sprint 3
- **Kategori:** Fleksibilitas Pengelolaan

**User Story:**

Sebagai investor yang telah mengajukan penawaran posisi investasi, saya ingin melihat status pengajuan melalui halaman Activity, agar saya dapat mengetahui perkembangan proses pemeriksaan penawaran saya.

**Acceptance Criteria:**

1. **Given** pengguna telah mengajukan penawaran, **When** pengguna membuka halaman Activity, **Then** sistem menampilkan daftar pengajuan milik pengguna.
2. **Given** pengajuan masih dalam proses pemeriksaan, **When** pengguna melihat daftar aktivitas, **Then** sistem menampilkan status Menunggu Pemeriksaan.
3. **Given** pemeriksaan telah selesai, **When** pengguna membuka daftar aktivitas, **Then** sistem menampilkan status hasil pemeriksaan sesuai hasil yang tersedia.
4. **Given** pengguna memilih salah satu pengajuan, **When** detail aktivitas dibuka, **Then** sistem menampilkan informasi posisi dan status pengajuan.

**Referensi BR:** Ketentuan pemantauan status pengajuan.

### US-23 — Mengedit atau Membatalkan Penawaran Posisi

- **Prioritas:** Should
- **Sprint:** Sprint 3
- **Kategori:** Early Liquidity, Fleksibilitas Pengelolaan

**User Story:**

Sebagai investor yang telah mengajukan penawaran posisi investasi, saya ingin mengelola penawaran saya, termasuk melakukan perubahan informasi atau membatalkan penawaran sesuai ketentuan sistem, agar saya dapat menyesuaikan penawaran dengan kondisi posisi investasi saya.

**Acceptance Criteria:**

1. **Given** pengguna memiliki penawaran yang telah diajukan, **When** pengguna membuka detail penawaran, **Then** sistem menampilkan informasi penawaran miliknya.
2. **Given** penawaran berada pada status yang memungkinkan perubahan, **When** pengguna memilih fungsi edit, **Then** sistem menyediakan akses untuk memperbarui informasi sesuai ketentuan yang berlaku.
3. **Given** pengguna ingin membatalkan penawaran, **When** pengguna memilih fungsi pembatalan, **Then** sistem meminta konfirmasi pembatalan.
4. **Given** pengguna mengonfirmasi pembatalan, **When** sistem memproses tindakan tersebut, **Then** status penawaran diperbarui sesuai alur sistem.
5. **Given** penawaran tidak berada pada status yang memungkinkan perubahan atau pembatalan, **When** pengguna mencoba melakukan tindakan tersebut, **Then** sistem tidak mengizinkan tindakan yang tidak sesuai.

**Referensi BR:** Ketentuan perubahan dan pembatalan penawaran. Perlu dikonfirmasi kembali sesuai keputusan tim.

---

# Sprint 4 — Matching, Negotiation & Price Simulation

### US-24 — Memperoleh Rekomendasi Matching Investor

- **Prioritas:** Must
- **Sprint:** Sprint 4
- **Kategori:** Investor Matching

**User Story:**

Sebagai calon investor yang ingin mengambil alih posisi investasi, saya ingin memperoleh rekomendasi penawaran berdasarkan karakteristik posisi dan profil risiko saya, agar saya dapat menemukan posisi investasi yang sesuai dengan kebutuhan dan kemampuan saya.

**Acceptance Criteria:**

1. **Given** pengguna telah login, **When** pengguna mengakses fitur matching, **Then** sistem memeriksa ketersediaan informasi profil pengguna.
2. **Given** pengguna belum melengkapi profil, **When** pengguna memulai proses matching, **Then** sistem mengarahkan pengguna untuk melengkapi profil terlebih dahulu.
3. **Given** profil pengguna telah dilengkapi, **When** pengguna melanjutkan proses, **Then** sistem memungkinkan pengguna mengisi atau melengkapi profil risiko.
4. **Given** profil dan profil risiko telah tersedia, **When** proses matching dijalankan, **Then** sistem menampilkan rekomendasi posisi berdasarkan karakteristik penawaran dan informasi profil pengguna.
5. **Given** tidak terdapat posisi yang sesuai, **When** proses matching selesai, **Then** sistem menampilkan informasi bahwa belum terdapat rekomendasi yang sesuai.

**Referensi BR:** Ketentuan matching berdasarkan karakteristik posisi dan profil calon investor.

### US-25 — Melihat Informasi Risiko dan Ketentuan Take-over

- **Prioritas:** Must
- **Sprint:** Sprint 4
- **Kategori:** Transparansi Informasi, Investor Matching

**User Story:**

Sebagai calon investor yang tertarik pada suatu penawaran, saya ingin melihat informasi risiko, riwayat pembayaran, nilai pengalihan, sisa tenor, dan ketentuan take-over, agar saya dapat mempertimbangkan risiko serta kewajiban yang berkaitan dengan posisi investasi tersebut.

**Acceptance Criteria:**

1. **Given** pengguna membuka detail penawaran, **When** informasi posisi ditampilkan, **Then** sistem menampilkan informasi risiko yang tersedia.
2. **Given** informasi riwayat pembayaran tersedia, **When** pengguna melihat detail posisi, **Then** sistem menampilkan informasi riwayat pembayaran.
3. **Given** informasi nilai pengalihan dan sisa tenor tersedia, **When** pengguna membuka detail penawaran, **Then** sistem menampilkan informasi tersebut.
4. **Given** terdapat ketentuan pengalihan posisi, **When** pengguna melihat detail penawaran, **Then** sistem menampilkan ketentuan yang perlu diperhatikan sebelum mengajukan take-over.
5. **Given** terdapat informasi yang belum tersedia, **When** detail penawaran ditampilkan, **Then** sistem tidak menampilkan data yang tidak didukung oleh informasi penawaran.

**Referensi BR:** Ketentuan transparansi informasi, risiko, dan pengalihan posisi investasi.

### US-26 — Melakukan Negosiasi Nilai Take-over

- **Prioritas:** Must
- **Sprint:** Sprint 4
- **Kategori:** Price Discovery

**User Story:**

Sebagai investor yang menawarkan posisi maupun calon investor yang ingin mengambil alih, saya ingin melakukan negosiasi nilai pengalihan, agar kedua pihak dapat membahas dan mencapai kesepakatan nilai take-over berdasarkan informasi posisi investasi.

**Acceptance Criteria:**

1. **Given** terdapat penawaran yang diminati calon investor, **When** proses negosiasi dimulai, **Then** sistem menyediakan akses ke bagian Negotiations.
2. **Given** pihak terkait telah memasuki bagian Negotiations, **When** proses pembahasan dilakukan, **Then** sistem menyediakan sarana untuk menyampaikan pembahasan nilai pengalihan sesuai fungsi prototype.
3. **Given** terdapat tanggapan atau perubahan nilai dalam proses negosiasi, **When** informasi diperbarui, **Then** sistem menampilkan perkembangan negosiasi kepada pihak terkait.
4. **Given** kedua pihak telah mencapai kesepakatan, **When** hasil kesepakatan dicatat, **Then** sistem menampilkan informasi kesepakatan sesuai alur prototype.

**Referensi BR:** Ketentuan negosiasi dan kesepakatan nilai pengalihan.

### US-27 — Mengajukan Permintaan Take-over

- **Prioritas:** Must
- **Sprint:** Sprint 4
- **Kategori:** Investor Matching, Price Discovery

**User Story:**

Sebagai calon investor yang tertarik pada posisi investasi yang ditawarkan, saya ingin mengajukan permintaan take-over melalui halaman detail penawaran, agar investor yang menawarkan posisi dapat mengetahui ketertarikan saya terhadap posisi tersebut.

**Acceptance Criteria:**

1. **Given** pengguna telah memilih posisi investasi yang tersedia, **When** pengguna membuka halaman detail penawaran, **Then** sistem menampilkan informasi dan opsi pengajuan take-over.
2. **Given** pengguna tertarik untuk mengambil alih posisi, **When** pengguna memilih opsi pengajuan take-over, **Then** sistem memproses permintaan pengguna.
3. **Given** permintaan berhasil diajukan, **When** sistem menyimpan data permintaan, **Then** sistem menampilkan konfirmasi bahwa permintaan take-over telah dikirim.
4. **Given** permintaan telah dikirim, **When** investor yang menawarkan posisi melihat aktivitasnya, **Then** sistem menyediakan informasi permintaan yang diterima.
5. **Given** pengguna belum memenuhi persyaratan pengajuan yang ditetapkan, **When** pengguna mencoba mengirimkan permintaan, **Then** sistem memberikan informasi mengenai persyaratan yang belum terpenuhi.

**Referensi BR:** Ketentuan pengajuan permintaan take-over dan respons terhadap penawaran.

### US-28 — Membandingkan Beberapa Penawaran Matching

- **Prioritas:** Should
- **Sprint:** Sprint 4
- **Kategori:** Investor Matching, Price Discovery, Transparansi Informasi

**User Story:**

Sebagai calon investor, saya ingin membandingkan beberapa penawaran posisi investasi yang sesuai, agar saya dapat mengevaluasi perbedaan karakteristik dan nilai masing-masing penawaran sebelum mengajukan take-over.

**Acceptance Criteria:**

1. **Given** terdapat beberapa penawaran yang sesuai dengan kebutuhan pengguna, **When** pengguna mengakses hasil matching, **Then** sistem menampilkan daftar penawaran yang dapat dipertimbangkan.
2. **Given** pengguna memilih beberapa penawaran, **When** pengguna menjalankan fungsi perbandingan, **Then** sistem menampilkan informasi masing-masing penawaran secara berdampingan atau dalam ringkasan perbandingan.
3. **Given** informasi penawaran tersedia, **When** perbandingan ditampilkan, **Then** sistem menyajikan informasi relevan seperti nilai posisi, sisa tenor, potensi imbal hasil indikatif, status pembayaran, dan risiko.
4. **Given** pengguna selesai membandingkan penawaran, **When** pengguna memilih salah satu penawaran, **Then** sistem mengarahkan pengguna ke detail penawaran yang dipilih.

**Referensi BR:** Ketentuan penyajian dan perbandingan informasi penawaran.

---

# Sprint 5 — Tracking, History & Finalization

### US-29 — Melihat Riwayat Aktivitas

- **Prioritas:** Must
- **Sprint:** Sprint 5
- **Kategori:** Fleksibilitas Pengelolaan

**User Story:**

Sebagai pengguna EXIT, saya ingin melihat riwayat aktivitas penawaran dan permintaan take-over yang pernah saya lakukan, agar saya dapat meninjau kembali perkembangan aktivitas investasi saya.

**Acceptance Criteria:**

1. **Given** pengguna telah login, **When** pengguna membuka halaman Activity, **Then** sistem menampilkan riwayat aktivitas pengguna.
2. **Given** pengguna pernah mengajukan penawaran posisi, **When** pengguna melihat riwayat aktivitas, **Then** sistem menampilkan informasi penawaran tersebut.
3. **Given** pengguna pernah mengajukan permintaan take-over, **When** pengguna melihat riwayat aktivitas, **Then** sistem menampilkan informasi permintaan tersebut.
4. **Given** pengguna belum memiliki riwayat aktivitas, **When** halaman Activity dibuka, **Then** sistem menampilkan informasi bahwa belum terdapat aktivitas.

**Referensi BR:** Ketentuan penyimpanan dan penyajian riwayat aktivitas.

### US-30 — Melacak Status Aktivitas

- **Prioritas:** Must
- **Sprint:** Sprint 5
- **Kategori:** Fleksibilitas Pengelolaan

**User Story:**

Sebagai pengguna EXIT, saya ingin memantau status aktivitas penawaran dan permintaan take-over melalui halaman Activity, agar saya dapat mengetahui perkembangan setiap proses yang sedang berlangsung.

**Acceptance Criteria:**

1. **Given** pengguna memiliki aktivitas penawaran atau permintaan take-over, **When** pengguna membuka halaman Activity, **Then** sistem menampilkan daftar aktivitas berdasarkan kategori yang tersedia.
2. **Given** pengguna membuka kategori All, **When** daftar aktivitas ditampilkan, **Then** sistem menampilkan seluruh aktivitas pengguna.
3. **Given** suatu aktivitas mengalami perubahan status, **When** pengguna melihat kembali aktivitas tersebut, **Then** sistem menampilkan status terbaru sesuai data yang tersedia.
4. **Given** pengguna memilih salah satu aktivitas, **When** detail aktivitas dibuka, **Then** sistem menampilkan informasi proses dan status aktivitas tersebut.

**Referensi BR:** Ketentuan pemantauan dan pembaruan status aktivitas.

### US-31 — Mendapatkan Informasi Ketika Tidak Terdapat Matching

- **Prioritas:** Must
- **Sprint:** Sprint 5
- **Kategori:** Investor Matching, Fleksibilitas Pengelolaan

**User Story:**

Sebagai investor yang menawarkan posisi investasi, saya ingin memperoleh informasi apabila tidak terdapat kecocokan matching terhadap penawaran saya, agar saya mengetahui kondisi penawaran dan respons calon investor terhadap posisi tersebut.

**Acceptance Criteria:**

1. **Given** investor telah menawarkan posisi investasi, **When** sistem tidak menemukan kecocokan matching, **Then** sistem menampilkan informasi bahwa belum terdapat calon investor yang sesuai.
2. **Given** tidak terdapat kecocokan matching, **When** investor membuka detail penawaran pada halaman My Offers, **Then** sistem menampilkan informasi kondisi matching.
3. **Given** terdapat permintaan yang masuk terhadap penawaran, **When** investor melihat detail penawaran, **Then** sistem menampilkan jumlah permintaan yang diterima sesuai data yang tersedia.
4. **Given** belum terdapat permintaan take-over, **When** investor melihat detail penawaran, **Then** sistem menampilkan informasi bahwa belum terdapat permintaan yang diterima.
5. **Given** kondisi matching belum menghasilkan calon investor, **When** informasi penawaran ditampilkan, **Then** sistem memberikan informasi perkembangan penawaran tanpa menjanjikan bahwa matching akan berhasil.

**Referensi BR:** Ketentuan matching dan penyajian informasi respons terhadap penawaran.

### US-32 — Melakukan Pengujian dan Perbaikan Prototype

- **Prioritas:** Must
- **Sprint:** Sprint 5
- **Kategori:** Internal Development / Quality Assurance

**User Story:**

Sebagai tim pengembang, saya ingin melakukan pengujian dan perbaikan prototype EXIT, agar aplikasi dapat berjalan sesuai kebutuhan dan fungsi yang telah ditentukan.

**Acceptance Criteria:**

1. **Given** fitur prototype telah dikembangkan, **When** tim QA melakukan pengujian, **Then** setiap fitur diuji berdasarkan kebutuhan dan Acceptance Criteria yang telah ditetapkan.
2. **Given** ditemukan kesalahan atau bug, **When** hasil pengujian didokumentasikan, **Then** tim memiliki catatan mengenai masalah yang ditemukan.
3. **Given** bug telah dilaporkan, **When** tim pengembang melakukan perbaikan, **Then** perubahan dilakukan sesuai hasil temuan pengujian.
4. **Given** perbaikan telah dilakukan, **When** pengujian ulang dilaksanakan, **Then** tim QA memeriksa kembali fungsi yang sebelumnya bermasalah.
5. **Given** seluruh pengujian yang direncanakan telah dilakukan, **When** hasil pengujian dirangkum, **Then** tim memiliki dokumentasi hasil pengujian prototype.

**Referensi BR:** Tidak berlaku sebagai fitur pengguna. Mengacu pada kebutuhan pengujian dan kualitas prototype.

---

## 3. Feature Mapping

Pemetaan berikut menunjukkan hubungan antara enam fitur utama EXIT dengan User Stories yang mendukung implementasinya.

| Feature ID | Main Feature | Related User Stories |
|---|---|---|
| F-01 | Early Liquidity | US-18, US-20, US-23 |
| F-02 | Verifikasi Posisi | US-19, US-20, US-21 |
| F-03 | Transparansi Informasi | US-14, US-25, US-28 |
| F-04 | Investor Matching | US-13, US-15, US-16, US-24, US-27, US-28, US-31 |
| F-05 | Price Discovery | US-26, US-27, US-28 |
| F-06 | Fleksibilitas Pengelolaan | US-12, US-17, US-22, US-23, US-29, US-30, US-31 |

**Supporting Stories:**
- Product Information & User Access: US-01 sampai US-09.
- Internal Development: US-10, US-11, dan US-32.

## 4. Product Constraints

- EXIT memfasilitasi proses penawaran dan permintaan take-over, tetapi tidak menjamin adanya calon pengambil alih.
- EXIT tidak menjamin tercapainya kesepakatan nilai pengalihan maupun keberhasilan pengalihan posisi investasi.
- Verifikasi dalam prototype terbatas pada pemeriksaan awal kelengkapan informasi posisi investasi.
- Sistem tidak menentukan nilai take-over secara otomatis.
- Pengalihan aktual bergantung pada ketentuan instrumen investasi, perjanjian, persetujuan penyelenggara, dan regulasi yang berlaku.
- Prototype tidak merepresentasikan transaksi pengalihan investasi aktual.
- Satu akun pengguna dapat menjalankan fungsi penawaran posisi maupun permintaan take-over.

## 5. Notes

1. Prioritas MoSCoW dan pembagian Sprint merupakan dasar perencanaan awal dan dapat disesuaikan berdasarkan hasil diskusi serta keputusan tim.
2. Acceptance Criteria digunakan sebagai acuan pengembangan dan pengujian setiap User Story.
3. Business Rules harus diselaraskan dengan bagian Business Rules pada PRD.
4. Mekanisme OTP, perubahan atau pembatalan penawaran, dan detail proses negosiasi perlu dikonfirmasi berdasarkan keputusan tim dan kemampuan prototype.
5. Setiap User Story harus tetap berada dalam ruang lingkup enam fitur utama dan batasan produk EXIT.
