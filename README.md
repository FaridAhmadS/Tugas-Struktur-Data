
🧠 Praktikum Struktur Data ADT Array & Conway’s Game of Life Simulation in Python

📌 Project Overview

Project ini merupakan implementasi:

✅ Abstract Data Type (ADT) Array

✅ Simulasi Conway’s Game of Life

✅ Konsep OOP (Object-Oriented Programming)

✅ Manipulasi Grid 2D

✅ Deep Copy & Iterasi

Project dibuat sebagai bagian dari praktikum mata kuliah Struktur Data.

📂 Project Structure praktikum-struktur-data/ │ ├── array.py # Implementasi ADT Array ├── game_of_life.py # Simulasi Game of Life └── README.md # Dokumentasi project

🧩 1️⃣ ADT Array Implementation 📖 Deskripsi

Kelas Array merupakan implementasi array dengan ukuran tetap (fixed size) yang memiliki fitur:

Konstruktor validasi ukuran

Akses index dengan validasi

Modifikasi elemen

Clear semua elemen

Support iterasi dengan iter

Mendukung fungsi len()

⚙️ Method Overview Method Fungsi init(size) Membuat array dengan ukuran tetap len() Mengembalikan panjang array getitem(index) Mengambil nilai berdasarkan index setitem(index, value) Mengubah nilai pada index clear(value) Mengisi seluruh array dengan nilai tertentu iter() Agar bisa digunakan dalam perulangan 💻 Contoh Output ADT Array Panjang array: 5

Isi array setelah diisi: 10 20 30 None None

Nilai pada index 1: 20

Isi array setelah clear: 0 0 0 0 0

🎮 2️⃣ Conway’s Game of Life 📖 Deskripsi

Game of Life adalah simulasi otomatis berbasis grid 2D yang mengikuti aturan matematika sederhana untuk menentukan apakah sel hidup atau mati di generasi berikutnya.

Ukuran grid: 5 x 5 Jumlah generasi: 5 Delay antar generasi: 1 detik

📜 Aturan Game of Life

Sel hidup dengan < 2 tetangga → mati (Underpopulation)

Sel hidup dengan 2 atau 3 tetangga → tetap hidup

Sel hidup dengan > 3 tetangga → mati (Overpopulation)

Sel mati dengan tepat 3 tetangga → menjadi hidup (Reproduction)

🖥 Contoh Tampilan di Terminal Generasi: 0 . . . . . . ■ ■ ■ . . . ■ . . . . . . . . . . . .

Generasi: 1 . . ■ . . . . ■ . . . ■ ■ . . . . . . . . . . . .

(Simulasi terus berjalan hingga generasi ke-4)

▶️ Cara Menjalankan Project 1️⃣ Clone Repository git clone [https://github.com/FaridAhmadS/praktikum-struktur-data.git
](https://github.com/FaridAhmadS/Tugas-Struktur-Data/edit/main/README.md)
2️⃣ Masuk ke Folder cd praktikum-struktur-data

3️⃣ Jalankan Program

Untuk ADT Array:

python array.py

Untuk Game of Life:

python game_of_life.py

🛠 Technologies Used

Python 3

Object-Oriented Programming

Deep Copy (copy.deepcopy)

Time Delay (time.sleep)

2D Grid Iteration

🎯 Learning Objectives

Memahami konsep Abstract Data Type (ADT)

Mengimplementasikan array dengan ukuran tetap

Menggunakan method khusus Python (len, getitem, dll)

Mengimplementasikan simulasi berbasis aturan matematis

Melatih logika dan pemodelan sistem

👨‍💻 Author
FARID AHMAD SANTOSO 25091397050 2025B
