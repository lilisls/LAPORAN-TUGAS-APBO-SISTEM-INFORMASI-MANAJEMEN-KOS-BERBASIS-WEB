# LAPORAN-TUGAS-APBO-SISTEM-INFORMASI-MANAJEMEN-KOS

## 👥 Anggota Kelompok 3

| Nama | NPM |
| :--- | :--- |
| Alamanda | 4522210078 |
| Lilis | 4524210051 |
| Ketut Sumantre | 4524210048 |
| Bunga Putri Nuriman | 4524210021 |
| Kornelius Timothy Setiawan | 4524210050 |


# 💬 Hasil Wawancara: Sistem Pengelolaan Kos

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

#  📋 Bagian 1: Analisis Aktor

 1. 👨‍💼 Pengelola Kos (Admin)
 
 Aktor utama yang memiliki kontrol penuh terhadap sistem dan operasional kos.

 Tugas & Tanggung Jawab: 
- Mengelola data penghuni (input, update, dan pencarian data)
- Mengelola data kamar (status kosong/terisi)
- Mencatat dan memverifikasi pembayaran kos
- Melihat rekapitulasi keuangan melalui dashboard
- Menanggapi dan mengelola keluhan dari penghuni
- Mengirim atau memantau notifikasi/pengingat pembayaran

2. 🧑‍💻 Penghuni Kos (User)

Aktor yang menggunakan layanan kos dan berinteraksi langsung dengan sistem.

Tugas & Tanggung Jawab:
- Melakukan pembayaran kos (transfer/cash)
- Mengunggah bukti pembayaran
- Melihat status pembayaran (lunas/belum)
- Mengirim keluhan terkait fasilitas kos
- Menerima notifikasi (pengingat pembayaran & informasi penting)

3. 📱 Sistem (Automated System)
Aktor non-manusia yang membantu otomatisasi proses dalam sistem.
 
Tugas & Tanggung Jawab:
- Mengirim notifikasi otomatis (misalnya pengingat pembayaran)
- Menyimpan dan mengelola database penghuni & pembayaran
- Menampilkan dashboard rekap data secara real-time
- Mencatat histori pembayaran dan keluhan
- Membantu memfilter data (siapa yang belum bayar, dll)

## ⚖️ Bagian 2: Analisis Perbandingan Sistem

Klik tiap bagian untuk melihat perbandingan sistem lama (manual) dan sistem baru (digital):

<details>
<summary><b>1.  Manajemen Data Penghuni</b></summary>
<br>

* **❌ Sistem Manual:**
    * Data disimpan dalam bentuk fisik (fotokopi KTP & KK)
    * Sulit mencari data karena tercampur dalam satu map
    * Risiko kehilangan data cukup tinggi
* **✅ Sistem Digital:**
    * Data penghuni tersimpan dalam database terpusat
    * Pencarian data cepat dan terstruktur
    * Data lebih aman dan tidak mudah hilang
</details>

<details>
<summary><b>2.  Pencatatan & Monitoring Pembayaran</b></summary>
<br>

* **❌ Sistem Manual:**
    * Pembayaran dicatat di buku tulis
    * Bukti pembayaran hanya berupa screenshot WhatsApp
    * Harus cek satu per satu untuk tahu siapa yang belum bayar
    * Rentan kesalahan pencatatan
* **✅ Sistem Digital:**
    * Pembayaran tercatat otomatis dalam sistem
    * Penghuni upload bukti langsung ke sistem
    * Status pembayaran bisa dilihat secara real-time
    * Tersedia rekap otomatis di dashboard
</details>

<details>
<summary><b>3.  Pengingat Pembayaran</b></summary>
<br>

* **❌ Sistem Manual:**
    * Pengelola harus mengingat dan menagih satu per satu
    * Sering merasa sungkan saat menagih
    * Banyak penghuni telat bayar karena lupa
* **✅ Sistem Digital:**
    * Sistem mengirim notifikasi otomatis (misal via WhatsApp)
    * Pengingat dikirim sebelum jatuh tempo
    * Mengurangi keterlambatan pembayaran
</details>

<details>
<summary><b>4.  Penanganan Keluhan</b></summary>
<br>

* **❌ Sistem Manual:**
    * Keluhan disampaikan via chat atau langsung
    * Tidak terdokumentasi dengan baik
    * Banyak keluhan terlewat atau terlupakan
* **✅ Sistem Digital:**
    * Keluhan dicatat dalam sistem
    * Ada riwayat dan tracking status keluhan
    * Pengelola lebih mudah memantau dan menindaklanjuti
</details>

<details>
<summary><b>5.  Penyampaian Informasi</b></summary>
<br>

* **❌ Sistem Manual:**
    * Menggunakan grup WhatsApp
    * Informasi sering tertumpuk dan terlewat
    * Tidak semua penghuni membaca info
* **✅ Sistem Digital:**
    * Notifikasi langsung ke masing-masing pengguna
    * Informasi lebih terstruktur dan tidak mudah hilang
    * Bisa diakses kembali kapan saja di sistem
</details>

      


