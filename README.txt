# 🇮🇳 Indian Language Classification System
Sistem klasifikasi bahasa India berbasis Deep Learning menggunakan model CNN.  
Aplikasi ini dapat mengidentifikasi bahasa India dari input teks yang diberikan pengguna melalui antarmuka web berbasis Flask.

---

## 🚀 Features
- 🧠 **Deep Learning Model (CNN)** untuk klasifikasi bahasa India  
- 🌐 **Web Interface (Flask)** — mudah digunakan  
- 📂 Mendukung berbagai bahasa India seperti:
  - Hindi
  - Bengali
  - Tamil
  - Kannada
  - Telugu
  - Malayalam  
  *(sesuaikan dengan dataset/mode kamu)*  
- 🖼️ **Upload atau input teks secara langsung**  
- 📊 Output berupa **prediksi bahasa + confidence score**

---

## 🗂️ Project Structure
├── app.py
├── model2.h5
├── templates/
│ └── index.html
├── static/
│ ├── styles.css
│ └── images/
├── temp/
└── README.md

yaml
Salin kode

---

## 🧰 Technologies Used
- **Python 3**
- **Flask**
- **TensorFlow / Keras**
- **NumPy**
- **HTML/CSS**

---

## 📦 Installation & Setup

### 1. Clone Repository
```bash
git clone https://github.com/Yefta2404-Ind/Indian-Language-Classification-System.git
cd Indian-Language-Classification-System
2. Install Dependencies
bash
Salin kode
pip install -r requirements.txt
Jika belum ada file requirements.txt, jalankan:

bash
Salin kode
pip freeze > requirements.txt
3. Run Flask App
bash
Salin kode
python app.py
Akses melalui browser:

arduino
Salin kode
http://localhost:5000
🧪 How It Works
User memasukkan teks bahasa India

Sistem mem-proses teks

Model CNN melakukan klasifikasi

Hasil prediksi ditampilkan di halaman web

📘 Screenshots
(Boleh tambahkan gambar UI kamu di folder /static/screenshots lalu tempelkan di sini)

📌 To-Do (Future Updates)
 Tambah akurasi model

 Tambah dukungan lebih banyak bahasa India

 Deploy aplikasi ke Render / Railway

 Tambah halaman dokumentasi API

🤝 Contributing
Pull request selalu diterima. Boleh bantu perbaikan model, UI, ataupun dokumentasi.

📜 License
Project ini menggunakan lisensi MIT — silakan gunakan dan kembangkan secara bebas.

👤 Author
Jefta Aditya
GitHub: https://github.com/Yefta2404-Ind
