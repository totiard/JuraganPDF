# Juragan PDF - Alat Manipulasi PDF Sederhana

Selamat datang di **Juragan PDF**, sebuah aplikasi web ringkas yang dirancang untuk membantu Anda mengelola file PDF dengan mudah langsung dari browser. Aplikasi ini sepenuhnya berjalan di sisi klien (client-side), yang berarti file Anda tetap aman dan tidak diunggah ke server mana pun.

Aplikasi ini juga dilengkapi penghitung aksi (pengunjung, jumlah penggabungan, dan pemisahan) secara real-time menggunakan Firebase Firestore untuk menunjukkan seberapa sering alat ini digunakan.

**[Lihat Demo Langsung](https://totiard.github.io/Mini-Aplikasi-PDF/)** (Ganti dengan URL GitHub Pages Anda jika sudah di-hosting)

![Pratinjau Aplikasi Juragan PDF](https://placehold.co/800x450/0f172a/e0e7ff?text=Pratinjau+Juragan+PDF)

---

## ✨ Fitur Utama

Juragan PDF menawarkan dua fitur utama untuk kebutuhan PDF Anda:

### 1. Gabungkan PDF (Merge PDF)
Fitur ini memungkinkan Anda untuk menggabungkan beberapa file PDF menjadi satu dokumen tunggal.

* **Pilih Banyak File**: Pilih satu atau lebih file PDF dari komputer Anda.
* **Tambah File Lagi**: Mudah menambahkan lebih banyak file ke dalam antrean.
* **Urutkan dengan Seret & Lepas (Drag & Drop)**: Atur urutan file PDF sesuai keinginan Anda dengan menyeret kartu pratinjau.
* **Hapus File**: Hapus file yang tidak diinginkan dari daftar sebelum digabungkan.
* **Pratinjau Halaman Pertama**: Lihat pratinjau halaman pertama dari setiap PDF untuk memudahkan identifikasi.

### 2. Pisahkan PDF (Split PDF)
Fitur ini menyediakan berbagai mode fleksibel untuk memecah satu file PDF menjadi beberapa file yang lebih kecil.

* **Mode Rentang (Range Mode)**:
    * **Rentang Khusus**: Tentukan satu atau lebih rentang halaman kustom (misalnya, halaman 2-5, 8-10). Anda bisa menambahkan sebanyak mungkin rentang yang dibutuhkan.
    * **Rentang Tetap**: Pisahkan PDF menjadi beberapa file dengan jumlah halaman yang sama (misalnya, pisahkan setiap 2 halaman).
    * **Opsi Gabung Rentang**: Pilih untuk menggabungkan semua rentang yang telah Anda tentukan menjadi satu file PDF baru.

* **Mode Halaman (Page Mode)**:
    * **Ekstrak Semua Halaman**: Ubah setiap halaman dari PDF menjadi file PDF terpisah.
    * **Pilih Halaman Tertentu**: Ekstrak halaman spesifik dengan mengetikkan nomornya (misalnya, 1, 3, 7) atau dengan mengklik pratinjau halaman secara visual.
    * **Opsi Gabung Halaman Terpilih**: Gabungkan semua halaman yang Anda pilih menjadi satu file PDF.

* **Unduh sebagai ZIP**: Jika hasil pemisahan menghasilkan lebih dari satu file, aplikasi akan secara otomatis mengemasnya dalam sebuah file `.zip` untuk kemudahan pengunduhan.

---

## 🛠️ Teknologi yang Digunakan

* **HTML5 & CSS3**: Struktur dan gaya dasar aplikasi.
* **Tailwind CSS**: Kerangka kerja CSS untuk desain antarmuka yang modern dan responsif.
* **JavaScript (ES6+)**: Logika inti aplikasi yang berjalan di browser.
* **[pdf-lib.js](https://pdf-lib.js.org/)**: Pustaka untuk membuat dan memodifikasi dokumen PDF. Digunakan untuk proses penggabungan dan pemisahan inti.
* **[PDF.js](https://mozilla.github.io/pdf.js/)**: Pustaka yang dikembangkan oleh Mozilla untuk merender dan menampilkan pratinjau file PDF di dalam elemen `<canvas>`.
* **[JSZip](https://stuk.github.io/jszip/)**: Pustaka untuk membuat, membaca, dan mengedit file `.zip` dengan JavaScript.
* **[Firebase Firestore](https://firebase.google.com/docs/firestore)**: Digunakan untuk fitur penghitung aksi (pengunjung, gabung, pisah) secara real-time.

---

## 🚀 Cara Menjalankan Secara Lokal

Anda tidak memerlukan server web untuk menjalankan aplikasi ini. Cukup ikuti langkah-langkah berikut:

1.  **Clone repositori ini:**
    ```bash
    git clone [https://github.com/USERNAME/NAMA-REPOSITORI.git](https://github.com/USERNAME/NAMA-REPOSITORI.git)
    ```
2.  **Buka direktori proyek:**
    ```bash
    cd NAMA-REPOSITORI
    ```
3.  **Buka file `index.html`:**
    Cukup klik dua kali file `index.html` atau buka langsung melalui browser Anda.

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah Lisensi MIT. Lihat file `LICENSE` untuk detailnya.

---

## 👨‍💻 Dibuat oleh

* **Toti Ardiansyah** - [GitHub](https://github.com/totiard)
