# 🧠🚀 Deteksi Objek dan Pelacakan Langsung Menggunakan YOLOv12 🎥✨

Selamat datang di proyek saya mengenai **Deteksi Objek dan Pelacakan Real-Time** menggunakan **YOLOv12**!  
YOLO (You Only Look Once) adalah salah satu model deteksi objek tercepat dan terakurat, dan pada proyek ini saya telah menggabungkannya dengan pelacakan video secara langsung menggunakan **OpenCV** dan **CSRT Tracker**.

---

## 🔥 Apa yang Dilakukan Proyek Ini?

Proyek ini menggabungkan deteksi dan pelacakan objek secara real-time:

1. 🧠 YOLOv12 mendeteksi objek dalam setiap frame video.
2. 🖱️ Pengguna bisa klik pada objek untuk mulai pelacakan.
3. 🎯 Sistem melacak objek tersebut secara dinamis dari frame ke frame menggunakan CSRT Tracker.

---

## 🌟 Mengapa Menggunakan YOLOv12?

Versi terbaru dari YOLO, yaitu **YOLOv12**, baru saja dirilis 4 hari lalu!  
Model ini hadir dengan peningkatan yang signifikan:

- ⚡ **Kecepatan Tinggi** – Cocok untuk aplikasi real-time.
- 🧠 **Akurasi Tinggi** – Deteksi lebih akurat dibanding versi sebelumnya.
- 📊 **Fleksibel** – Telah dilatih menggunakan dataset COCO, sehingga mampu mengenali 80+ kelas objek umum.

---

## 📊 Performa YOLOv12

Perbandingan metrik performa terhadap versi sebelumnya:

![Performance](https://github.com/user-attachments/assets/d31e482c-6d5d-4271-932a-d042cc0ddc67)

---

## 📦 Tentang Dataset COCO

Dataset **COCO (Common Objects in Context)** adalah standar industri untuk pelatihan model deteksi objek.  
Beberapa contoh kategori objek yang dapat dikenali:

- 🏃 Orang
- 🚗 Mobil
- 🐶 Anjing
- 📱 Ponsel
- 🍕 Pizza  
...dan masih banyak lagi.

Saya menggunakan dataset ini karena fleksibilitas dan kecocokannya untuk aplikasi deteksi umum.

---

## 🔧 Cara Kerja Sistem

1. **Tangkap Video Langsung** 🎥 menggunakan OpenCV.
2. **Deteksi Objek** dengan YOLOv12.
3. **Klik Objek** untuk memulai pelacakan.
4. **Pelacakan Dinamis** menggunakan CSRT frame demi frame.

---

## 🚀 Teknologi yang Digunakan

- `YOLOv12` – Deteksi objek berbasis deep learning.
- `OpenCV` – Pengolahan video dan input kamera.
- `CSRT Tracker` – Pelacak visual berbasis bounding box.

---

## 🔗 Fitur Utama

- 💻 Deteksi dan pelacakan **real-time**
- 🖱️ Pemilihan objek secara **interaktif**
- 🔁 Pelacakan yang **akurat dan stabil**
- 🧩 Mudah diperluas ke dataset khusus jika diperlukan

---

## 🛠️ Cara Menjalankan

1. Clone repository dan pastikan dependensi terinstal.

2. Jalankan skrip Python.

3. Gunakan jendela feed video live untuk memilih objek dengan mengkliknya.

4. Saksikan sistem melacak objek yang Anda pilih secara real-time!

---

## Demo 📽

[![Demo Video](https://img.youtube.com/vi/ZmmIUGCnj5U/0.jpg)](https://www.youtube.com/watch?v=ZmmIUGCnj5U)

📽️ [Tonton Demo di YouTube](https://www.youtube.com/watch?v=ZmmIUGCnj5U)


