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
  <h3><a href="https://ieeexplore.ieee.org/document/10250127" target="_blank">Klasifikasi Wajah Anak Autis Menggunakan SURF dan Boosting</a></h3>
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
  <p><a href="https://ieeexplore.ieee.org/document/10250127" target="_blank">📄 Lihat Publikasi IEEE</a></p>
</div>

### 💬 Analisis Sentimen Ulasan
<div class="project">
  <div class="subtitle">Laskar AI x Dicoding</div>
  <h3><a href="https://github.com/Yorrissiagian/Proyek-Analisis-Sentimen" target="_blank">Analisis Sentimen Review Gojek</a></h3>
  <p>Submission kelas Belajar Fundamental Deep Learning yang berfokus pada scraping, preprocessing, pelabelan sentimen berbasis lexicon, visualisasi, serta klasifikasi menggunakan MLP terhadap review aplikasi Gojek dari Google Play Store.</p>
  <ul>
    <li>Scraping: 10.000 review menggunakan google-play-scraper</li>
    <li>Preprocessing lengkap: cleaning, slang correction, tokenization, stopword removal, stemming</li>
    <li>Labeling sentimen: lexicon_positive & lexicon_negative (threshold >=0: positif)</li>
    <li>Model: MLPClassifier (akurasi testing: 92.14%)</li>
  </ul>
  <p>
    <span class="badge">NLP</span>
    <span class="badge">Sentiment Analysis</span>
    <span class="badge">Lexicon-Based</span>
    <span class="badge">MLPClassifier</span>
  </p>
</div>

### 🏗 Membangun Proyek ML Terintegrasi
<div class="project">
  <div class="subtitle">Laskar AI x Dicoding</div>
  <h3><a href="https://github.com/Yorrissiagian/Membangun-proyek-ML" target="_blank">Membangun Proyek Machine Learning</a></h3>
  <p>Submission akhir kelas "Membangun Proyek Machine Learning" yang terdiri dari dua bagian: Clustering pengeluaran masyarakat & Klasifikasi berdasarkan hasil klaster.</p>
  <ul>
    <li>Clustering: KMeans (3 klaster), PowerTransformer, analisis RFM</li>
    <li>Klasifikasi: Logistic Regression & KNN, evaluasi F1 > 99%</li>
    <li>Model tuning: GridSearchCV & RandomizedSearchCV</li>
    <li>Visualisasi: learning curve, confusion matrix, distribusi fitur</li>
  </ul>
  <p>
    <span class="badge">MLOps</span>
    <span class="badge">Clustering</span>
    <span class="badge">Classification</span>
    <span class="badge">Tuning</span>
  </p>
</div>

---

## 📣 Kontak Saya
- 📧 Email: yorrissiagian6@email.com  
- 💼 LinkedIn: [linkedin.com/in/yorris-siagian-9a4756243](https://linkedin.com/in/yorris-siagian-9a4756243)  
- 👥 GitHub: [github.com/Yorrissiagian](https://github.com/Yorrissiagian)
 
> Terakhir diperbarui: {{ "now" | date: "%d %B %Y" }}
