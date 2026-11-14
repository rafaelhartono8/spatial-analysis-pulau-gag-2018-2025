# 🛰️ MATA AI DI LANGIT RAJA AMPAT
**Analisis Perubahan Fungsi Lahan di Pulau Gag Periode 2018–2025 dengan Algoritma Random Forest**

Proyek analisis geospasial ini memanfaatkan citra satelit **Sentinel-2 (A & B)** pada **Google Earth Engine (GEE)** serta algoritma *machine learning* **Random Forest** untuk memantau dampak aktivitas pertambangan dan perubahan tutupan lahan di Pulau Gag, Raja Ampat.

---

## 🌍 Latar Belakang: Mengapa Harus Citra Satelit?

![Latar Belakang 1](./Latar%20Belakang%201.png)

Pada sisi kiri merupakan tampilan *default* dari Google Maps. Kita mungkin bisa dengan mudah mengukur panjang sebuah meja dengan penggaris, luas lantai keramik dengan penggaris, atau luas sebuah rumah dengan laser pengukur jarak, tetapi **bagaimana cara mengukur luas seukuran pulau?**

Lalu, kenapa tidak menggunakan tampilan satelit dari Google Maps saja? Pada sisi kanan gambar di atas, citra satelit Google Maps memang terlihat bersih dari awan, tetapi memiliki resolusi analisis yang terbatas dan jika kalian teliti kalian dapat beberapa area tertentu yang disensor dengan *blur*. Oleh karena itu, dibutuhkan data citra satelit multispektral mentah seperti **Sentinel-2** agar setiap piksel ($10\text{ m} \times 10\text{ m}$) dapat dianalisis secara objektif dan akurat.

---

## 🐢 Surga yang Terancam

![Latar Belakang 2](./Latar%20Belakang%202.png)

Siapa di sini yang pernah mendengar julukan **Pulau Surga**? Melalui potret di atas, tidak salah jika Raja Ampat disebut sebagai surganya flora dan fauna—gugusan kepulauan yang memukau, penyu raksasa, hingga pari manta raksasa hidup berdampingan dalam ekosistem yang sangat indah.

![Latar Belakang 3](./Latar%20Belakang%203.png)

Namun, keindahan itu terancam tidak lama lagi akan lenyap. Terlihat kumpulan ikan yang berenang di sekitar rongsokan besi, terumbu karang dengan latar belakang alat berat dan mesin, hingga pulau-pulau kecil yang beralih fungsi menjadi area pertambangan. Sedih sekali, bukan? 😢

> **Kira-kira, setelah melihat kenyataan ini, langkah nyata apa yang akan kalian lakukan?**  
> Bagi kami, langkah pertama adalah menghadirkan bukti berbasis data yang transparan dan tidak terbantahkan melalui pemantauan satelit dan kecerdasan buatan.

---

## ☁️ Mengapa Menggunakan Puluhan Data Gambar?

![Contoh Data Kotor](./data%20kotor.png)

Mengapa kami mengumpulkan **78 citra** pada periode 2018–2019 dan **104 citra** pada periode 2024–2025, alih-alih langsung memilih 1 gambar saja?

Karena wilayah tropis seperti Raja Ampat sangat sering tertutup awan tebal. Jika hanya mengambil 1 gambar tunggal, data yang didapat akan penuh gangguan awan dan bayangan seperti pada gambar di atas. Dengan menggabungkan puluhan citra (*image compositing*) dan menerapkan *cloud masking*, kita bisa mendapatkan tampilan permukaan Pulau Gag yang bersih untuk diklasifikasikan.

---

## 📊 Infografis & Temuan Utama

![Infografis Mata AI di Langit Raja Ampat](./MATA%20AI%20DI%20LANGIT%20RAJA%20AMPAT.png)

### Ringkasan Hasil Analisis (2018–2025):
* **Ekspansi Area Tambang lebih dari 2x Lipat:** Luas area pertambangan melonjak **+141,5%**, dari **128,1 Ha** (2018–2019) menjadi **307,3 Ha** (2024–2025)
* **Peningkatan Perairan Keruh:** Luas area air yang diduga keruh di sekitar pesisir pulau meningkat sebesar **+117.4%** dari **166.7 Ha** (2018–2019) menjadi **307.1 Ha** (2024–2025) yang berpotensi mengancam ekosistem terumbu karang dan perikanan lokal
* **Proyeksi Masa Depan:** Jika laju pertumbuhan area pertambangan berlangsung konstan tanpa pengendalian, seluruh area vegetasi di Pulau Gag diprediksi **akan habis sebelum tahun 2208**.

---

## 📄 Dokumen & Tim Penyusun

* 📑 **Karya Tulis Ilmiah (PDF):** [Baca KTI Lengkap di Sini](./KTI_MATA%20AI%20DI%20LANGIT%20RAJA%20AMPAT.pdf)
* 🎓 **Program Studi:** S1 Sains Data — Universitas Negeri Surabaya
* 👥 **Anggota Tim:**
  * **Rafael Hartono** (`24031554166`)
  * **Satya Apta Mahardika** (`24031554024`)
  * **Muhammad Arief Firmansyah** (`24031554059`)
  * **Naufal Muzaki** (`24031554061`)
  * **Yazid Husain Abdurrahman** (`24031554076`)
