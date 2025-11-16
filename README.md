# 📊 Mental Health Analysis During Isolation

**Proyek Data Analyst menggunakan Python & Looker Studio**

---

## 📁 Ringkasan Proyek

Proyek ini menganalisis bagaimana durasi berada di dalam rumah, riwayat keluarga, serta tingkat stres memengaruhi kondisi kesehatan mental seseorang selama masa isolasi.
Analisis dilakukan menggunakan **Python** untuk eksplorasi data dan **Looker Studio** untuk pembuatan dashboard interaktif.

---
🔗 Dashboard Interaktif

Dashboard dapat diakses melalui link berikut:

👉 Klik untuk membuka Dashboard Looker Studio

https://lookerstudio.google.com/reporting/e32813a8-9ff0-49f6-a0bc-b4aa8ea861bb

---

## 🎯 Tujuan Proyek

* Mengetahui hubungan antara **DaysIndoors** dan tingkat **IncreasingStress**
* Menganalisis pengaruh **FamilyHistory** terhadap kondisi mental
* Mengidentifikasi bagaimana stres memengaruhi:

  * Mood Swings
  * Work Interest
  * Coping Struggles
  * Social Weakness

---

## 📊 Informasi Dataset

* **Sumber:** Kaggle – Mental Health Dataset (https://www.kaggle.com/datasets/alamshihab075/mental-health-dataset)
* **Jumlah Data:** ± 261.000 baris
* **Jumlah Kolom Setelah Cleaning:** 16
* **Tipe Data:** Kategorikal & Numerikal
* **Negara Terkait:** USA, UK, India, Australia, Canada, dll.

### Fitur Utama

* **Demografi:** Gender, Country, Occupation
* **Perilaku & Kebiasaan:** DaysIndoors, HabitsChange, CopingStruggles
* **Indikator Mental:** MentalHealthHistory, IncreasingStress, MoodSwings
* **Dukungan:** CareOptions, MentalHealthInterview

---

## 🧹 Pembersihan Data

Tahapan penting dalam proses data cleaning:

- Menghapus kolom duplikat `SocialWeakness.1`
- Mengisi missing value pada `SelfEmployed` → `"Unknown"`
- Menstandarkan kategori Yes/No/Maybe
- Menghapus spasi yang tidak diperlukan
- Memastikan konsistensi format pada seluruh kolom

---

## 🔍 Exploratory Data Analysis (EDA)

### 1️⃣ **Days Indoors vs Increasing Stress**

| Durasi             | Persentase Stres (Yes) |
| ------------------ | ---------------------- |
| 1–14 hari          | 34.14%                 |
| 15–30 hari         | 35.07%                 |
| 31–60 hari         | 34.34%                 |
| Keluar setiap hari | **29.45%**             |
| > 2 bulan          | **36.41%**             |

📌 **Insight Utama:** Semakin lama berada di dalam rumah → tingkat stres semakin meningkat.

---

### 2️⃣ **Family History vs Mental Health History**

Proporsi responden yang memiliki riwayat keluarga dan tidak hampir seimbang.

📌 **Insight:** Riwayat keluarga **tidak terlalu memengaruhi** kondisi mental responden pada dataset ini.

---

### 3️⃣ **Dampak Stres pada Faktor Lain**

* **Mood Swings:** Tingkat stres tinggi → mood tidak stabil
* **Work Interest:** Semakin stres → minat kerja menurun
* **Coping Struggles:** Stres tinggi → lebih sulit mengatasi tekanan
* **Social Weakness:** Peningkatan ringan saat stres meningkat

📌 **Insight:** Stres lebih berdampak pada **emosi dan kemampuan coping** dibanding faktor sosial.

---

## 🧠 Kesimpulan Utama

1. **Durasi isolasi panjang memicu peningkatan stres yang signifikan.**
2. **Riwayat keluarga bukan faktor dominan** dalam kondisi mental individu.
3. **Stres berdampak besar** pada mood, motivasi kerja, dan kemampuan mengatasi masalah.

---

## 📊 Dashboard Looker Studio

Dashboard berisi visualisasi interaktif:

* Total Stress Count
* Days Indoors vs Stress
* Mood Swings
* Work Interest
* Coping Struggles
* Social Weakness
* Family History Analysis

> Dibangun menggunakan Looker Studio dengan filter dinamis (Yes/No/Maybe).

---

## 🛠️ Tools yang Digunakan

* **Python:** Pandas, Matplotlib, Seaborn
* **Looker Studio:** Dashboarding
* **Jupyter Notebook:** Analisis EDA
* **GitHub:** Dokumentasi proyek

---

## 🚀 Cara Menjalankan

1. Clone repository
2. Buka notebook untuk melihat analisis data
3. Akses dashboard Looker Studio menggunakan link yang disediakan
4. Gunakan filter pada dashboard untuk eksplorasi data lebih dalam

---

## ✨ Ringkasan Singkat

Analisis ini memberikan gambaran bagaimana stres dan masa isolasi memengaruhi kondisi mental seseorang. Proyek ini mencakup **EDA lengkap + dashboard interaktif**, cocok sebagai portofolio Data Analyst.

---

## 🧑‍💻 Author
* Putri Danty Apriani
* Fresh Graduate – Sistem Komputer, Universitas Sriwijaya
* Fokus pada Data Analyst, Python, dan Business Intelligence
* Berpengalaman dalam pembuatan EDA, dashboard interaktif, dan proyek analisis data.

---
