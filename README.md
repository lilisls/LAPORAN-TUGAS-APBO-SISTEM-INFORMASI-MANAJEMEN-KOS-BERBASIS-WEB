# LAPORAN-TUGAS-APBO-SISTEM-INFORMASI-MANAJEMEN-KOS

## Anggota Kelompok 3

| Nama | NPM |
| :--- | :--- |
| Alamanda | 4522210078 |
| Lilis | 4524210051 |
| Ketut Sumantre | 4524210048 |
| Bunga Putri Nuriman | 4524210021 |
| Kornelius Timothy Setiawan | 4524210050 |

---

# Sasaran Pengguna
Sasaran Pengguna dari Sistem Informasi Manajemen Kos Berbasis Web ini terdiri dari dua kelompok utama: Pemilik atau Pengelola Kos sebagai Admin dan Penghuni Kos sebagai User. Sistem ini dirancang untuk memenuhi kebutuhan masing-masing pengguna agar pengelolaan kos lebih efisien dan komunikasi antar pemilik dan prnghuni berjalan lancar. Berikut adalah penjelasan singkat mengenai kedua kelompok pengguna tersebut:

### 1. Pengelola Kos (Admin)
Pengelola kos adalah pihak yang bertanggung jawab atas sistem dan operasional kos. Pengelola juga memiliki pekerjaan utama sehingga dibutuhkan sistem yang lebih efisien.  
Sebagai pengelola, mereka membutuhkan informasi terpusat mengenai pembayaran, data penghuni, dan status kamar agar bisa memantau kos secara efektif tanpa harus mengganggu pekerjaan utama.

### 2. Penghuni Kos (User)
Penghuni kos adalah mahasiswa atau pekerja yang menempati kamar kos. Mereka sudah terbiasa menggunakan smartphone dan membutuhkan kemudahan dalam melakukan pembayaran, mengirim keluhan, dan menerima pengumuman atau notifikasi penting.  
Sistem yang mudah diakses dan transparan akan membantu mereka menjaga kewajiban pembayaran dan komunikasi dengan pemilik kos.

---

# Studi Literatur
Keterbatasan dalam pengelolaan kos yang masih dilakukan secara manual menunjukkan perlunya penerapan sistem yang lebih terintegrasi dan efisien. Oleh karena itu, dilakukan peninjauan terhadap berbagai konsep dan teknologi yang mendukung pengembangan sistem informasi berbasis web. Studi literatur ini digunakan sebagai landasan dalam merancang solusi yang sesuai dengan kebutuhan pengelola maupun penghuni kos.


### 1. Sistem Informasi Manajemen
Sistem Informasi Manajemen merupakan sistem yang digunakan untuk mengelola dan mengolah data menjadi informasi yang berguna dalam mendukung operasional dan pengambilan keputusan. Dalam pengelolaan kos, sistem ini berperan dalam mengintegrasikan data penyewa, status kamar, serta riwayat pembayaran ke dalam satu sistem yang terstruktur.

Dengan adanya sistem yang terintegrasi, pengelola dapat memantau kondisi kos secara lebih efektif tanpa harus melakukan pencatatan secara manual, sehingga mengurangi risiko kesalahan dan meningkatkan efisiensi pengelolaan.

