<style>
  body {
    background-color: #121212;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
    color: #e0e0e0;
    padding: 2rem;
    line-height: 1.6;
  }

  h1, h2 {
    text-align: center;
    color: #64b5f6;
  }

  .profile-photo {
    display: flex;
    justify-content: center;
    margin: 2rem 0;
  }

  .profile-photo img {
    width: 160px;
    height: 160px;
    border-radius: 50%;
    object-fit: cover;
    border: 4px solid #0288d1;
    box-shadow: 0 0 10px rgba(2,136,209,0.4);
  }

  .project {
    border: 1px solid #333;
    border-radius: 12px;
    padding: 1.5rem;
    margin: 1.5rem 0;
    background: #1e1e1e;
    box-shadow: 0 2px 10px rgba(0,0,0,0.4);
  }

  .project h3 {
    margin-top: 0;
    color: #90caf9;
  }

  .project p {
    margin-bottom: 0.5rem;
  }

  .project .subtitle {
    font-weight: bold;
    color: #81d4fa;
    margin-bottom: 0.7rem;
  }

  .badge {
    display: inline-block;
    padding: 0.35em 0.7em;
    margin: 0.2em 0.2em 0 0;
    font-size: 0.8em;
    background: #0288d1;
    color: white;
    border-radius: 10px;
  }

  a {
    color: #4fc3f7;
    text-decoration: none;
  }

  a:hover {
    text-decoration: underline;
  }
</style>

# 👋 Halo! Saya Yorrissiagian

Fresh graduate yang fokus pada pengembangan sistem AI & Machine Learning end-to-end.  
Berikut adalah kumpulan proyek yang pernah saya kerjakan.

<div class="profile-photo">
  <img src="{{ '/yoris.jpg' | relative_url }}" alt="Foto Profil Yorrissiagian">
</div>

---

## 💼 Tentang Saya
> Lulusan Teknik Informatika dari Universitas Medan Area dengan minat kuat dalam membangun solusi AI yang berdampak.  
> Fokus: Data preprocessing, modeling, deployment & monitoring model ML.  
> Tools favorit: Python, scikit-learn, TensorFlow, Streamlit, MLflow, Prometheus, Metabase, Docker.

---

## 🚀 Proyek Unggulan

<!-- Semua proyek ditampilkan di bawah -->

### 🌾 Deteksi Penyakit Tanaman Pertanian
<div class="project">
  <div class="subtitle">Laskar AI x Dicoding</div>
  <h3><a href="https://github.com/Capstone-LAI25-SM015/Capstone_Project_LAI25" target="_blank">Deteksi Penyakit Tanaman</a></h3>
  <p>Proyek Computer Vision berbasis MobileNetV1 untuk mendeteksi penyakit tanaman. Dideploy dengan Streamlit.</p>
  <p><strong>Peran:</strong> Pemimpin tim, pengujian model, deployment.</p>
  <p>
    <span class="badge">Classification</span>
    <span class="badge">Streamlit</span>
    <span class="badge">MobileNetV1</span>
  </p>
  <p><a href="https://deteksipenyakittanaman.streamlit.app/" target="_blank">🔗 Lihat Demo</a></p>
</div>

### 🎓 Prediksi Dropout Mahasiswa
<div class="project">
  <div class="subtitle">Laskar AI x Dicoding</div>
  <h3><a href="https://github.com/Yorrissiagian/Prediksi-Dropout-Mahasiswa" target="_blank">Prediksi Dropout Mahasiswa</a></h3>
  <p>Model Random Forest untuk mendeteksi risiko dropout mahasiswa. Dilengkapi dashboard Metabase & aplikasi Streamlit.</p>
  <p>
    <span class="badge">Classification</span>
    <span class="badge">Metabase</span>
    <span class="badge">Random Forest</span>
  </p>
  <p><a href="https://jayajayainstitut-k75cbyntzam6qn66aabwtv.streamlit.app/" target="_blank">🔗 Lihat Demo</a></p>
</div>

### 🧑‍💼 Analisis Attrition Human Resources
<div class="project">
  <div class="subtitle">Laskar AI x Dicoding</div>
  <h3><a href="https://github.com/Yorrissiagian/Permasalahan-Human-Resources" target="_blank">Attrition Analysis - Jaya Jaya Maju</a></h3>
  <p>Model Logistic Regression untuk menganalisis penyebab tingginya attrition. Dashboard dibuat menggunakan Metabase.</p>
  <p>
    <span class="badge">HR Analytics</span>
    <span class="badge">Logistic Regression</span>
    <span class="badge">Metabase</span>
  </p>
</div>

### 🖼 Klasifikasi Gambar Daun Tomat
<div class="project">
  <div class="subtitle">Laskar AI x Dicoding</div>
  <h3><a href="https://github.com/Yorrissiagian/Proyek-Klasifikasi-Gambar" target="_blank">Klasifikasi Penyakit Daun Tomat</a></h3>
  <p>Menggunakan CNN untuk klasifikasi 10 jenis penyakit daun tomat. Akurasi mencapai 91.2%.</p>
  <p>
    <span class="badge">CNN</span>
    <span class="badge">Klasifikasi Gambar</span>
    <span class="badge">TensorFlow</span>
  </p>
