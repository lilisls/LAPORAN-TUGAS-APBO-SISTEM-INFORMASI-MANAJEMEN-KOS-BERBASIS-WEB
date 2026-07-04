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

# Bagian 3: Skenario Sistem / Use Case

## Pemetaan Aktor & Hak Akses

Berikut adalah pemetaan aktor yang terlibat dalam Sistem Informasi Manajemen Kos beserta hak akses dan fungsionalitasnya yang telah disesuaikan dengan prinsip *Object-Oriented Programming* (OOP):

| Peran (Aktor) | Ruang Lingkup Akses | Fungsionalitas Utama |
| :--- | :--- | :--- |
| **Pengelola Kos (Admin)** | Memiliki akses penuh terhadap seluruh data operasional sistem melalui autentikasi untuk memicu fungsi manajemen entitas. | * Melakukan `Login` & `Logout`<br>* Kelola Data Penghuni<br>* Kelola Data Kamar (Alokasi Kamar)<br>* Memverifikasi Pembayaran<br>* Memproses Keluhan<br>* Memproses Check-out<br>* Kelola Biaya Operasional<br>* Melihat Laporan Keuangan<br>* Kelola Informasi & Pengumuman |
| **Penghuni Kos (User)** | Memiliki akses terbatas pada manipulasi data pribadi dan pengiriman data objek yang berelasi dengan kamarnya sendiri. | * Melakukan `Login` & `Logout`<br>* Melihat Tagihan<br>* Upload Bukti Pembayaran<br>* Melihat Riwayat Pembayaran<br>* Membuat Keluhan<br>* Melihat Notifikasi & Pengumuman |

---

## Detail Use Case

Setiap skenario di bawah ini dirancang dengan prinsip *Single Responsibility* (Satu Use Case fokus pada aksi aktif dari satu aktor utama):

### 1. Use Case: Kelola Data Penghuni
* **Aktor Utama:** Pengelola Kos (Admin)  
* **Tujuan:** Menambahkan, mengubah, atau menghapus data identitas penghuni kos ke dalam database sistem.  
* **Alur Interaksi:**
  1. Admin memilih menu "Kelola Data Penghuni".
  2. Admin memilih opsi "Tambah Penghuni Baru".
  3. Admin menginput data identitas penghuni (Nama, No HP, Kontak Darurat, Username, Password).
  4. Sistem memvalidasi inputan dan menyimpan data objek Penghuni baru.
* **Output / Hasil Akhir:** Objek data penghuni baru berhasil dibuat dan tersimpan.

### 2. Use Case: Kelola Data Kamar (Alokasi Kamar)
* **Aktor Utama:** Pengelola Kos (Admin)  
* **Tujuan:** Mengatur informasi kamar dan memetakan penempatan kamar untuk penghuni baru.  
* **Alur Interaksi:**
  1. Admin membuka menu "Kelola Data Kamar".
  2. Admin memilih nomor kamar yang berstatus "Kosong".
  3. Admin mengalokasikan kamar tersebut kepada salah satu ID Penghuni.
  4. Sistem memperbarui atribut status kamar menjadi "Terisi".
* **Output / Hasil Akhir:** Status kamar berubah di dalam sistem dan penempatan kamar terdata.

### 3. Use Case: Upload Bukti Pembayaran
* **Aktor Utama:** Penghuni Kos  
* **Tujuan:** Mengunggah berkas bukti transaksi transfer bank untuk melunasi tagihan kos bulanan.  
* **Alur Interaksi:**
  1. Penghuni memilih menu "Melihat Tagihan".
  2. Penghuni memilih tagihan aktif lalu menekan opsi "Upload Bukti".
  3. Penghuni mengunggah gambar resi transfer dan menekan tombol kirim.
  4. Sistem membuat objek Pembayaran baru dan mengubah status objek Tagihan terkait menjadi "Menunggu Verifikasi".
* **Output / Hasil Akhir:** Objek pembayaran tercipta dan status tagihan terbarui.

### 4. Use Case: Memverifikasi Pembayaran
* **Aktor Utama:** Pengelola Kos (Admin)  
* **Tujuan:** Melakukan pengecekan terhadap validitas bukti transfer yang diunggah oleh penghuni kos.  
* **Alur Interaksi:**
  1. Admin membuka menu "Memverifikasi Pembayaran".
  2. Admin memilih data pembayaran yang berstatus "Menunggu Verifikasi".
  3. Admin memeriksa kesesuaian gambar bukti transfer dengan mutasi bank asli.
  4. Admin menekan tombol "Verifikasi Sukses" (atau "Tolak" jika tidak sesuai).
  5. Sistem mengubah status Pembayaran menjadi "Lunas" dan meneruskan pembaruan data ke kelas Laporan Keuangan.
* **Output / Hasil Akhir:** Transaksi dinyatakan sah dan status tagihan berubah menjadi lunas.

