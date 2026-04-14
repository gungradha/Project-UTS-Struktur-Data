# Project-UTS-Struktur-Data

# 🚗 Sistem Antrian Parkir (Circular Queue)

## 📌 Deskripsi

Queue atau antrian adalah sekumpulan data yang penambahan elemennya dilakukan melalui satu sisi (rear) dan penghapusan elemennya dilakukan melalui sisi lainnya (front). Konsep ini mengikuti prinsip FIFO (First-In First-Out), di mana elemen yang pertama kali masuk akan menjadi yang pertama kali keluar, mirip dengan antrian kendaraan di gerbang parkir. 

Program ini merupakan implementasi **struktur data dengan Circular Queue** yang  menggunakan bahasa Python untuk mensimulasikan sistem antrian parkir pada area luas seperti hotel atau restoran.

Konsep utama yang digunakan adalah **FIFO (First In First Out)**, di mana kendaraan yang masuk terlebih dahulu akan keluar terlebih dahulu.

---

## 🖼️ Flowchart Sistem

![Flowchart](images/flowchart.png)

---

## 🔁 Diagram Circular Queue

![Circular Queue](https://github.com/niaparamita/project-tugas/blob/6e07a62de4c7a0b47dbb0b04fd674a3f430d64f6/Antrian%20Melingkar%20pada%20Sistem%20Parkir.png)

---

## 🧠 Konsep yang Digunakan

* Queue (Antrian)
* Circular Queue (Queue Melingkar)
* FIFO (First In First Out)
* Array (List Python)
* Waktu real-time (datetime)

---

## ⚙️ Fitur Program

* ✅ Enqueue (Masuk)
* ✅ Dequeue (Keluar)
* ✅ Peek
* ✅ Display
* ✅ Waktu masuk & keluar
* ✅ Perhitungan biaya parkir

---

## 💻 Teknologi

* Python 3
* Visual Studio Code

---

## ▶️ Cara Sistem Bekerja

Alur kerja sistem dimulai dengan input kapasitas parkir, kemudian program menampilkan menu utama untuk dipilih pengguna.

Proses utamanya yaitu:

Enqueue: Menambahkan kendaraan ke antrian dan mencatat waktu masuk jika kapasitas belum penuh.
Dequeue: Mengeluarkan kendaraan terdepan, menghitung durasi parkir, dan menentukan biaya.
Peek: Menampilkan kendaraan paling depan tanpa menghapus data.
Display: Menampilkan seluruh kendaraan dalam antrian.

Seluruh proses yang terjadi pada program menggunakan operasi modulo supaya menjaga sifat melingkar pada circular queue.

Biaya parkir akan dihitung dengan berdasarkan lama waktu kendaraan berada di area parkir, yaitu selisih antara waktu masuk dan waktu keluar yang dikonversi ke dalam satuan jam.

## 📊 Keunggulan

* Lebih efisien (circular queue)
* Tidak ada pergeseran data
* Simulasi nyata sistem parkir

---

## 👨‍💻 Author

* Nama: (NI MADE NIA PARAMITA (2501010376) )
* Nama: (NI PUTU VIRA ARTIKA DEWI (2501010377) )
* Nama: (ANAK AGUNG RADHA NOVIANTI (2501010378) )

---
