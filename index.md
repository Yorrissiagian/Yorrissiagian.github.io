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

<!-- 🧠 Klasifikasi Wajah Anak Autis -->
<div class="project">
  <div class="subtitle">Skripsi</div>
  <h3><a href="https://ieeexplore.ieee.org/document/10250127" target="_blank">Klasifikasi Wajah Anak Autis Menggunakan SURF dan Boosting</a></h3>
  <p>
    Proyek skripsi yang bertujuan mengembangkan sistem klasifikasi untuk membedakan wajah anak dengan gangguan spektrum autisme (ASD) dan wajah anak normal. 
    Sistem ini memanfaatkan teknik ekstraksi fitur <strong>SURF (Speeded-Up Robust Features)</strong> dan lima varian algoritma <strong>Boosting</strong>.
  </p>

  <h4>🎯 Tujuan</h4>
  <ul>
    <li>Mengklasifikasikan wajah anak autis dan normal secara otomatis berbasis citra.</li>
    <li>Mengevaluasi performa lima algoritma Boosting terhadap fitur citra hasil ekstraksi SURF.</li>
  </ul>

  <h4>📁 Dataset</h4>
  <ul>
    <li>Jumlah gambar: 203 (102 autis, 101 normal)</li>
    <li>Format: .jpg | Sumber: Bundaku Autism Clinic Center</li>
    <li>Rasio split: 80% pelatihan, 20% pengujian</li>
  </ul>

  <h4>⚙️ Metodologi</h4>
  <ul>
    <li>Preprocessing: konversi gambar ke grayscale</li>
    <li>Ekstraksi fitur wajah menggunakan <strong>SURF</strong></li>
    <li>Pelatihan lima model Boosting: AdaBoost, GradientBoost, LightGBM, CatBoost, dan XGBoost</li>
    <li>Evaluasi menggunakan metrik: Accuracy, Precision, Recall, F1-Score, dan F2-Score</li>
  </ul>

  <h4>📊 Hasil Evaluasi</h4>
  <table style="width:100%; border-collapse: collapse; color: #e0e0e0;">
  <thead>
  <tr>
    <th style="padding: 8px; border: 1px solid #555; background-color: #263238; color: #ffffff; font-weight: bold;">Algoritma</th>
    <th style="padding: 8px; border: 1px solid #555; background-color: #263238; color: #ffffff; font-weight: bold;">Akurasi</th>
    <th style="padding: 8px; border: 1px solid #555; background-color: #263238; color: #ffffff; font-weight: bold;">Precision</th>
    <th style="padding: 8px; border: 1px solid #555; background-color: #263238; color: #ffffff; font-weight: bold;">Recall</th>
    <th style="padding: 8px; border: 1px solid #555; background-color: #263238; color: #ffffff; font-weight: bold;">F1-Score</th>
    <th style="padding: 8px; border: 1px solid #555; background-color: #263238; color: #ffffff; font-weight: bold;">F2-Score</th>
  </tr>
</thead>
    <tbody>
      <tr>
        <td style="padding: 8px; border: 1px solid #555;">AdaBoost</td>
        <td style="padding: 8px; border: 1px solid #555;">68.29%</td>
        <td style="padding: 8px; border: 1px solid #555;">69.49%</td>
        <td style="padding: 8px; border: 1px solid #555;">69.02%</td>
        <td style="padding: 8px; border: 1px solid #555;">68.22%</td>
        <td style="padding: 8px; border: 1px solid #555;">68.45%</td>
      </tr>
      <tr style="background-color: #263238;">
        <td style="padding: 8px; border: 1px solid #555;">Gradient Boosting</td>
        <td style="padding: 8px; border: 1px solid #555;">73.17%</td>
        <td style="padding: 8px; border: 1px solid #555;">73.57%</td>
        <td style="padding: 8px; border: 1px solid #555;">73.57%</td>
        <td style="padding: 8px; border: 1px solid #555;">73.17%</td>
        <td style="padding: 8px; border: 1px solid #555;">73.31%</td>
      </tr>
      <tr>
        <td style="padding: 8px; border: 1px solid #555;">LightGBM</td>
        <td style="padding: 8px; border: 1px solid #555;">73.17%</td>
        <td style="padding: 8px; border: 1px solid #555;">73.10%</td>
        <td style="padding: 8px; border: 1px solid #555;">73.21%</td>
        <td style="padding: 8px; border: 1px solid #555;">73.11%</td>
        <td style="padding: 8px; border: 1px solid #555;">73.16%</td>
      </tr>
      <tr style="background-color: #263238;">
        <td style="padding: 8px; border: 1px solid #555;"><strong>CatBoost</strong></td>
        <td style="padding: 8px; border: 1px solid #555;"><strong>80.49%</strong></td>
        <td style="padding: 8px; border: 1px solid #555;"><strong>80.60%</strong></td>
        <td style="padding: 8px; border: 1px solid #555;"><strong>80.74%</strong></td>
        <td style="padding: 8px; border: 1px solid #555;"><strong>80.74%</strong></td>
        <td style="padding: 8px; border: 1px solid #555;"><strong>80.59%</strong></td>
      </tr>
      <tr>
        <td style="padding: 8px; border: 1px solid #555;">XGBoost</td>
        <td style="padding: 8px; border: 1px solid #555;">70.73%</td>
        <td style="padding: 8px; border: 1px solid #555;">70.84%</td>
        <td style="padding: 8px; border: 1px solid #555;">70.93%</td>
        <td style="padding: 8px; border: 1px solid #555;">70.72%</td>
        <td style="padding: 8px; border: 1px solid #555;">70.80%</td>
      </tr>
    </tbody>
  </table>

  <h4>📌 Kesimpulan</h4>
  <p>
    Proyek ini menunjukkan bahwa kombinasi metode <strong>SURF + Boosting</strong> mampu membedakan wajah anak autis dan wajah normal secara efektif. 
    Algoritma <strong>CatBoost</strong> menjadi yang paling akurat dengan nilai F1-score dan F2-score di atas 80%.
    Studi ini membuka peluang untuk pengembangan sistem diagnosis awal berbasis pengenalan wajah anak.
  </p>

  <p>
    <span class="badge">SURF</span>
    <span class="badge">Boosting</span>
    <span class="badge">Autism Detection</span>
    <span class="badge">Machine Learning</span>
  </p>
  <p><a href="https://ieeexplore.ieee.org/document/10250127" target="_blank">📄 Lihat Publikasi IEEE</a></p>