</div>

### 🧠 Klasifikasi Wajah Anak Autis
<div class="project">
  <div class="subtitle">Skripsi</div>
  <h3><a href="https://ieeexplore.ieee.org/document/XXXXX" target="_blank">Klasifikasi Wajah Anak Autis Menggunakan SURF dan Boosting</a></h3>
  <p>Sistem klasifikasi wajah anak dengan gangguan spektrum autisme (ASD) menggunakan fitur SURF dan lima varian Boosting.</p>
  <ul>
    <li>Ekstraksi fitur: SURF</li>
    <li>Model: AdaBoost, GradientBoost, LightGBM, CatBoost, XGBoost</li>
    <li>Hasil terbaik: CatBoost (akurat 80.49%)</li>
  </ul>
  <p>
    <span class="badge">SURF</span>
    <span class="badge">Boosting</span>
    <span class="badge">Autism Detection</span>
    <span class="badge">Computer Vision</span>
  </p>
  <p><a href="https://ieeexplore.ieee.org/document/XXXXX" target="_blank">📄 Lihat Publikasi IEEE</a></p>
</div>

### 💬 Analisis Sentimen Ulasan Gojek
<div class="project">
  <div class="subtitle">Laskar AI x Dicoding</div>
  <h3><a href="https://github.com/Yorrissiagian/Proyek-Analisis-Sentimen" target="_blank">Analisis Sentimen Review Gojek</a></h3>
  <p>Proyek ini bertujuan untuk melakukan scraping data ulasan aplikasi Gojek dari Google Play Store dan mengklasifikasikan sentimen (positif vs negatif).</p>
  <ul>
    <li><strong>Web Scraping:</strong> Mengambil data ulasan menggunakan <code>google-play-scraper</code></li>
    <li><strong>Klasifikasi Sentimen:</strong> Label otomatis dari rating, preprocessing teks, fitur TF-IDF, dan model ML</li>
    <li><strong>Model:</strong> Logistic Regression, Naive Bayes, SVM</li>
    <li><strong>Evaluasi:</strong> Confusion Matrix, Accuracy, Precision, Recall, F1-score</li>
  </ul>
  <p><strong>Output:</strong> <code>gojek_reviews.csv</code> & model klasifikasi terlatih</p>
  <p>
    <span class="badge">Web Scraping</span>
    <span class="badge">Text Classification</span>
    <span class="badge">Naive Bayes</span>
    <span class="badge">TF-IDF</span>
    <span class="badge">SVM</span>
  </p>
</div>


### 🏗 Membangun Machine Learning
<div class="project">
  <div class="subtitle">Laskar AI x Dicoding</div>
  <h3><a href="https://github.com/Yorrissiagian/Membangun-proyek-ML" target="_blank">Belajar Membangun Machine Learning Project</a></h3>
  <p>Proyek ini mencakup dua komponen utama: klasifikasi untuk prediksi dropout mahasiswa, dan clustering untuk segmentasi pelanggan.</p>

  <p><strong>🧠 Klasifikasi: Prediksi Dropout Mahasiswa</strong></p>
  <ul>
    <li>EDA dan korelasi fitur dropout</li>
    <li>Preprocessing: encoding, normalisasi, imputasi</li>
    <li>Model: <code>RandomForestClassifier</code>, pipeline disimpan sebagai .pkl</li>
    <li>Evaluasi: accuracy, precision, recall, F1, confusion matrix</li>
    <li><strong>Output:</strong> <code>final_model_pipeline.pkl</code>, <code>label_encoder.pkl</code></li>
  </ul>

  <p><strong>📈 Clustering: Segmentasi Pelanggan</strong></p>
  <ul>
    <li>Analisis RFM (Recency, Frequency, Monetary)</li>
    <li>Preprocessing: PowerTransformer</li>
    <li>Clustering: KMeans, Elbow Method, Silhouette Score</li>
    <li>Output: Visualisasi scatter plot, pairplot, penamaan segmen</li>
  </ul>

  <p>
    <span class="badge">Classification</span>
    <span class="badge">Clustering</span>
    <span class="badge">Random Forest</span>
    <span class="badge">KMeans</span>
    <span class="badge">MLflow</span>
    <span class="badge">CI/CD</span>
  </p>
</div>


---

## 📫 Kontak Saya
- 📧 Email: yorrissiagian6@email.com  
- 💼 LinkedIn: [linkedin.com/in/yorris-siagian-9a4756243](https://linkedin.com/in/yorris-siagian-9a4756243)  
- 🐱 GitHub: [github.com/Yorrissiagian](https://github.com/Yorrissiagian)
 
> Terakhir diperbarui: {{ "now" | date: "%d %B %Y" }}
