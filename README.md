# lab4_layoutdzalhari
bismilah sukses 
Laporan Praktikum 4: CSS Layout
Mata Kuliah: Pemrograman Web
Dosen Pengampu: Agung Nugroho
Institusi: Universitas Pelita Bangsa
📌 Daftar Isi
Tujuan Praktikum
Langkah-Langkah Praktikum & Penjelasan
Part 1: Box Element & CSS Float Property
Part 2: Mengatur Clearfix Elemen
Part 3: Membuat Layout Sederhana
Tugas dan Latihan
1. Halaman About (about.html)
2. Halaman Contact (kontak.html)
Kesimpulan
🎯 Tujuan Praktikum
Mahasiswa mampu memahami struktur dasar pembuatan Layout Web.
Mahasiswa mampu memahami konsep Box Element (Margin, Border, Padding, dan Content).
Mahasiswa mampu memahami dan mengimplementasikan CSS Floating (float dan clear).
Mahasiswa mampu memahami dan memanfaatkan HTML5 Semantic Elements (<header>, <nav>, <section>, <aside>, <footer>, dll).
Mahasiswa mampu membuat Layout Web Sederhana yang responsif dan terstruktur.
🚀 Langkah-Langkah Praktikum & Penjelasan
Part 1: Box Element & CSS Float Property
Pada tahap awal praktikum ini, kita mempelajari bagaimana elemen <div> berperan sebagai Box Element dan bagaimana properti float dapat mengubah tata letak default elemen dari vertikal (block) menjadi horizontal.
1. Kode HTML & CSS (lab4_box.html)
![alt text](<img width="1600" height="899" alt="lab4_layoutdzalhari" src="https://github.com/user-attachments/assets/3df7eca0-758c-4dfa-8737-7e2d6730dd8a" />?raw=true)
2. Penjelasan Detail Langkah PraktikumBlock-level Element: Secara bawaan (default), elemen <div> bersifat block element, yang berarti elemen tersebut mengambil lebar penuh ($100\%$) dan memaksa elemen di bawahnya berpindah ke baris baru.Properti float: left: Dengan menambahkan aturan float: left; pada CSS, alur kerja normal dokumen diabaikan. Elemen Div 1, Div 2, dan Div 3 akan melayang (float) ke arah kiri dan saling berdampingan secara horizontal dari kiri ke kanan.Ruang Dalam (padding): padding: 10px; diberikan untuk memberi jarak antara isi teks dengan tepi batas masing-masing elemen <div>.
![alt text](<img width="1600" height="899" alt="WhatsApp Image 2026-10-18 at 14 03 49" src="https://github.com/user-attachments/assets/feac3fc3-ae45-434c-baa9-25c5bd6a8daa" />?raw=true)
3. Tangkapan Layar (Screenshot) Hasil Tampilan
(Ganti URL gambar di atas dengan screenshot file lab4_box.html dari browser Anda)
Part 2: Mengatur Clearfix Element
Saat menggunakan properti float, elemen-elemen setelahnya akan berpotensi ikut melayang atau naik ke ruang kosong yang ada di sebelahnya. Untuk menghentikan efek float ini, digunakan properti clear.
1. Penambahan Kode div4 dan CSS Clearfix
![alt text](<img width="1600" height="898" alt="WhatsApp Image 2026-10-18 at 14 45 12" src="https://github.com/user-attachments/assets/88870c09-aaac-4bd1-827c-a14abc5fb67f" />?raw=true)
2. Penjelasan Detail Langkah Praktikum
Masalah Tanpa clear: Tanpa adanya clear, Div 4 akan menempati area kosong di sebelah kanan Div 3.
Fungsi clear: left: Properti clear: left; memberitahu browser agar Div 4 tidak berada di samping elemen mana pun yang memiliki properti float: left. Sebaliknya, Div 4 secara paksa dipindahkan ke baris baru tepat di bawah barisan floating elements.
Penggunaan float: none: Memastikan Div 4 kembali mengikuti perilaku normal tata letak (normal flow).
![alt text](<img width="1600" height="899" alt="WhatsApp Image 2026-10-18 at 14 45 25" src="https://github.com/user-attachments/assets/1beffe0c-ef63-48be-bdc5-f60fbe7df4a7" />?raw=true)
![alt text](<img width="1600" height="899" alt="WhatsApp Image 2026-10-18 at 14 46 49" src="https://github.com/user-attachments/assets/1a09cdc3-fecb-4950-8144-b5b4c503837a" />?raw=true)
![alt text](<img width="1600" height="899" alt="WhatsApp Image 2026-10-18 at 14 47 04" src="https://github.com/user-attachments/assets/dae36594-e641-4795-95f9-e38b554f20b0" />?raw=true)
![alt text](<img width="1600" height="901" alt="WhatsApp Image 1" src="https://github.com/user-attachments/assets/77e45d99-df36-44a6-87d0-1f24673800a9" />?raw=true)
![alt text](<img width="1600" height="900" alt="WhatsApp Image 2" src="https://github.com/user-attachments/assets/b83e32cc-ace5-4440-b723-9c7bbadd3a42" />?raw=true)
