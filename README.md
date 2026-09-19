# Analisis Sentimen dan Persepsi Publik terhadap Pemotongan Anggaran Inpres 1/2025 di Media Sosial

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-Sentiment%20Analysis-4B8BBE?style=flat)
![YouTube](https://img.shields.io/badge/Data%20Source-YouTube-FF0000?style=flat&logo=youtube&logoColor=white)
![Status](https://img.shields.io/badge/Project-Completed-success?style=flat)
> Collaborative Project — Data Analyst & Researcher

## Project Overview

Instruksi Presiden (Inpres) No. 1 Tahun 2025 mengenai efisiensi anggaran belanja pemerintah pusat dan daerah memunculkan berbagai respons dari masyarakat Indonesia di media sosial. Media sosial menjadi salah satu ruang utama bagi masyarakat untuk menyampaikan pendapat, kritik, dukungan, maupun kekhawatiran terhadap suatu kebijakan. Oleh karena itu, analisis sentimen dan persepsi publik dilakukan untuk memahami bagaimana masyarakat merespons kebijakan efisiensi anggaran tersebut.

> Project ini merupakan collaborative project yang berfokus pada pengolahan dan analisis data teks dari komentar YouTube untuk mengidentifikasi pola sentimen, topik pembahasan, serta persepsi publik terhadap kebijakan efisiensi anggaran.

### Tujuan

Project ini bertujuan untuk:

1. Mengidentifikasi isu-isu utama yang muncul dalam pembahasan mengenai Inpres No. 1 Tahun 2025.
2. Menganalisis sentimen publik terhadap kebijakan efisiensi anggaran.
3. Mengidentifikasi respons publik terhadap berbagai isu yang berkaitan dengan kebijakan tersebut.
4. Menggambarkan ekspektasi dan kekhawatiran publik terhadap implementasi kebijakan efisiensi anggaran.

---

## Research Questions

Beberapa pertanyaan yang ingin dijawab melalui analisis ini adalah:

- Apa isu utama yang banyak dibahas publik terkait Inpres No. 1 Tahun 2025?
- Bagaimana sentimen publik terhadap kebijakan efisiensi anggaran?
- Bagaimana respons publik terhadap berbagai isu yang muncul?
- Apa ekspektasi publik terhadap implementasi kebijakan efisiensi anggaran?

---

## Data Collection

Data yang digunakan dalam project ini berupa komentar publik dari YouTube yang membahas kebijakan efisiensi anggaran berdasarkan Inpres No. 1 Tahun 2025. Data dikumpulkan dengan menggunakan kata kunci yang relevan dengan topik penelitian, kemudian komentar yang diperoleh digunakan sebagai sumber data untuk analisis teks. Total data yang dianalisis mencapai lebih dari 3.900 komentar YouTube.

---

## Workflow

Analisis dilakukan melalui beberapa tahapan berikut:

### 1. Data Collection

Mengumpulkan lebih dari 3.900 komentar YouTube yang relevan dengan pembahasan Inpres No. 1 Tahun 2025 menggunakan kata kunci terkait efisiensi anggaran.

### 2. Data Preprocessing

Melakukan text preprocessing untuk mempersiapkan data sebelum dianalisis, meliputi:

- Normalisasi teks
- Penanganan slang
- Penghapusan stopwords
- Penghapusan karakter yang tidak diperlukan
- Stemming

### 3. Exploratory Text Analysis

Melakukan eksplorasi terhadap data teks untuk memahami:

- Distribusi komentar berdasarkan waktu
- Kata-kata yang sering muncul
- Pola pembahasan publik
- Topik yang dominan

### 4. Word Cloud Analysis

Membuat word cloud untuk mengidentifikasi kata-kata yang paling sering muncul dalam komentar publik.

### 5. Temporal Analysis

Menganalisis pola jumlah komentar berdasarkan waktu untuk melihat perubahan intensitas respons publik terhadap kebijakan.

### 6. Sentiment & Perception Analysis

Menganalisis kecenderungan sentimen dan persepsi publik berdasarkan komentar yang telah diproses.

---

## Key Findings

### 1. Respons publik meningkat setelah kebijakan diterbitkan
![Tren Jumlah Komentar](overview.png)

Aktivitas komentar menunjukkan adanya peningkatan respons publik dalam periode awal setelah Inpres No. 1 Tahun 2025 diterbitkan. Puncak komentar terjadi dalam sekitar 48 jam setelah kebijakan diberitakan/dibahas, yang menunjukkan adanya respons publik yang relatif cepat terhadap isu tersebut.

### 2. Efisiensi anggaran menjadi salah satu tema utama

Pembahasan publik banyak berkaitan dengan efisiensi anggaran, penggunaan anggaran negara, serta implementasi kebijakan pemerintah.

### 3. Muncul dukungan terhadap tujuan kebijakan

![Word Cloud](wordcloud.png)
Sebagian komentar menunjukkan respons yang mendukung tujuan efisiensi anggaran dan pemberantasan korupsi. Hal tersebut tercermin dari munculnya kata dan frasa yang berkaitan dengan:

- efisiensi
- pemberantasan korupsi
- hemat anggaran
- transparansi
- penggunaan anggaran

### 4. Skeptisisme terhadap implementasi kebijakan

Selain dukungan terhadap tujuan kebijakan, ditemukan pula komentar yang menunjukkan keraguan terhadap implementasinya.

Kemunculan frasa seperti "omong kosong" menunjukkan adanya skeptisisme publik terhadap efektivitas pelaksanaan kebijakan.

Temuan ini menunjukkan bahwa skeptisisme yang muncul lebih banyak berkaitan dengan **kepercayaan terhadap implementasi kebijakan**, bukan semata-mata penolakan terhadap tujuan efisiensi anggaran.

---

## Main Insights

Berdasarkan hasil analisis, respons publik terhadap kebijakan efisiensi anggaran menunjukkan adanya dua sisi utama:

**Support terhadap tujuan kebijakan**

Publik membahas pentingnya efisiensi, penghematan anggaran, serta pemberantasan korupsi.

**Skeptisisme terhadap implementasi**

Sebagian masyarakat mempertanyakan bagaimana kebijakan tersebut akan diterapkan dan apakah implementasinya benar-benar dapat mencapai tujuan yang diharapkan.

Dengan demikian, persepsi publik tidak hanya berkaitan dengan apakah masyarakat mendukung atau menolak kebijakan, tetapi juga berkaitan dengan **tingkat kepercayaan terhadap pelaksanaan kebijakan tersebut.**

---

## Tools & Technologies

- Python
- Google Colab
- Pandas
- Text Preprocessing
- NLP
- Word Cloud
- Data Visualization

---

## Project Type

**Collaborative Project**

### Team Members

| Name |
|---|
| Ulfatul Adawiyah |
| Muhammad Abdul Ghofur |
| Miranita Anisa Rohmah |
| Syafiqah Marsya Kholiyadi |

### Role

**Data Analyst & Researcher**

My Contributed to:

- Data understanding
- Data preparation
- Presentation

---

## Conclusion

Analisis komentar YouTube menunjukkan bahwa pembahasan mengenai efisiensi anggaran menghasilkan respons publik yang beragam. Publik tidak hanya membahas tujuan efisiensi dan pemberantasan korupsi, tetapi juga menyoroti aspek implementasi dan kepercayaan terhadap pelaksanaan kebijakan.
