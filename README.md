---

# 📌 Project Web Scraper Pemula

**By: Mufrih Fawwaz**

## 📝 Pengertian Web Scraper

Web Scraper adalah proses **mengambil data dari sebuah website secara otomatis**, lalu menyimpannya dalam format yang bisa diolah lebih lanjut, seperti **CSV, Excel, atau database**.

## 🎯 Tujuan Proyek

1. Belajar cara melakukan web scraping dari website.
2. Mengambil dan menyimpan **judul, link, dan isi berita**.
3. Membersihkan hasil scraping agar siap dianalisis.
4. Menambahkan kategori pada setiap berita.
5. Melakukan **EDA (Exploratory Data Analysis)**.
6. Membuat model sederhana untuk klasifikasi berita.
7. Mengevaluasi performa model.

---

## 🌐 Sumber Data

Proyek ini menggunakan data dari **BBC Indonesia**:
🔗 [https://www.bbc.com/indonesia](https://www.bbc.com/indonesia)

Data yang diambil berupa berita-berita terbaru, dengan mayoritas kategori didominasi oleh **politik**.

---

## ⚙️ Instalasi & Setup

1. **Clone Repository**
   Unduh proyek ini dengan perintah:

   ```bash
   git clone https://github.com/Mufawaz29/Project1WebScraperPythonPemula.git
   ```

2. **Masuk ke Folder Proyek**

   ```bash
   cd Project1WebScraperPythonPemula
   ```

   Jika ada file `scripts.zip` dan `data.zip`, silakan **ekstrak terlebih dahulu** hingga muncul folder `scripts/` dan `data/`.

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

5. **Jalankan Pipeline Proyek (Urutannya Penting ⚡)**

   * **Langkah 1** → `scrape_bbc.py` → scraping data berita
   * **Langkah 2** → `clean_bbc.py` → membersihkan teks
   * **Langkah 3** → `eda_bbc.py` → melakukan exploratory data analysis
   * **Langkah 4** → `add_category_bbc.py` → menambahkan kategori (saat ini fokus politik)
   * **Langkah 5** → `modelling_bbc.py` → membangun model klasifikasi sederhana
   * **Langkah 6** → `evaluation_bbc.py` → mengevaluasi performa model

---