### 5. Use Case: Membuat Keluhan
* **Aktor Utama:** Penghuni Kos  
* **Tujuan:** Melaporkan adanya kendala atau kerusakan pada fasilitas kos agar terdata oleh pengelola.  
* **Alur Interaksi:**
  1. Penghuni membuka menu "Membuat Keluhan".
  2. Penghuni mengisi kategori keluhan, deskripsi permasalahan, dan mengunggah foto pendukung.
  3. Sistem membuat objek data Keluhan baru dengan status awal berupa "Pending".
* **Output / Hasil Akhir:** Laporan keluhan baru terdaftar di dalam sistem antrean admin.

### 6. Use Case: Memproses Keluhan
* **Aktor Utama:** Pengelola Kos (Admin)  
* **Tujuan:** Merespons, menindaklanjuti, dan memperbarui status penanganan atas keluhan fasilitas yang dikirim oleh penghuni.  
* **Alur Interaksi:**
  1. Admin membuka menu "Memproses Keluhan".
  2. Admin memilih keluhan berstatus "Pending" dan mengubah statusnya menjadi "Sedang Diproses" saat teknisi mulai bekerja.
  3. Setelah perbaikan fasilitas selesai dilakukan, Admin menekan tombol "Selesaikan Keluhan".
  4. Sistem memperbarui status objek Keluhan tersebut menjadi "Selesai".
* **Output / Hasil Akhir:** Siklus hidup objek keluhan ditutup dengan status akhir selesai.

### 7. Use Case: Memproses Check-out
* **Aktor Utama:** Pengelola Kos (Admin)  
* **Tujuan:** Menyelesaikan masa sewa penghuni, mengarsipkan data, dan mengosongkan kembali slot kamar.  
* **Alur Interaksi:**
  1. Admin membuka menu "Memproses Check-out".
  2. Admin memilih nama penghuni yang masa sewanya telah berakhir atau mengajukan keluar.
  3. Admin memvalidasi administrasi akhir dan menyelesaikan sewa.
  4. Sistem mengubah status objek Kamar terkait menjadi "Kosong" dan mengarsipkan record Penghuni tersebut.
* **Output / Hasil Akhir:** Kamar kembali berstatus kosong dan siap dialokasikan ulang.

### 8. Use Case: Kelola Biaya Operasional & Keuangan
* **Aktor Utama:** Pengelola Kos (Admin)  
* **Tujuan:** Mencatat pengeluaran rutin kos bulanan serta memantau ringkasan neraca laba bersih.  
* **Alur Interaksi:**
  1. Admin membuka menu "Kelola Biaya Operasional".
  2. Admin menginput nominal dan detail pengeluaran kos (misal: listrik, air, gaji penjaga).
  3. Sistem menyimpan data pengeluaran dan secara otomatis memperbarui kalkulasi pada objek Laporan Keuangan.
* **Output / Hasil Akhir:** Data pengeluaran kos tercatat dan terakumulasi ke dalam neraca keuangan.

---

## Diagram Use Case

### Diagram Use Case

Di bawah ini adalah representasi visual dari hubungan interaksi antar aktor terhadap fungsi-fungsi di dalam Sistem Informasi Manajemen Kos:

<img width="307" height="580" alt="USE CASE DIAGRAM - SI MANAJEMEN KOST drawio" src="https://github.com/user-attachments/assets/4f5df610-c4cd-48ed-bea0-b4aa8e12b2f0" />



---

## Kesimpulan

Berdasarkan hasil wawancara dan analisis sistem yang sedang berjalan, dapat disimpulkan bahwa pengelolaan kos yang masih dilakukan secara manual menimbulkan berbagai permasalahan signifikan, seperti kesulitan dalam pencatatan dan pencarian data penghuni, ketidakefisienan dalam monitoring pembayaran, serta kurang optimalnya komunikasi antara pengelola dan penghuni. Permasalahan ini diperkuat oleh kondisi nyata di lapangan, seperti penggunaan buku tulis dan WhatsApp sebagai media utama, yang terbukti rentan terhadap kesalahan, kehilangan data, serta informasi yang terlewat.

Oleh karena itu, pengembangan sistem informasi manajemen kos berbasis web menjadi solusi yang relevan dan dibutuhkan, dengan mempertimbangkan dua aktor utama yaitu pengelola sebagai admin dan penghuni sebagai user. Sistem ini tidak hanya berfungsi untuk meningkatkan efisiensi pengelolaan data dan operasional kos, tetapi juga memberikan kemudahan akses, transparansi informasi, serta peningkatan kualitas komunikasi. Dengan adanya fitur seperti pencatatan pembayaran otomatis, notifikasi pengingat, serta manajemen keluhan terintegrasi, sistem diharapkan mampu mengatasi permasalahan yang ada sekaligus meningkatkan kualitas layanan kos secara keseluruhan.
