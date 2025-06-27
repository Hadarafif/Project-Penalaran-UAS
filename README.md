# 🔍 Sistem Analisis Putusan Hukum Berbasis Case-Based Reasoning

Repositori ini berisi implementasi metode Case-Based Reasoning (CBR) untuk menganalisis kasus hukum berbasis data putusan pengadilan Indonesia. Proyek ini terdiri dari pipeline end-to-end mulai dari pengambilan data, representasi kasus, pencarian kasus serupa, hingga evaluasi hasil solusi yang diusulkan.

---

## 📁 Struktur Proyek
📦cbr-hukum/
┣ 📜README.md
┣ 📜requirements.txt
┣ 📁data/
┃ ┗ putusan_clean.csv
┣ 📁notebooks/
┃ ┣ 01_scraping.ipynb
┃ ┣ 02_representasi.ipynb
┃ ┣ 03_retrieval.ipynb
┃ ┣ 04_prediksi_solusi.ipynb
┃ ┗ 05_evaluasi.ipynb


---

## ⚙️ Instalasi

1. Clone repositori:
   ```bash
   git clone https://github.com/username/cbr-hukum.git
   cd cbr-hukum

python -m venv venv
source venv/bin/activate     # Linux/macOS
venv\Scripts\activate        # Windows

pip install -r requirements.txt

##👨‍💻 Penulis
Apriadzandy Putra – Universitas Muhammadiyah Malang

M. Haidar Afif Al Azizi – Universitas Muhammadiyah Malang
