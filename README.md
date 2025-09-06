# 📌 Project Web Scraper Pemula

**By: Mufrih Fawwaz**

## 📝 Pengertian Web Scraper

Web Scraper adalah proses **mengekstrak atau mengambil data dari sebuah website secara otomatis**, kemudian menyimpannya dalam format yang dapat diolah lebih lanjut, seperti spreadsheet (Excel/CSV) atau basis data.

## 🎯 Tujuan Proyek

1. Mempelajari cara mengekstrak data dari sebuah website.
2. Mengambil dan menganalisis **judul, link berita, dan isi berita**.
3. Mengolah hasil scraping agar dapat digunakan untuk analisis data lebih lanjut.
4. Menambahkan kategori pada setiap berita.
5. Melakukan **EDA (Exploratory Data Analysis)**.
6. Membuat model sederhana untuk klasifikasi berita.
7. Mengevaluasi performa model.

---

## 🌐 Sumber Data

Proyek ini menggunakan data dari situs **BBC Indonesia**: [https://www.bbc.com/indonesia](https://www.bbc.com/indonesia)

Data yang diperoleh merupakan berita-berita terbaru yang dipublikasikan di BBC Indonesia. Mayoritas informasi yang diambil didominasi oleh berita dengan **kategori politik**.

---


---

## ⚙️ Tahapan Instalasi & Setup

1. **Clone Repository**
   Unduh proyek ini dengan cara:

   ```bash
   git clone https://github.com/Mufawaz29/Project1WebScraperPythonPemula.git
   ```

2. **Masuk ke Folder Proyek**

   ```bash
   cd Project1WebScraperPythonPemula
   ```

3. **Buat Virtual Environment (Opsional tapi Disarankan)**

   ```bash
   python -m venv venv
   ```

   Aktifkan virtual environment:

   * **Windows**

     ```bash
     .\venv\Scripts\activate
     ```
   * **Linux/Mac**

     ```bash
     source venv/bin/activate
     ```

4. **Install Semua Library yang Dibutuhkan**

   ```bash
   pip install -r requirements.txt
   ```

5. **Jalankan Pipeline Proyek Secara Berurutan**

   * Pertama: `scrape_bbc.py` → untuk scraping data berita.
   * Kedua: `clean_bbc.py` → untuk membersihkan teks.
   * Ketiga: `eda_bbc.py` → untuk melakukan exploratory data analysis.
   * Keempat: `add_category_bbc.py` → untuk menambahkan kategori (saat ini fokus politik).
   * Kelima: `modelling_bbc.py` → untuk membangun model klasifikasi sederhana.
   * Terakhir: `evaluation_bbc.py` → untuk mengevaluasi performa model.

---