</div>


<!-- 📱 Analisis Sentimen Review Gojek -->
<div class="project">
  <div class="subtitle">Laskar AI x Dicoding</div>
  <h3>Analisis Sentimen</h3>
    <p>
    <a href="https://github.com/Yorrissiagian/Proyek-Analisis-Sentimen" class="button" target="_blank">
      🔗 Lihat Proyek Lengkap di GitHub
    </a>
  </p>
  <p>
    Submission proyek kelas <strong>"Belajar Fundamental Deep Learning"</strong> yang berfokus pada analisis sentimen terhadap review aplikasi Gojek dari Google Play Store. 
    Proyek ini mencakup scraping, preprocessing teks, labeling sentimen berbasis lexicon, visualisasi, dan klasifikasi menggunakan <strong>MLPClassifier</strong>.
  </p>

  <ul>
    <li>Scraping 10.000 review aplikasi com.gojek.app menggunakan <strong>google-play-scraper</strong></li>
    <li>Preprocessing teks: slang correction, tokenization, stopword removal, stemming</li>
    <li>Labeling sentimen berbasis <strong>lexicon-positive</strong> dan <strong>lexicon-negative</strong></li>
    <li>Model klasifikasi: <strong>MLPClassifier</strong> dengan akurasi testing 92.14%</li>
  </ul>

  <div class="image-block">
    <img src="Asset/Sentiment Polarity Data.png" alt="Distribusi Sentimen Review Gojek"
      style="max-width:100%; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.2);">
    <p class="caption">
      <strong>Distribusi Sentimen:</strong> Pie chart menunjukkan bahwa sebagian besar review bernada positif, dengan proporsi signifikan dari review negatif. 
      Ini menjadi dasar evaluasi performa model klasifikasi selanjutnya.
    </p>
  </div>

  <div class="image-block">
    <img src="Asset/WordCloud.png" alt="Word Cloud Review Gojek"
      style="max-width:100%; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.2);">
    <p class="caption">
      <strong>WordCloud:</strong> Visualisasi kata-kata yang paling sering muncul dalam review pengguna aplikasi Gojek. Kata "gojek", "driver", dan "layanan" termasuk yang paling dominan.
    </p>
  </div>

  <h4>📈 Evaluasi Model Klasifikasi (MLPClassifier)</h4>
  <ul>
    <li><strong>Akurasi Training:</strong> 98.11%</li>
    <li><strong>Akurasi Testing:</strong> 92.14%</li>
  </ul>
  <pre style="background-color:#1e1e1e; padding:1rem; border-radius:10px; color:#cfd8dc;">
Classification Report (Testing - MLP):

              precision    recall  f1-score   support

           0       0.93      0.94      0.94      3966
           1       0.90      0.89      0.90      2471

    accuracy                           0.92      6437
   macro avg       0.92      0.92      0.92      6437
weighted avg       0.92      0.92      0.92      6437
  </pre>

  <h4>📌 Hasil & Insight</h4>
  <p>
    Dataset review Gojek berhasil dikumpulkan dan diproses menggunakan pipeline teks lengkap. Labeling berbasis lexicon memberikan dasar yang kuat untuk supervised learning.
    WordCloud memperlihatkan kata-kata kunci pengguna, dan model <strong>MLPClassifier</strong> berhasil mengklasifikasikan review dengan akurasi tinggi. 
    Hal ini menunjukkan bahwa pendekatan sederhana namun terstruktur dapat menghasilkan model NLP yang <strong>efektif dan dapat diandalkan</strong>.
  </p>

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