> **Referensi:**  [Sistem Informasi Manajemen (2021)](https://ojs.stmikdharmapalariau.ac.id/index.php/repository/article/view/590/340)


### 2. Sistem Berbasis Web
Sistem berbasis web merupakan sistem yang dapat diakses melalui browser dengan memanfaatkan jaringan internet, sehingga memungkinkan pengguna memperoleh informasi dengan lebih fleksibel. Dalam pengelolaan kos, sistem ini memberikan kemudahan dalam mengakses informasi terkait ketersediaan kamar, data penyewa, serta transaksi secara real-time.

Penelitian yang dilakukan oleh Zefanya Yulius Kurnia dan Marvin Chandra Wijaya (2024) menunjukkan bahwa penerapan sistem informasi kos berbasis web mampu meningkatkan efisiensi pengelolaan serta mempermudah akses informasi bagi pengguna. Hal ini membuktikan bahwa sistem berbasis web merupakan solusi yang efektif dalam mendukung pengelolaan kos secara modern.

> **Referensi:**  [Web-based information system for boarding house information (IJSRM, 2024)](https://doi.org/10.18535/ijsrm/v12i03.ec11)

### 3. Sistem Pembayaran Digital
Sistem pembayaran digital merupakan mekanisme yang digunakan untuk mendukung proses transaksi secara elektronik, yang mencakup pengelolaan tagihan (invoicing) serta pencatatan pembayaran secara sistematis. Dalam konteks e-business, sistem ini berperan dalam meningkatkan efisiensi transaksi, mempermudah proses pembayaran, serta memastikan keamanan dan keandalan dalam pengelolaan data pembayaran.

> **Referensi:** [Billing and Payment Systems (Springer, 2023)](https://link.springer.com/chapter/10.1007/978-3-031-39626-7_6#citeas)

### 4. Manajemen Keluhan
Manajemen keluhan merupakan proses pengelolaan laporan atau pengaduan dari pengguna terhadap suatu layanan. Penerapan sistem ini memungkinkan segala keluhan dicatat dan diproses secara terstruktur, sehingga memudahkan pengelola dalam melakukan tindak lanjut serta meningkatkan kualitas pelayanan. Selain itu, sistem manajemen keluhan juga membantu menciptakan transparansi dan komunikasi yang lebih efektif antara pengguna dan pengelola.

> **Referensi:**
> [Sistem Informasi Pengaduan Siswa Berbasis Website Dengan Framework Laravel (Josh, 2023)](https://pdfs.semanticscholar.org/cf97/0b30fc094d7c92a0435f36dd309cdc845891.pdf),
> [SISTEM INFORMASI PENGADUAN MASYARAKAT BERBASIS WEBSITE DI DESA PAGARBATU (2025)](https://doi.org/10.69714/s896fk61)

---

# Hasil Wawancara: Sistem Informasi Manajemen Kos

Klik pada masing-masing bagian di bawah ini untuk melihat detail daftar pertanyaan dan jawaban hasil wawancara terkait sistem yang sedang berjalan:

<details>
<summary><b>Bagian 1: Operasional & Manajemen Inventaris Kamar</b></summary>

1. **Bagaimana sistem pengelolaan kos saat ini berjalan?**
   > "Saat ini masih sepenuhnya manual, hanya mengandalkan WhatsApp untuk komunikasi dan buku tulis untuk pencatatan."

2. **Berapa jumlah kamar dan penghuni kos saat ini?**
   > "Total tersedia 20 kamar. Saat ini terisi 18 kamar dengan total penghuni sebanyak 18 orang."

3. **Apa saja kendala utama yang sering dihadapi dalam mengurus operasional kos?**
   > "Kendala utama adalah manajemen penagihan biaya bulanan dan menangani keluhan fasilitas. Karena faktor usia, pengelola sering kali lupa terhadap detail keluhan yang masuk."

4. **Bagaimana cara menyimpan dan mengelola data fisik penghuni?**
   > "Data disimpan dalam map fisik yang berisi fotokopi KTP dan Kartu Keluarga."

5. **Apakah pernah mengalami kesulitan atau kehilangan data penghuni?**
   > "Sering kesulitan mencari data karena tercampur dalam satu map dokumen. Bahkan pernah terjadi kehilangan data karena pengelola lupa tempat menyimpannya."
</details>

<details>
<summary><b>Bagian 2: Alur Pembayaran & Keuangan</b></summary>

1. **Bagaimana proses pembayaran kos dilakukan oleh penghuni?**
   > "Sebagian besar melalui transfer manual ke rekening bank atau GoPay, namun masih ada beberapa penghuni yang membayar secara tunai (cash)."

2. **Bagaimana metode pencatatan pembayaran yang digunakan?**
   > "Untuk transfer, penghuni mengirimkan bukti *screenshot* via WhatsApp, lalu saya catat manual di buku. Pembayaran tunai juga langsung dicatat di buku yang sama."

3. **Bagaimana cara Anda memantau status pembayaran setiap bulannya?**
   > "Saya harus mengecek buku catatan satu per satu dan mencocokkannya dengan mutasi di m-banking atau aplikasi GoPay untuk memastikan siapa yang belum bayar."

4. **Apakah sering terjadi keterlambatan pembayaran? Apa alasannya?**
   > "Lumayan sering, sekitar 3 sampai 4 orang setiap bulannya. Alasannya beragam, mulai dari menunggu tanggal gajian, kiriman orang tua yang terlambat, hingga murni karena lupa."
</details>

<details>
<summary><b>Bagian 3: Komunikasi & Penanganan Keluhan</b></summary>

1. **Bagaimana cara penghuni menyampaikan keluhan atau kendala fasilitas?**
   > "Biasanya melalui pesan pribadi di WhatsApp atau menyampaikan secara langsung saat bertemu pengelola."

2. **Apakah ada keluhan yang sering terlewat untuk ditangani?**
   > "Sering sekali. Karena tidak terdokumentasi dengan baik dan faktor usia pengelola, banyak keluhan yang akhirnya terlupakan."

3. **Bagaimana cara pengelola menyampaikan informasi penting kepada seluruh penghuni?**
   > "Kami menggunakan grup WhatsApp khusus penghuni untuk membagikan pengumuman atau informasi penting."

4. **Apakah penyampaian informasi melalui grup tersebut sudah efektif?**
   > "Kurang efektif. Sering kali informasi terlewat karena chat yang menumpuk, grup yang di-*mute* oleh penghuni, atau hanya dibaca sekilas tanpa diperhatikan."
</details>

<details>
<summary><b>Bagian 4: Kebutuhan & Harapan Terhadap Sistem Baru</b></summary>

1. **Apakah sistem digital akan membantu pengelolaan kos sehari-hari?**
   > "Sangat membantu. Sistem manual saat ini sangat tidak efisien. Dengan sistem baru, diharapkan manajemen menjadi lebih rapi dan pengelola tidak perlu mengecek data secara manual satu per satu."

2. **Bagian mana yang paling krusial untuk segera diperbaiki?**
   > "Prioritas utama adalah perbaikan pada sistem pencatatan pembayaran dan digitalisasi manajemen data penghuni."

3. **Bagaimana pendapat Anda mengenai fitur pengingat pembayaran otomatis?**
   > "Itu akan sangat mempermudah kerja kami. Selain lebih praktis, kami tidak perlu lagi merasa sungkan saat harus menagih penghuni satu per satu secara manual."

4. **Preferensi notifikasi seperti apa yang Anda harapkan?**
   > "Untuk penghuni, notifikasi via WhatsApp adalah yang paling efektif. Sedangkan untuk pengelola, saya membutuhkan *dashboard* berbasis web agar bisa melihat rekapitulasi data secara menyeluruh."
</details>

---
## 🎥 Video Dokumentasi

[![Video Dokumentasi](cover/cover.jpeg)](https://youtu.be/RORLaileWqk)

*(Klik gambar di atas untuk memutar video)*

---

# Latar Belakang


Pengelolaan rumah kos ini masih dilakukan secara manual, terutama dalam pencatatan data penyewa, ketersediaan kamar, serta pembayaran sewa. Cara ini berpotensi menimbulkan berbagai permasalahan seperti kesalahan pencatatan, keterlambatan informasi, hingga kesulitan dalam memantau status kamar secara akurat. Di sisi lain, tingginya mobilitas mahasiswa sebagai penyewa kos menuntut adanya akses informasi yang cepat dan praktis terkait ketersediaan kamar, harga, serta fasilitas yang ditawarkan.

Untuk mengatasi permasalahan tersebut, diperlukan sebuah sistem informasi manajemen kos berbasis web yang mampu mengintegrasikan proses pengelolaan data sekaligus memberikan kemudahan akses bagi penyewa sebagai pengguna utama. Sistem ini diharapkan dapat membantu pengelola dalam melakukan pencatatan secara lebih terstruktur dan efisien, serta memungkinkan penyewa memperoleh informasi kos secara real-time tanpa harus datang langsung ke lokasi. Dengan demikian, sistem ini tidak hanya meningkatkan efisiensi pengelolaan, tetapi juga memberikan nilai tambah dalam pelayanan kepada penyewa di lingkungan sekitar kampus.

---

## Bagian 1: Analisis Aktor

# 1. Pengelola Kos (Admin)

Pengelola kos menjadi pihak yang paling berperan dalam sistem ini karena semua kegiatan operasional dipegang oleh pengelola. Dari yang saya lihat, sebagian besar proses masih dilakukan secara manual, sehingga cukup merepotkan jika data sudah banyak.

Tugas dan tanggung jawab:
- Mengelola data penghuni, seperti menambah atau mengubah data
- Mengatur kamar, apakah masih kosong atau sudah terisi
- Mencatat dan mengecek pembayaran dari penghuni
- Melihat laporan keuangan
- Menangani keluhan dari penghuni
- Mengingatkan penghuni terkait pembayaran

---

# 2. Penghuni Kos (User)

Penghuni kos adalah pengguna yang langsung menggunakan sistem ini. Biasanya lebih fokus pada pembayaran dan penyampaian keluhan.

Tugas dan tanggung jawab:
- Melakukan pembayaran kos
- Mengunggah bukti pembayaran
- Mengecek status pembayaran
- Menyampaikan keluhan jika ada masalah
- Menerima informasi atau pengingat dari sistem

---

# 3. Sistem

Sistem berfungsi untuk membantu agar semua proses menjadi lebih rapi dan tidak lagi dilakukan secara manual.

Tugas dan tanggung jawab:
- Mengirim notifikasi otomatis, seperti pengingat pembayaran
- Menyimpan data penghuni dan pembayaran
- Menampilkan data dalam bentuk dashboard
- Menyimpan riwayat pembayaran dan keluhan
- Membantu pencarian data dengan lebih cepat

## Bagian 2: Analisis Perbandingan Sistem

# 1. Manajemen Data Penghuni

Sistem manual:
Data biasanya disimpan dalam bentuk berkas seperti fotokopi KTP. Jika jumlah data sudah banyak, akan sulit dicari karena tercampur.

Sistem digital:
Data disimpan dalam database sehingga lebih rapi dan mudah dicari. Risiko kehilangan data juga lebih kecil.

---

# 2. Pembayaran

Sistem manual:
Pembayaran dicatat di buku, dan bukti pembayaran sering dikirim melalui WhatsApp. Untuk mengecek siapa yang belum bayar harus dilakukan satu per satu.

Sistem digital:
Pembayaran tercatat langsung di sistem. Penghuni dapat mengunggah bukti pembayaran dan statusnya bisa langsung dilihat.

---

# 3. Pengingat Pembayaran

Sistem manual:
Pengelola harus mengingat dan menagih secara manual, dan terkadang merasa tidak enak.

Sistem digital:
Sistem dapat mengirim pengingat otomatis sehingga lebih praktis dan mengurangi keterlambatan.

---

# 4. Keluhan

Sistem manual:
Keluhan disampaikan melalui chat dan tidak selalu tercatat dengan baik.

Sistem digital:
Keluhan tercatat dalam sistem sehingga memiliki riwayat dan lebih mudah ditindaklanjuti.

---

# 5. Penyampaian Informasi

Sistem manual:
Informasi disampaikan melalui grup WhatsApp, namun sering tertumpuk dan terlewat.

Sistem digital:
Informasi lebih teratur dan dapat diakses kembali kapan saja.

## Bagian 3: Skenario Sistem / Use Case

### Pemetaan Aktor & Hak Akses

Berikut adalah pemetaan aktor yang terlibat dalam Sistem Informasi Manajemen Kos beserta hak akses dan fungsionalitasnya:

| Peran (Aktor) | Ruang Lingkup Akses | Fungsionalitas Utama |
| :--- | :--- | :--- |
| **Pengelola (Admin)** | Memiliki akses penuh terhadap seluruh data dan fitur dalam sistem, termasuk data penghuni, kamar, pembayaran, dan laporan keuangan | • Mengelola data penghuni (tambah, ubah, hapus, dan pencarian) <br>• Mengelola data kamar dan status ketersediaan <br>• Memproses masuk/keluar penghuni (check-in & check-out) <br>• Memverifikasi pembayaran kos <br>• Melihat dashboard dan laporan keuangan <br>• Mengelola dan menanggapi keluhan penghuni <br>• Mengirim notifikasi atau pengingat pembayaran |
| **Penghuni Kos (User)** | Memiliki akses terbatas pada data pribadi dan layanan yang berkaitan dengan kamar yang ditempati | • Melihat informasi kamar dan tagihan bulanan <br>• Mengunggah bukti pembayaran <br>• Melihat status dan riwayat pembayaran <br>• Mengirim keluhan atau pengaduan fasilitas <br>• Menerima notifikasi dan informasi penting |
| **Sistem (Automated System)** | Bertindak sebagai aktor otomatis yang menjalankan proses sistem secara terintegrasi | • Menghasilkan tagihan bulanan secara otomatis <br>• Mengirim notifikasi pengingat pembayaran <br>• Menyimpan dan mengelola database secara terpusat <br>• Menampilkan data secara real-time pada dashboard <br>• Melakukan filtering data (misalnya penghuni yang belum membayar, status kamar, dll) |

### Detail Use Case

#### 1. Pendaftaran Penghuni & Alokasi Kamar (Onboarding)
**Aktor**: Pengelola (Admin)  
**Tujuan**: Memasukkan data penyewa baru ke dalam database dan menetapkan unit kamar yang akan ditempati.  
**Alur Interaksi**:
1. Pengelola membuka menu *Manajemen Kamar* dan memfilter unit yang berstatus `[KOSONG]`.
2. Pengelola menginput kelengkapan data diri penyewa (KTP, Kontak darurat).
3. Pengelola menentukan durasi sewa, uang jaminan (deposit), dan tanggal jatuh tempo.

**Output / Hasil Akhir**: Unit kamar terkunci dengan status `[DIHUNI]` dan akun portal untuk penyewa otomatis aktif.

#### 2. Pelunasan Tagihan Sewa Bulanan
**Aktor**: Penghuni & Pengelola  
**Syarat Awal**: Sistem telah menerbitkan *invoice* tagihan berstatus `[BELUM DIBAYAR]`.  
**Alur Interaksi**:
1. Penghuni masuk ke portal, melihat nominal tagihan, lalu melakukan transfer dana.
2. Penghuni melampirkan foto resi transfer ke dalam sistem.
3. Status tagihan otomatis berubah menjadi `[MENUNGGU VERIFIKASI]`.
4. Pengelola menerima peringatan sistem, mengecek mutasi rekening, dan menekan tombol *Verifikasi Lunas*.

**Output / Hasil Akhir**: Sistem menerbitkan kuitansi digital dan riwayat pembayaran penghuni tercatat sukses.

#### 3. Tiket Laporan Keluhan (Maintenance)
**Aktor**: Penghuni & Pengelola  
**Tujuan**: Memfasilitasi pelaporan fasilitas yang rusak (misal: AC bocor, kran mati) agar tidak terlewat oleh pengelola.  
**Alur Interaksi**:
1. Penghuni membuat tiket aduan baru dengan memilih kategori dan melampirkan foto kerusakan.
2. Tiket masuk ke *dashboard* pengelola dengan status `[ANTREAN]`.
3. Pengelola mengalokasikan teknisi/tukang dan mengubah status menjadi `[DIPROSES]`.
4. Setelah masalah teratasi, pengelola menutup tiket aduan tersebut.

**Output / Hasil Akhir**: Status tiket menjadi `[SELESAI]` dan penghuni bisa melihat pembaruannya di portal mereka.

#### 4. Pengosongan Kamar (Proses Check-out)
**Aktor**: Pengelola (Admin)  
**Tujuan**: Menyelesaikan masa sewa penghuni, menangani deposit, dan menyiapkan kamar untuk penyewa berikutnya.  
**Alur Interaksi**:
1. Penghuni mengonfirmasi masa akhir sewa kepada pengelola.
2. Pengelola melakukan inspeksi final kamar. Jika ada kerusakan berat, pengelola mencatat potongan dari uang deposit.
3. Pengelola menekan eksekusi *Check-out* pada profil penghuni.

**Output / Hasil Akhir**: Data penghuni diarsipkan ke daftar *Alumni*, dan status kamar dikembalikan menjadi `[KOSONG]`.

#### 5. Rekapitulasi Keuangan & Operasional
**Aktor**: Pengelola (Admin)  
**Tujuan**: Menghitung laba/rugi bulanan dari bisnis kost.  
**Alur Interaksi**:
1. Pengelola mencatat semua biaya operasional bulanan (Token listrik induk, iuran sampah, biaya perbaikan).
2. Sistem mengakumulasikan total pengeluaran tersebut.
3. Sistem membandingkannya dengan total pemasukan dari sewa kamar bulan itu.

**Output / Hasil Akhir**: Terbentuk grafik atau laporan bersih laba/rugi yang bisa diunduh oleh pengelola.

### Diagram Use Case

<img width="631" height="620" alt="Screenshot 2026-04-29 195457" src="https://github.com/user-attachments/assets/b181a0a0-3c3c-4e8a-88a6-2306ad5d2035" />

---

### Diagram Class

<img width="1050" height="1306" alt="Diagram Class SI Manajemen Kost (APBO) drawio" src="https://github.com/user-attachments/assets/7606b8c6-b6f2-46c4-b13e-8f123fe359aa" />


---

# Dokumentasi Perancangan Sistem

## Penjelasan Diagram Class

Diagram Class pada Sistem Informasi Manajemen Kos Berbasis Web digunakan untuk menggambarkan struktur data statis, spesifikasi kelas, atribut, fungsi (method), serta hubungan (relationship) antar objek secara terintegrasi. 

Sesuai dengan prinsip enkapsulasi pada Pemrograman Berorientasi Objek (OOP), seluruh atribut diatur sebagai Private untuk mengamankan data internal dari akses langsung luar kelas, sedangkan method/fungsi diatur sebagai Public agar dapat dieksekusi oleh sistem atau antarmuka pengguna (UI).

---

## 1. Class Admin
Class Admin merepresentasikan pengelola kos yang memegang hak akses penuh terhadap sistem untuk mengontrol seluruh aktivitas operasional dan administrasi.

### Atribut (Private)
* idAdmin : int — Identitas unik sistem untuk admin
* nama : string — Nama lengkap pengelola kos
* username : string — Kredensial unik untuk hak akses masuk admin
* password : string — Kata sandi akun admin (terenkripsi)
* noHp : string — Nomor telepon pengelola yang aktif

### Method (Public)
* login() — Memvalidasi kredensial masuk admin ke sistem
* kelolaKamar() — Melakukan operasi CRUD (Create, Read, Update, Delete) pada data kamar
* kelolaPenghuni() — Mengelola data registrasi, profil, dan status tinggal penghuni
* verifikasiBayar() — Memeriksa dan menyetujui validitas bukti pembayaran sewa
* lihatLaporan() — Mengakses visualisasi dashboard dan rekapitulasi keuangan kos
* tanganiKeluhan() — Mengalokasikan atau memperbarui status penanganan laporan kerusakan
* kirimNotifikasi() — Memicu pengiriman pengumuman atau pengingat tagihan ke penghuni

---

## 2. Class Penghuni
Class Penghuni merepresentasikan penyewa kamar kos yang menggunakan sistem secara mandiri untuk mengakses layanan sewa, transaksi, dan pengaduan.

### Atribut (Private)
* idPenghuni : int — Identitas unik sistem untuk penghuni
* nama : string — Nama lengkap penghuni sesuai kartu identitas
* alamat : string — Alamat asal penghuni sesuai KTP
* noHp : string — Nomor telepon seluler penghuni yang dapat dihubungi
* noKTP : string — Nomor Induk Kependudukan (NIK) resmi penyewa
* kontakDarurat : string — Nomor telepon kerabat dekat jika terjadi situasi darurat
* tglMasuk : date — Tanggal resmi dimulainya kontrak sewa kamar
* tglKeluar : date — Tanggal berakhirnya kontrak sewa atau rencana check-out
* username : string — Kredensial unik akun penghuni
* password : string — Kata sandi keamanan akun penghuni

### Method (Public)
* login() — Memproses autentikasi masuk penghuni ke platform
* uploadPembayaran() — Mengirim dan menyimpan berkas digital bukti transfer bank
* kirimKeluhan() — Membuat formulir pengaduan terkait kerusakan fasilitas kos
* lihatTagihan() — Menampilkan rincian nominal tagihan aktif bulan berjalan
* lihatRiwayat() — Mengakses daftar transaksi pembayaran yang pernah dilakukan sebelumnya

---

## 3. Class Teknisi
Class Teknisi digunakan untuk mendata pekerja lapangan yang bertanggung jawab melakukan perbaikan fisik berdasarkan eskalasi keluhan fasilitas.

### Atribut (Private)
* idTeknisi : int — Identitas unik sistem untuk teknisi
* nama : string — Nama lengkap teknisi
* noHp : string — Nomor kontak teknisi untuk koordinasi perbaikan
* bidang : string — Keahlian spesifik teknisi (misal: Kelistrikan, Plambing, Elektronik)

### Method (Public)
* perbaikiFasilitas() — Mengubah status penanganan kerja teknisi pada fasilitas terkait

---

## 4. Class Kamar
Class Kamar merepresentasikan data fisik entitas unit kamar kos yang disewakan.

### Atribut (Private)
* idKamar : int — Identitas unik untuk tiap unit kamar
* nomorKamar : string — Kode unik atau nomor penanda kamar (misal: A01, B05)
* tipeKamar : string — Kategori kelas kamar (misal: Deluxe, Standard, VIP)
* harga : double — Nominal tarif biaya sewa per bulan
* status : string — Indikator ketersediaan kamar (misal: Kosong, Dihuni, Pemeliharaan)
* fasilitas : string — Daftar inventaris bawaan di dalam kamar

### Method (Public)
* ubahStatus() — Memperbarui indikator ketersediaan unit kamar secara otomatis/manual
* tampilInfo() — Menyajikan rincian spesifikasi lengkap kamar kepada pengguna

---

## 5. Class Keluhan
Class Keluhan digunakan untuk mencatat, menampung, dan melacak status penyelesaian masalah sarana kos yang dikeluhkan pengguna.

### Atribut (Private)
* idKeluhan : int — Nomor tiket unik pengaduan keluhan
* kategori : string — Jenis area keluhan (misal: Air, Fasilitas Kamar, Fasilitas Umum)
* deskripsi : string — Penjelasan kronologi atau detail kerusakan sarana
* foto : string — Jalur penyimpanan (path/URL) file foto bukti kerusakan
* status : string — Status progres pelaporan (misal: Antrean, Diproses, Selesai)
* tanggalKeluhan : date — Waktu (stempel tanggal) pengaduan dikirim pertama kali

### Method (Public)
* buatKeluhan() — Menyimpan data laporan pengaduan baru dari penghuni ke database
* updateStatus() — Memperbarui alur penanganan keluhan oleh pihak pengelola
* tutupKeluhan() — Mengunci status tiket aduan menjadi selesai jika perbaikan rampung

---

## 6. Class Notifikasi
Class Notifikasi berfungsi sebagai mesin pengelola pesan atau pengingat berkala yang dihasilkan oleh sistem.

### Atribut (Private)
* idNotifikasi : int — Identitas unik rekaman notifikasi
* pesan : string — Teks isi pesan/informasi penting yang dikirimkan
* tanggalKirim : datetime — Log waktu pengiriman pesan
* jenis : string — Kategori pesan (misal: Peringatan Tagihan, Pengumuman Bersama)

### Method (Public)
* kirimNotif() — Menyebarkan atau menampilkan pesan notifikasi ke akun tujuan

---

## 7. Class Tagihan
Class Tagihan menyimpan akumulasi nilai finansial berkala yang wajib dilunasi oleh penghuni sesuai siklus sewa.

### Atribut (Private)
* idTagihan : int — Nomor invoice unik lembar tagihan
* bulan : string — Periode siklus tagihan bulanan (misal: Oktober 2026)
* totalTagihan : double — Jumlah nominal uang yang harus dibayarkan
* jatuhTempo : date — Batas waktu akhir pembayaran sebelum dikenai sanksi/teguran
* status : string — Kondisi tagihan saat ini (misal: Belum Dibayar, Lunas)

### Method (Public)
* generateTagihan() — Menghasilkan lembar tagihan otomatis berdasarkan waktu jatuh tempo sewa
* ubahStatus() — Mengubah parameter tagihan menjadi lunas pasca verifikasi admin

---

## 8. Class Pembayaran
Class Pembayaran mencatat seluruh riwayat pembuktian transaksi finansial yang diajukan penghuni sebagai pelunasan tagihan.

### Atribut (Private)
* idPembayaran : int — Identitas unik untuk tiap transaksi masuk
* tanggalBayar : date — Log tanggal penghuni mengirimkan pembayaran
* jumlah : double — Nominal uang tunai/transfer yang didepositkan
* buktiTransfer : string — Jalur berkas gambar/dokumen bukti transfer bank
* statusPembayaran : string — Status validasi transaksi (misal: Menunggu Verifikasi, Disetujui, Ditolak)

### Method (Public)
* uploadBukti() — Mengunggah file tanda transfer dari sisi user
* verifikasi() — Mengubah status peninjauan keabsahan dana oleh admin
* cetakKuitansi() — Menghasilkan dokumen kuitansi digital resmi berformat cetak

---

## 9. Class BiayaOperasional
Class BiayaOperasional berfungsi mencatat arus kas keluar (cash outflow) di luar pengeluaran pribadi penyewa untuk kebutuhan operasional rumah kos.

### Atribut (Private)
* idBiaya : int — Identitas unik pos pengeluaran operasional
* namaBiaya : string — Nama deskripsi alokasi biaya (misal: Tagihan Listrik Induk, Gaji Teknisi)
* tanggal : date — Tanggal terjadinya pengeluaran kas
* jumlah : double — Nominal uang kas kos yang dikeluarkan

### Method (Public)
* tambahBiaya() — Menambahkan pencatatan pos biaya pengeluaran operasional baru

---

## 10. Class LaporanKeuangan
Class LaporanKeuangan berfungsi merekapitulasi seluruh kalkulasi neraca laba-rugi bisnis kos pada jangka waktu berkala.

### Atribut (Private)
* idLaporan : int — Identitas unik berkas laporan keuangan
* periode : string — Rentang jangka laporan (misal: Triwulan I - 2026)
* totalPemasukan : double — Akumulasi dana transaksi pembayaran sewa yang sah/lunas
* totalPengeluaran : double — Akumulasi pengeluaran dari seluruh Biaya Operasional
* labaBersih : double — Hasil perhitungan laba bersih (Total Pemasukan - Total Pengeluaran)

### Method (Public)
* generateLaporan() — Memproses kalkulasi otomatis pemasukan dan pengeluaran berkala
* exportPDF() — Mengompilasi dan mengunduh berkas laporan keuangan ke format cetak PDF

---

## Penjelasan Relasi Antar Class

### 1. Relasi Admin dengan Penghuni
* **Jenis Relasi:** One to Many (1..*)
* **Penjelasan:** Admin memiliki hubungan dengan Penghuni dalam proses pengelolaan data penghuni, seperti menambah, mengubah, dan menghapus data penghuni. Satu admin dapat mengelola banyak penghuni.

### 2. Relasi Admin dengan Kamar
* **Jenis Relasi:** One to Many (1..*)
* **Penjelasan:** Admin memiliki hubungan dengan Kamar dalam pengelolaan status dan informasi kamar kos. Satu admin dapat mengelola banyak kamar.

### 3. Relasi Admin dengan Keluhan
* **Jenis Relasi:** One to Many (1..*)
* **Penjelasan:** Admin memiliki hubungan dengan Keluhan dalam proses penanganan dan tindak lanjut laporan penghuni. Satu admin dapat menangani banyak keluhan.

### 4. Relasi Admin dengan LaporanKeuangan
* **Jenis Relasi:** One to Many (1..*)
* **Penjelasan:** Admin memiliki hubungan dengan LaporanKeuangan dalam proses pembuatan dan monitoring laporan keuangan kos. Satu admin dapat membuat banyak laporan keuangan.

### 5. Relasi Penghuni dengan Kamar
* **Jenis Relasi:** One to One (0..1 ke 1)
* **Penjelasan:** Penghuni memiliki hubungan dengan Kamar karena setiap penghuni menempati satu kamar kos. Relasi 0..1 menunjukkan bahwa penghuni bisa belum memiliki kamar atau hanya menempati satu kamar.

### 6. Relasi Penghuni dengan Pembayaran
* **Jenis Relasi:** One to Many (1..*)
* **Penjelasan:** Penghuni memiliki hubungan dengan Pembayaran karena penghuni dapat melakukan banyak pembayaran selama masa sewa kos.

### 7. Relasi Penghuni dengan Tagihan
* **Jenis Relasi:** One to Many (1..*)
* **Penjelasan:** Penghuni memiliki hubungan dengan Tagihan karena setiap penghuni memiliki beberapa tagihan pembayaran bulanan.

### 8. Relasi Penghuni dengan Keluhan
* **Jenis Relasi:** One to Many (1..*)
* **Penjelasan:** Penghuni memiliki hubungan dengan Keluhan karena penghuni dapat membuat banyak laporan kerusakan atau pengaduan fasilitas.

### 9. Relasi Notifikasi dengan Penghuni
* **Jenis Relasi:** Many to One (*..1)
* **Penjelasan:** Notifikasi memiliki hubungan dengan Penghuni karena sistem dapat mengirim banyak notifikasi kepada satu penghuni, seperti pengingat pembayaran atau informasi penting.

### 10. Relasi Tagihan dengan Pembayaran
* **Jenis Relasi:** One to One (1 ke 0..1)
* **Penjelasan:** Tagihan memiliki hubungan dengan Pembayaran karena satu tagihan hanya dapat dibayar dengan satu pembayaran atau belum dibayar sama sekali.

### 11. Relasi Keluhan dengan Teknisi
* **Jenis Relasi:** Many to One (*..1)
* **Penjelasan:** Keluhan memiliki hubungan dengan Teknisi karena satu teknisi dapat menangani banyak keluhan, sedangkan satu keluhan ditangani oleh maksimal satu teknisi.

### 12. Relasi LaporanKeuangan dengan Pembayaran
* **Jenis Relasi:** One to Many (1..*)
* **Penjelasan:** LaporanKeuangan memiliki hubungan dengan Pembayaran karena satu laporan keuangan mengambil data dari banyak transaksi pembayaran sebagai sumber pemasukan.

### 13. Relasi LaporanKeuangan dengan BiayaOperasional
* **Jenis Relasi:** One to Many (1..*)
* **Penjelasan:** LaporanKeuangan memiliki hubungan dengan BiayaOperasional karena satu laporan keuangan mengambil data dari banyak biaya operasional sebagai sumber pengeluaran.

---

## Kesimpulan

Berdasarkan hasil wawancara dan analisis sistem yang sedang berjalan, dapat disimpulkan bahwa pengelolaan kos yang masih dilakukan secara manual menimbulkan berbagai permasalahan signifikan, seperti kesulitan dalam pencatatan dan pencarian data penghuni, ketidakefisienan dalam monitoring pembayaran, serta kurang optimalnya komunikasi antara pengelola dan penghuni. Permasalahan ini diperkuat oleh kondisi nyata di lapangan, seperti penggunaan buku tulis dan WhatsApp sebagai media utama, yang terbukti rentan terhadap kesalahan, kehilangan data, serta informasi yang terlewat.

Oleh karena itu, pengembangan sistem informasi manajemen kos berbasis web menjadi solusi yang relevan dan dibutuhkan, dengan mempertimbangkan dua aktor utama yaitu pengelola sebagai admin dan penghuni sebagai user. Sistem ini tidak hanya berfungsi untuk meningkatkan efisiensi pengelolaan data dan operasional kos, tetapi juga memberikan kemudahan akses, transparansi informasi, serta peningkatan kualitas komunikasi. Dengan adanya fitur seperti pencatatan pembayaran otomatis, notifikasi pengingat, serta manajemen keluhan terintegrasi, sistem diharapkan mampu mengatasi permasalahan yang ada sekaligus meningkatkan kualitas layanan kos secara keseluruhan.
