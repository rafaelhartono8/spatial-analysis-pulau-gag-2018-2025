# 🛰️ Mata AI di Langit Raja Ampat: Analisis Spasial Pulau Gag (2018–2025)

Pemantauan perubahan fungsi lahan di **Pulau Gag, Raja Ampat** menggunakan citra satelit **Sentinel-2** dan algoritma **Random Forest** pada platform **Google Earth Engine (GEE)**.

---

## 🌍 Latar Belakang

### 1. Mengukur Pulau dari Langit
![Latar Belakang 1](Latar%20Belakang%201.png)

Pada sisi kiri merupakan tampilan *default* dari Google Maps yang biasa kita gunakan sehari-hari. Kita mungkin bisa dengan mudah mengukur sebidang meja, sehelai baju, atau luas sebuah rumah—**tapi bagaimana cara mengukur perubahan sebuah pulau secara menyeluruh?**

**Kenapa harus memakai satelit dan bukan sekadar gambar Google Maps? (Sisi Kanan)**  
Tampilan Google Maps standar hanya menyajikan foto visual warna tampak (*RGB*) statis tanpa kontrol periode waktu yang presisi. Sebaliknya, citra satelit multispektral seperti **Sentinel-2** mampu merekam pantulan gelombang cahaya yang tidak terlihat oleh mata manusia (seperti spektrum inframerah untuk membaca kesehatan vegetasi, tingkat kekeruhan perairan, hingga indeks kandungan besi) serta memiliki arsip deret waktu (*time-series*) yang konsisten untuk membandingkan kondisi masa lalu dan masa kini secara terukur.

---

### 2. Pesona "Pulau Surga"
![Latar Belakang 2](Latar%20Belakang%202.png)

Siapa di sini yang pernah mendengar julukan **Pulau Surga**? Melalui potret ini, tidak salah bukan jika kawasan ini disebut sebagai surganya flora dan fauna? Gugusan kepulauan hijau yang asri, penyu raksasa, hingga pari manta raksasa hidup berdampingan dalam ekosistem laut yang sangat indah.

---

### 3. Ancaman di Balik Keindahan
![Latar Belakang 3](Latar%20Belakang%203.png)

Namun, keindahan itu terancam tidak lama lagi akan lenyap. Terlihat kumpulan ikan yang kini berenang di sekitar rongsokan besi, terumbu karang dengan latar belakang alat berat mesin, serta pulau-pulau kecil yang berubah menjadi kawasan pertambangan. Sedih sekali, bukan? 😢

---

## 📊 Hasil Analisis & Infografis

![Infografis Mata AI di Langit Raja Ampat](MATA%20AI%20DI%20LANGIT%20RAJA%20AMPAT.png)

### Ringkasan Singkat
* **Data & Metode:** Mengolah **78 citra** Sentinel-2 (periode 2018–2019) dan **104 citra** (periode 2024–2025) dengan resolusi spasial `10m × 10m` per piksel menggunakan klasifikasi **Random Forest** (*100 decision trees*, akurasi *Kappa* ~98%).
* **Ekspansi Tambang:** Luas area pertambangan meningkat **141,2%** (dari `138,1 Ha` menjadi `337,2 Ha`).
* **Dampak Perairan:** Area air keruh di sekitar pesisir pulau melonjak **117,4%** (dari `141,7 Ha` menjadi `307,1 Ha`).
* **Proyeksi Keberlanjutan:** Jika laju pertumbuhan area tambang berlangsung konstan tanpa pengendalian, seluruh tutupan vegetasi di Pulau Gag diprediksi habis sebelum tahun **2208**.

📄 **Kajian Lengkap:** Baca naskah lengkap penelitian di [KTI_MATA AI DI LANGIT RAJA AMPAT.pdf](./KTI_MATA%20AI%20DI%20LANGIT%20RAJA%20AMPAT.pdf).

---

> 💭 **Setelah melihat data dan potret nyata di atas, kira-kira langkah apa yang akan kalian lakukan setelah ini?**

---

## 👥 Tim Penyusun (Kelompok 07 — S1 Sains Data, UNESA)
* **Rafael Hartono** (24031554166)
* **Satya Apta Mahardika** (24031554024)
* **Muhammad Arief Firmansyah** (24031554059)
* **Naufal Muzaki** (24031554061)
* **Yazid Husain Abdurrahman** (24031554076)
