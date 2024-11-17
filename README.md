# 🚀 Aplikasi GUI Perhitungan Hari

Selamat datang di proyek ini! 🎉 Proyek ini adalah implementasi GUI berbasis Java untuk menghitung jumlah hari dalam suatu bulan, dengan fitur tambahan seperti menampilkan informasi hari pertama dan terakhir dalam bulan tersebut, serta menghitung selisih hari antara dua tanggal.

---

## 👨‍💻 Tentang Saya

Halo! Nama saya **Nur Yoga Andika** 👋  
- 📚 **NPM:** 2210010652  
- 🎓 **Jurusan:** Teknologi Informasi  
- 🌟 Saya selalu berusaha belajar hal-hal baru dan berbagi apa yang saya pelajari.  

💬 Jangan ragu untuk menghubungi saya untuk berdiskusi lebih lanjut tentang proyek ini atau topik lainnya! 🚀  

---

## 📝 Deskripsi Program

Aplikasi ini memungkinkan pengguna:
1. Memilih **bulan** menggunakan `JComboBox`.
2. Memasukkan **tahun** menggunakan `JSpinner` atau **JCalendar**.
3. Menekan tombol:
   - **Hitung:** Untuk menampilkan jumlah hari dalam bulan yang dipilih.
   - **Hapus:** Untuk menghapus input dan memulai dari awal.
   - **Keluar:** Untuk menutup aplikasi dengan mudah.

Aplikasi ini juga menyediakan fitur tambahan seperti:
- Informasi tentang hari pertama dan terakhir dalam bulan tersebut.
- Perhitungan selisih hari antara dua tanggal.

---

## 💻 Komponen GUI

Berikut adalah komponen utama yang digunakan dalam aplikasi ini:
- **JFrame:** Sebagai jendela utama aplikasi.
- **JPanel:** Mengatur tata letak komponen GUI.
- **JLabel:** Menampilkan label teks.
- **JComboBox:** Untuk memilih bulan.
- **JSpinner:** Untuk memasukkan tahun.
- **JCalendar:** Alternatif untuk memilih bulan dan tahun.
- **JButton:** Untuk melakukan tindakan seperti hitung, hapus, dan keluar.

---

## 🔍 Logika Program

1. **Perhitungan Hari dalam Bulan:**
   - Menggunakan `LocalDate` untuk menentukan jumlah hari dalam bulan.
   - Menentukan apakah tahun yang dimasukkan adalah tahun kabisat.
   
2. **Penggunaan API Tanggal:**
   - `LocalDate` untuk manipulasi tanggal.
   - Menampilkan hari pertama dan terakhir dalam bulan.

3. **Selisih Hari:**
   - Menggunakan API tanggal untuk menghitung jumlah hari antara dua tanggal.

---

## 🎯 Events yang Diimplementasikan

1. **ActionListener:**  
   - Untuk tombol **Hitung**, memproses perhitungan jumlah hari dalam bulan.  
   - Untuk tombol **Hapus**, menghapus semua input pengguna.
   - Untuk tombol **Keluar**, menutup aplikasi.

2. **ChangeListener:**  
   - Menggunakan `JSpinner` untuk mendeteksi perubahan tahun.

---

## ✨ Variasi

1. Memberikan informasi tambahan:
   - Hari pertama dan terakhir dalam bulan yang dipilih.
2. Perhitungan selisih hari:
   - Menghitung jumlah hari antara dua tanggal yang dipilih.
3. Validasi input:
   - Menampilkan pesan kesalahan jika input kosong atau tidak valid.

---

## 🔧 Cara Menggunakan Program

1. Pilih **bulan** menggunakan `JComboBox`.
2. Masukkan **tahun** menggunakan `JSpinner` atau pilih tanggal menggunakan `JCalendar`.
3. Tekan tombol:
   - **Hitung:** Untuk melihat jumlah hari dalam bulan yang dipilih.
   - **Hapus:** Bersihkan semua input dan mulai dari awal.
   - **Keluar:** Tutup aplikasi dengan mudah.
4. Informasi tambahan tentang hari pertama dan terakhir dalam bulan akan ditampilkan di bidang yang telah disediakan.
5. Untuk menghitung selisih hari, pilih dua tanggal menggunakan `JCalendar`.

---

