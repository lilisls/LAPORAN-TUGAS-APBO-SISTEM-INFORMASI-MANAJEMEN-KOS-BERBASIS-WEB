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
