<style>
  body {
    background-color: #121212;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
    color: #e0e0e0;
    margin: 0;
    padding: 1rem;
    line-height: 1.6;
  }

  .container {
    max-width: 1300px;
    margin: 0 auto;
    padding: 2rem;
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

  .grid-2 {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1.5rem;
    margin-top: 1.5rem;
  }

  .image-block {
    text-align: center;
  }

  .caption {
    font-size: 0.9rem;
    color: #b0bec5;
    margin-top: 0.5rem;
  }

  a {
    color: #4fc3f7;
    text-decoration: none;
  }

  a:hover {
    text-decoration: underline;
  }

  .button {
    display: inline-block;
    background-color: #1e88e5;
    color: white;
    padding: 8px 16px;
    border-radius: 6px;
    text-decoration: none;
    font-weight: bold;
    transition: background 0.3s ease;
  }

  .button:hover {
    background-color: #1565c0;
  }

  @media (max-width: 768px) {
    .grid-2 {
      grid-template-columns: 1fr;
    }
  }
</style>

<h1>👋 Halo! Saya Yorrissiagian</h1>
<div class="profile-photo">
  <img src="{{ '/yoris.jpg' | relative_url }}" alt="Foto Profil Yorrissiagian">
</div>

<p>Fresh graduate yang fokus pada pengembangan sistem AI & Machine Learning end-to-end. Berikut adalah kumpulan proyek yang pernah saya kerjakan.</p>

<h2>💼 Tentang Saya</h2>
<blockquote>
  Lulusan Teknik Informatika dari Universitas Medan Area dengan minat kuat dalam membangun solusi AI yang berdampak.<br>
  Fokus: Data preprocessing, modeling, deployment & monitoring model ML.<br>
  Tools favorit: Python, scikit-learn, TensorFlow, Streamlit, MLflow, Prometheus, Metabase, Docker.
</blockquote>

<h2>🚀 Proyek Saya</h2>

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

<!-- 🏗 Membangun Proyek ML Terintegrasi -->
<div class="project">
  <div class="subtitle">Laskar AI x Dicoding</div>
  <h3>Membangun Proyek Machine Learning</h3>
  <p>
    <a href="https://github.com/Yorrissiagian/Membangun-proyek-ML" class="button" target="_blank">
      🔗 Lihat Proyek Lengkap di GitHub
    </a>
  </p>
  <p>
    Submission akhir kelas <strong>"Membangun Proyek Machine Learning"</strong> yang terdiri dari dua bagian:
    Clustering pengeluaran masyarakat & Klasifikasi berdasarkan hasil klaster.
  </p>

  <!-- 🔷 Clustering -->
  <h4>🔷 Clustering: Segmentasi Masyarakat Berdasarkan Pengeluaran</h4>
  <ul>
    <li>Algoritma: KMeans (3 klaster) dengan PowerTransformer</li>
    <li>Evaluasi jumlah cluster menggunakan Inertia & Silhouette Score</li>
    <li>Analisis distribusi pengeluaran untuk mengidentifikasi skewness & outlier</li>
    <li>Segmentasi masyarakat berdasarkan pola pengeluaran tahunan</li>
  </ul>

  <div class="image-block">
    <img src="Asset/Distribusi Pengeluaran.png" alt="Distribusi Pengeluaran" style="max-width:100%; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.2);">
    <p class="caption">
      <strong>Distribusi Pengeluaran:</strong> Histogram ini menunjukkan bahwa sebagian besar masyarakat memiliki
      pengeluaran rendah, dengan kehadiran outlier yang signifikan. Visual ini mendasari keputusan untuk melakukan
      transformasi data sebelum clustering.
    </p>
  </div>

  <div class="image-block">
    <img src="Asset/Evaluasi Jumlah Cluster (Inertia & Silhouette Score).png" alt="Evaluasi Jumlah Cluster" style="max-width:100%; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.2);">
    <p class="caption">
      <strong>Evaluasi Jumlah Cluster:</strong> Metode Elbow dan Silhouette Score digunakan untuk menentukan jumlah klaster optimal.
      Hasil menunjukkan bahwa 3 klaster memberikan pemisahan terbaik antar segmen masyarakat.
    </p>
  </div>

  <!-- 🔶 Klasifikasi -->
  <h4>🔶 Klasifikasi: Prediksi Segmentasi Masyarakat</h4>
  <ul>
    <li>Model: Logistic Regression & KNN</li>
    <li>Evaluasi akurasi dan F1-score mencapai >99%</li>
    <li>Hyperparameter tuning: GridSearchCV & RandomizedSearchCV</li>
    <li>Visualisasi: Confusion matrix dan learning curve untuk analisis performa</li>
  </ul>

  <div class="grid-2">
    <div class="image-block">
      <img src="Asset/Confusion Matrix Logistic Regression.png" alt="Confusion Matrix Logistic Regression" style="width:100%; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.15);">
      <p class="caption">
        <strong>Confusion Matrix (Logistic Regression):</strong> Model berhasil mengklasifikasikan setiap kelas dengan sangat akurat, hampir tanpa kesalahan.
      </p>
    </div>
    <div class="image-block">
      <img src="Asset/Confusion Matrix KNN.png" alt="Confusion Matrix KNN" style="width:100%; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.15);">
      <p class="caption">
        <strong>Confusion Matrix (KNN):</strong> Performa tinggi secara umum, meski sedikit lebih rendah pada kelas minoritas dibanding Logistic Regression.
      </p>
    </div>
  </div>

  <div class="grid-2">
    <div class="image-block">
      <img src="Asset/Learning Curve Logistic Regression.png" alt="Learning Curve Logistic" style="width:100%; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.15);">
      <p class="caption">
        <strong>Learning Curve (Logistic Regression):</strong> Kurva training dan validation yang mendekat menunjukkan model general dan tidak overfit.
      </p>
    </div>
    <div class="image-block">
      <img src="Asset/Learning Curve KNN.png" alt="Learning Curve KNN" style="width:100%; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.15);">
      <p class="caption">
        <strong>Learning Curve (KNN):</strong> Kinerja stabil dengan sedikit variasi, menunjukkan model cukup fleksibel terhadap perubahan data.
      </p>
    </div>
  </div>

  <!-- 📌 Hasil & Kesimpulan -->
  <h4>📌 Hasil & Kesimpulan</h4>
  <div class="conclusion" style="line-height: 1.7; font-size: 1rem; rgba(0,0,0,0.15);">
    <p>
      Proyek ini berhasil melakukan segmentasi terhadap masyarakat Indonesia berdasarkan pola pengeluaran tahunan menggunakan algoritma
      <strong>KMeans clustering</strong>. Analisis dan visualisasi evaluasi menunjukkan bahwa
      <strong>3 klaster</strong> merupakan jumlah optimal, masing-masing dengan karakteristik pengeluaran yang berbeda-beda.
      Preprocessing menggunakan <strong>PowerTransformer</strong> berhasil menormalkan distribusi data yang awalnya sangat skewed.
    </p>
    <p>
      Hasil klaster kemudian digunakan sebagai label target dalam proses klasifikasi.
      Dua model utama, yaitu <strong>Logistic Regression</strong> dan <strong>K-Nearest Neighbors (KNN)</strong>,
      berhasil dibangun dengan hasil yang sangat baik. Evaluasi model menunjukkan
      <strong>F1-score di atas 99%</strong>, serta confusion matrix yang mendekati sempurna untuk seluruh kelas.
    </p>
    <p>
      Selain itu, <strong>learning curve</strong> dari kedua model menunjukkan performa yang stabil
      dan tidak terjadi overfitting maupun underfitting yang signifikan. Hal ini menandakan bahwa
      pipeline machine learning yang dibangun—dari tahap eksplorasi, preprocessing, segmentasi, hingga klasifikasi—
      telah berjalan efektif dan menghasilkan sistem prediksi yang <strong>akurat, stabil, dan dapat direproduksi</strong>.
    </p>
  </div>
  <p>
    <span class="badge">MLOps</span>
    <span class="badge">Clustering</span>
    <span class="badge">Classification</span>
    <span class="badge">Tuning</span>
  </p>
</div>

<hr>

<h2>📣 Kontak Saya</h2>
<ul>
  <li>📧 Email: yorrissiagian6@email.com</li>
  <li>💼 LinkedIn: <a href="https://linkedin.com/in/yorris-siagian-9a4756243" target="_blank">linkedin.com/in/yorris-siagian-9a4756243</a></li>
  <li>👥 GitHub: <a href="https://github.com/Yorrissiagian" target="_blank">github.com/Yorrissiagian</a></li>
</ul>

<blockquote>
  Terakhir diperbarui: {{ "now" | date: "%d %B %Y" }}
</blockquote>
