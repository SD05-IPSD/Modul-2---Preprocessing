# 🧠 Modul Penugasan: *Data Preprocessing*

## 📂 Deskripsi Tugas
Pada penugasan ini, Anda diminta untuk melakukan **tahapan preprocessing data** menggunakan bahasa pemrograman **Python**.  
Data yang digunakan dapat diunduh melalui tautan berikut:

🔗 **[Download Dataset di Google Drive](https://drive.google.com/drive/folders/1oikgKUhVwxuDy-6Trrox0rrPhRGgU7GH?usp=drive_link)**

Tujuan dari tugas ini adalah agar mahasiswa mampu memahami dan menerapkan proses *cleaning*, *transformation*, dan *encoding* pada dataset sebelum digunakan untuk analisis atau *machine learning*.

---

## 🎯 Tujuan Pembelajaran
1. Memahami konsep dan tahapan dalam preprocessing data.  
2. Mampu menangani nilai hilang (*missing values*) dengan berbagai metode.  
3. Mampu melakukan transformasi tipe data dan encoding.  
4. Menampilkan serta menganalisis data sebelum dan sesudah preprocessing.

---

## 🧩 Petunjuk Pengerjaan
- Kerjakan menggunakan **Google Colab** atau **Jupyter Notebook**.  
- Gunakan library seperti `pandas`, `numpy`, `sklearn`, dan `miceforest` (jika digunakan).  
- Beri komentar di setiap langkah agar mudah dipahami.  
- Simpan hasil pengerjaan dalam format `.ipynb` 

---

## 🧾 Soal Penugasan

### 1️. Tampilkan data yang telah diunduh, kemudian **jelaskan semua kolom** yang terdapat pada dataset tersebut.  


---

### 2️. Lakukan **agregasi** antara tabel `features` dengan tabel `labels`.  

---

### 3️. Tampilkan **tipe data** dari setiap kolom yang terdapat dalam dataset.  

---

### 4️. Tampilkan **statistik deskriptif** dari dataset dan berikan **analisis singkat** mengenai hasilnya.  

---

### 5️. Slicing Data
Tampilkan:
- **20 baris awal** dari dataset  
- **20 baris terakhir**  
- **Baris dari index 80 - 100**  


---

### 6️. Tangani **nilai yang hilang (NaN)** menggunakan salah satu metode berikut:
- Imputasi dengan **statistik deskriptif** (`mean`, `median`, `mode`), atau  
- Imputasi dengan **model** seperti:
  - `SimpleImputer`
  - `KNNImputer`
  - `miceforest` *(nilai plus jika menggunakan ini)*

> Pastikan untuk menampilkan data sebelum dan sesudah imputasi.

---

### 7️. Opsional : Lakukan **encoding** terhadap kolom bertipe *object* menjadi numerik menggunakan:
- `LabelEncoder`, atau  
- `OneHotEncoder`

> Tampilkan hasil transformasi setelah encoding.

---

### 8️. Tampilkan kembali dataset yang telah melalui seluruh proses preprocessing (cleaning, imputasi, dan encoding).

---

## 📦 File yang Dikumpulkan
- Notebook: `NIM_Nama.ipynb`  


---

## 💡 Tips Tambahan
- Pastikan tidak ada nilai `NaN` atau tipe data yang tidak sesuai setelah preprocessing.  
- Gunakan `Markdown` atau komentar di notebook untuk menjelaskan setiap langkah dengan jelas.

---

## ✍️ Penilaian
| Kriteria | Bobot |
|-----------|--------|
| Kelengkapan langkah preprocessing | 40% |
| Penanganan missing value | 20% |
| Kejelasan penjelasan dan komentar kode | 20% |
| Kerapian dan format laporan | 10% |
| Bonus (miceforest, visualisasi tambahan) | 10% |

---

📘 **Selamat mengerjakan!**  
Gunakan penugasan ini untuk memperkuat pemahaman Anda tentang **data preprocessing dalam machine learning.**
