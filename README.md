# Project-Penalaran-UAS

Proyek ini mengimplementasikan sistem Case-Based Reasoning (CBR) untuk menganalisis dan mencocokkan kasus-kasus putusan pengadilan pidana, khususnya kasus pencurian di Pengadilan Negeri Sumenep. Sistem ini dirancang untuk membantu pencarian preseden hukum berdasarkan kemiripan isi dokumen putusan.

## 📁 Struktur Folder

- data/  
  Berisi data mentah atau terstruktur seperti hasil scraping dan preprocessed file.

- ipynb/  
  Berisi notebook tahap-tahap pemrosesan CBR:
  - 01_casebase.ipynb
  - 02_caserepresentation.ipynb
  - 03_retreival.ipynb
  - 04_predict.ipynb
  - 05_modelevaluation.ipynb

- Scraping_PA_SUMENEP.ipynb  
  Notebook scraping data putusan dari situs Mahkamah Agung.

- putusan_ma_2025-06-25.csv  
  Dataset hasil scraping dan pembersihan yang siap digunakan untuk representasi kasus.

## ⚙️ Teknologi dan Library

- Python 3.x
- scikit-learn (TF-IDF, cosine_similarity)
- pandas, numpy (manipulasi data)
- nltk, Sastrawi (pemrosesan teks Bahasa Indonesia)
- matplotlib, seaborn (visualisasi dan evaluasi)

## 🔁 Alur CBR

1. Preprocessing teks putusan (cleaning, stemming)
2. Representasi dokumen menggunakan TF-IDF
3. Pengukuran kemiripan antar kasus menggunakan cosine similarity
4. Reuse solusi kasus terdahulu dengan metode:
   - Majority Vote
   - Weighted Similarity
5. Evaluasi performa model dengan confusion matrix, accuracy, precision, recall, dan F1-score

## 📊 Hasil Evaluasi

- Accuracy: ±81%
- F1-Score: 0.81
- Visualisasi Confusion Matrix tersedia di notebook evaluasi

## 📌 Tujuan

Proyek ini bertujuan mendemonstrasikan bagaimana teknologi CBR dapat digunakan untuk mendukung penalaran hukum dan sistem preseden berbasis data historis putusan.
"""
---
👨‍💻 Penulis

Apriadzandy Putra – Universitas Muhammadiyah Malang

M. Haidar Afif Al Azizi – Universitas Muhammadiyah Malang

