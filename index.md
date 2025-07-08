<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Portofolio Yorris Siagian</title>
  <link rel="stylesheet" href="style.css">
  <style>
  body {
    background-color: #121212;
    color: #e0e0e0;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
    padding: 2rem;
    line-height: 1.6;
  }

  h1, h2, h3, h4 {
    color: #64b5f6;
  }

  a {
    color: #64b5f6;
    text-decoration: none;
  }

  a:hover {
    text-decoration: underline;
  }

  .button {
  display: inline-block;
  background-color: #64b5f6;
  color: #ffffff;
  padding: 10px 18px;
  border-radius: 8px;
  font-weight: bold;
  transition: background-color 0.2s ease;
}
  .button:hover {
    background-color: #42a5f5;
    color: #ffffff;
  }

  .badge {
    display: inline-block;
    background-color: #64b5f6;
    color: #ffffff;
    padding: 6px 10px;
    border-radius: 5px;
    font-size: 0.9rem;
    margin-right: 6px;
    margin-bottom: 6px;
     font-weight: bold;
  }

  .project {
    margin-bottom: 4rem;
    padding: 1.5rem;
    background-color: #1e1e1e;
    border-radius: 15px;
    box-shadow: 0 0 10px rgba(100, 181, 246, 0.2);
  }

  .image-block {
    margin-top: 1rem;
  }

  .image-block img {
  max-width: 70%; 
  height: auto;   
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0,0,0,0.2);
  display: block;
  margin-left: auto;
  margin-right: auto;
}

  .caption {
    font-size: 0.95rem;
    margin-top: 0.5rem;
    color: #b0bec5;
  }

  blockquote {
    background-color: #1f1f1f;
    border-left: 5px solid #64b5f6;
    padding: 1rem;
    font-style: italic;
    border-radius: 5px;
  }

  ul, ol {
    padding-left: 1.5rem;
  }

  table {
    width: 100%;
    border-collapse: collapse;
    color: #e0e0e0;
    margin-top: 1rem;
  }

  th, td {
    padding: 8px;
    border: 1px solid #555;
  }

  th {
    background-color: #1a237e;
    color: #fff;
  }

  tr:nth-child(even) {
    background-color: #263238;
  }

  .grid-2 {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1rem;
  }

  hr {
    border: 1px solid #64b5f6;
    margin: 3rem 0;
  }

  .profile-container {
    text-align: center;
    margin-bottom: 3rem;
  }

  .profile-container img {
    width: 150px;
    height: 150px;
    object-fit: cover;
    border-radius: 50%;
    box-shadow: 0 0 10px rgba(100, 181, 246, 0.4);
    margin-bottom: 1rem;
  }
</style>

</head>
<body>
<div class="profile-container">
  <img src="{{ '/yoris.jpg' | relative_url }}" alt="Foto Profil Yorris Siagian">
  <h1>Yorris Siagian</h1>
  <p>Machine Learning Engineer | AI Enthusiast</p>
</div>

<h2>💼 Tentang Saya</h2>
<blockquote>
  Saya adalah lulusan Teknik Informatika dari Universitas Medan Area. Saya memiliki minat yang besar dalam membangun sistem AI dan Machine Learning dari awal hingga tahap implementasi. Fokus saya meliputi pemahaman data, pembuatan model, deployment, hingga monitoring performa model di lingkungan produksi.
</blockquote>

<h2>🧰 Tools Favorit</h2>
<ul>
  <li>Python</li>
  <li>scikit-learn</li>
  <li>TensorFlow</li>
  <li>Streamlit</li>
  <li>MLflow</li>
  <li>Metabase</li>
  <li>Prometheus</li>
  <li>Docker</li>
</ul>

<h2>👨‍💼 Pengalaman Kerja</h2>
<ul>
  <li><strong>Web Administrator – Tobacamp (Juli 2023 - September 2024)</strong><br> 
      Bekerja dalam Bertanggung jawab atas pengelolaan website mulai dari pemeliharaan hingga konten website dan bertanggung jawab sebagai mentor UX Design untuk pelatihan UX Design.</li>
</ul>

<h2>🎓 Riwayat Pendidikan</h2>
<ul>
  <li><strong>Universitas Medan Area</strong> – S1 Teknik Informatika (2019–2024)</li>
</ul>

<h2>🚀 Proyek Saya</h2>

<!-- Semua proyek ditampilkan di bawah -->

🌾 Deteksi Penyakit Tanaman Pertanian
<div class="project">
  <div class="subtitle">Laskar AI x Dicoding</div>
  <h3>Deteksi Penyakit Tanaman</h3>
  <p><a href="https://github.com/Capstone-LAI25-SM015/Capstone_Project_LAI25" class="button" target="_blank">🔗 Lihat Proyek Lengkap di GitHub</a></p>
  <p>Sistem klasifikasi 31 kelas daun tanaman (sehat dan sakit) berbasis MobileNetV1, di-deploy via Streamlit.</p>
  <p><strong>Peran:</strong> Lead tim, tuning model, deployment.</p>
  <span class="badge">Agritech</span></p>
  <p><a href="https://deteksipenyakittanaman.streamlit.app/" target="_blank">🔗 Coba Demo Aplikasinya</a></p>
  <div class="image-block">
    <img src="Asset/Confusion matrix_mobilenet.png" alt="Confusion Matrix MobileNetV1">
    <p class="caption">Confusion matrix 31 kelas daun, akurasi & F1-score 82%. Beberapa kelas mirip masih tertukar.</p>
  </div>
  <div class="image-block">
    <img src="Asset/streamlit_deteksi_penyakit_tanaman.jpeg" alt="Streamlit Deteksi Penyakit Tanaman">
    <p class="caption">Tampilan aplikasi Streamlit: upload gambar daun, hasil klasifikasi muncul langsung.</p>
  </div>
  <p><span class="badge">Image Classification</span> <span class="badge">MobileNetV1</span> <span class="badge">Streamlit</span> <span class="badge">Transfer Learning</span> 
</div>

🎓 Prediksi Dropout Mahasiswa
<div class="project">
  <div class="subtitle">Laskar AI x Dicoding</div>
  <h3>Prediksi Dropout Mahasiswa</h3>
  <p><a href="https://github.com/Yorrissiagian/Prediksi-Dropout-Mahasiswa" class="button" target="_blank">🔗 Lihat Proyek Lengkap di GitHub</a></p>
  <p>Prediksi risiko dropout menggunakan Random Forest, dashboard Metabase, dan aplikasi Streamlit.</p>
  <h4>📊 Dashboard</h4>
  <p>Visualisasi distribusi dropout berdasar gender, usia, beasiswa, dan ekonomi.</p>
  <div class="image-block">
    <img src="Asset/jayainstitut_dashboard.jpg" alt="Dashboard Dropout Mahasiswa">
    <p class="caption">Dashboard Metabase menampilkan insight penting terkait dropout.</p>
  </div>
  <h4>🧠 Prediksi Model</h4>
  <ul>
    <li>Akurasi: 91.87%</li>
    <li>F1-score dropout: 0.89</li>
  </ul>
  <p>Fitur penting: tunggakan, beasiswa, usia masuk, nilai masuk.</p>
  <h4>🖥 Aplikasi Streamlit</h4>
  <p>Form input mahasiswa untuk prediksi dropout secara langsung.</p>
  <div class="image-block">
    <img src="Asset/streamlit_JayaInstitut.png" alt="Streamlit Prediksi Dropout">
    <p class="caption">Form interaktif prediksi status mahasiswa berdasarkan input data.</p>
  </div>
  <p><a href="https://jayajayainstitut-k75cbyntzam6qn66aabwtv.streamlit.app/" target="_blank">🔗 Lihat Demo Aplikasi Streamlit</a></p>
  <p><span class="badge">Classification</span> <span class="badge">Metabase</span> <span class="badge">Streamlit</span> <span class="badge">Random Forest</span></p>
</div>
🧑‍💼 Analisis Attrition Human Resources
<div class="project">
  <div class="subtitle">Laskar AI x Dicoding</div>
  <h3>Attrition Analysis - Jaya Jaya Maju</h3>
  <p>
    <a href="https://github.com/Yorrissiagian/Permasalahan-Human-Resources" class="button" target="_blank">
      🔗 Lihat Proyek Lengkap di GitHub
    </a>
  </p>
  <p>
    Proyek akhir kelas <strong>Belajar Penerapan Data Science</strong> oleh <strong>Laskar AI x Dicoding</strong>, menganalisis penyebab <em>attrition</em> (>12%) di Jaya Jaya Maju dengan <strong>Logistic Regression</strong> dan visualisasi interaktif di <strong>Metabase</strong>.

  </p>
  <p><strong>Peran:</strong> Exploratory Data Analysis, pemodelan, dan visualisasi bisnis.</p>
  <p>
    <span class="badge">HR Analytics</span>
    <span class="badge">Logistic Regression</span>
    <span class="badge">Metabase</span>
  </p>

  <p><strong>Fitur Utama:</strong></p>
  <p>Proyek ini menganalisis pola attrition berdasarkan lembur, promosi, dan masa kerja. Dua model Logistic Regression dibangun; model seimbang dipilih karena meningkatkan recall dari 50% ke 72%. Hasilnya divisualisasikan lewat dashboard Metabase yang menyoroti attrition per departemen, dampak lembur, dan tren promosi.
</p>

  <p><strong>Hasil Insight:</strong></p>
  <p>Lembur dan kurangnya promosi dalam 0–2 tahun terakhir jadi faktor utama attrition. Departemen Sales mencatat attrition tertinggi (\~22%). Disarankan pengurangan beban lembur dan penerapan program promosi terjadwal.
</p>

  <p><strong>Model Disimpan:</strong> logistic_attrition_model.pkl (class-balanced version)</p>

  <p><strong>Visualisasi Dashboard Metabase:</strong></p>
  <img src="Asset/Metabase.png" alt="Visualisasi Dashboard Metabase - Attrition Analysis"/>
  <p style="font-size: 0.9rem; margin-top: 0.5rem;">
    Visual ini menampilkan ringkasan attrition rate perusahaan, distribusi berdasarkan lembur, masa kerja, promosi terakhir, dan departemen. 
    Tujuannya adalah memberi wawasan cepat dan actionable kepada tim HR melalui tampilan interaktif berbasis Metabase.
  </p>
</div>


🖼 Klasifikasi Penyakit Daun Tomat
<div class="project">
  <div class="subtitle">Laskar AI x Dicoding</div>
  <h3>Klasifikasi Daun Tomat Menggunakan CNN</h3>
  <p>
    <a href="https://github.com/Yorrissiagian/Proyek-Klasifikasi-Gambar" class="button" target="_blank">
      🔗 Lihat Proyek Lengkap di GitHub
    </a>
  </p>
  <p>
    Proyek akhir kelas <strong>Belajar Fundamental Deep Learning</strong> dengan model CNN untuk klasifikasi 10 penyakit daun tomat. Dataset berisi 10.000 gambar yang dibagi menjadi train, validation, dan test, dengan augmentasi untuk meningkatkan generalisasi.
  </p>
  <p>
    Arsitektur model terdiri dari 3 blok Conv2D + MaxPooling, diikuti Dense layer dan Dropout. 
    Model dilatih menggunakan <strong>Adam optimizer</strong> dan EarlyStopping. Evaluasi menunjukkan:
  </p>
  <ul>
    <li><strong>Akurasi:</strong> 91.2%</li>
    <li><strong>F1-Score Macro:</strong> 0.91</li>
    <li>Performa stabil pada semua kelas, termasuk deteksi daun sehat</li>
  </ul>

  <div class="image-block">
    <img src="Asset/training_validation_plot.png" alt="Training vs Validation Accuracy and Loss">
    <p class="caption">
      <strong>Learning Curve:</strong> Menunjukkan bahwa model tidak overfitting dan berhasil belajar dari data secara konsisten.
    </p>
  </div>

  <p>
    <span class="badge">CNN</span>
    <span class="badge">Image Classification</span>
    <span class="badge">Tomato Disease</span>
    <span class="badge">Deep Learning</span>
  </p>
</div>


<!-- 🧠 Klasifikasi Wajah Anak Autis -->
<div class="project">
  <div class="subtitle">Skripsi</div>
  <h3>Klasifikasi Wajah Anak Autis Menggunakan SURF dan Boosting</h3>
  <p>
    <a href="https://github.com/Yorrissiagian/Klasifikasi-Wajah-Anak-Autis" class="button" target="_blank">
      🔗 Lihat Proyek Lengkap di GitHub
    </a>
  </p>
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
  <p>
    Dataset berisi 203 gambar (.jpg) dari Bundaku Autism Clinic Center, terdiri dari 102 gambar autis dan 101 normal, dengan rasio split 80% untuk pelatihan dan 20% untuk pengujian.
  </p>

  <h4>⚙️ Metodologi</h4>
  <p>
    Gambar dikonversi ke grayscale dan fitur wajah diekstraksi dengan <strong>SURF</strong>. Lima model Boosting dilatih: AdaBoost, GradientBoost, LightGBM, CatBoost, dan XGBoost. Evaluasi dilakukan dengan metrik Accuracy, Precision, Recall, F1-Score, dan F2-Score.
  </p>

  <h4>📊 Hasil Evaluasi</h4>
  <table style="width:100%; border-collapse: collapse; color: #e0e0e0;">
  <thead>
  <tr>
    <th style="padding: 8px; border: 1px solid #555; background-color: #1a237e; color: #ffffff; font-weight: bold;">Algoritma</th>
    <th style="padding: 8px; border: 1px solid #555; background-color: #1a237e; color: #ffffff; font-weight: bold;">Akurasi</th>
    <th style="padding: 8px; border: 1px solid #555; background-color: #1a237e; color: #ffffff; font-weight: bold;">Precision</th>
    <th style="padding: 8px; border: 1px solid #555; background-color: #1a237e; color: #ffffff; font-weight: bold;">Recall</th>
    <th style="padding: 8px; border: 1px solid #555; background-color: #1a237e; color: #ffffff; font-weight: bold;">F1-Score</th>
    <th style="padding: 8px; border: 1px solid #555; background-color: #1a237e; color: #ffffff; font-weight: bold;">F2-Score</th>
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
    Proyek ini membuktikan bahwa kombinasi <strong>SURF + Boosting</strong> efektif membedakan wajah anak autis dan normal. <strong>CatBoost</strong> menjadi model terbaik dengan F1 dan F2-score di atas 80%. Hasil ini membuka peluang pengembangan sistem diagnosis dini berbasis wajah.
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
    Submission proyek kelas <strong>"Belajar Fundamental Deep Learning"</strong> ini menganalisis sentimen review aplikasi Gojek dari Google Play Store. Proyek mencakup scraping, preprocessing, pelabelan sentimen berbasis lexicon, visualisasi, dan klasifikasi dengan <strong>MLPClassifier</strong>.
  </p>
  <p>
    Scraping 10.000 review aplikasi Gojek dilakukan dengan <strong>google-play-scraper</strong>. Teks diproses melalui slang correction, tokenisasi, stopword removal, dan stemming. Sentimen dilabeli menggunakan lexicon positif-negatif. Model <strong>MLPClassifier</strong> digunakan dengan akurasi pengujian sebesar 92,14%.
  </p>

  <div class="image-block">
    <img src="Asset/Sentiment Polarity Data.png" alt="Distribusi Sentimen Review Gojek"
      style="max-width:100%; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.2);">
    <p class="caption">
      <strong>Distribusi Sentimen:</strong> Pie chart menunjukkan mayoritas review bernada positif, diikuti proporsi signifikan review negatif, yang menjadi dasar evaluasi performa model klasifikasi.
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
    Dataset review Gojek diproses dengan pipeline teks dan labeling lexicon. WordCloud mengungkap kata kunci pengguna, sementara <strong>MLPClassifier</strong> mencapai akurasi tinggi, menunjukkan pendekatan sederhana bisa menghasilkan model NLP yang <strong>efektif dan andal</strong>.
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
  <p>
    Menggunakan KMeans (3 klaster) dengan PowerTransformer, jumlah klaster dievaluasi via Inertia dan Silhouette Score. Analisis distribusi pengeluaran dilakukan untuk mengidentifikasi skewness dan outlier, lalu masyarakat disegmentasi berdasarkan pola pengeluaran tahunan.
  </p>

  <div class="image-block">
    <img src="Asset/Distribusi Pengeluaran.png" alt="Distribusi Pengeluaran" style="max-width:100%; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.2);">
    <p class="caption">
      <strong>Distribusi Pengeluaran:</strong> Histogram menunjukkan mayoritas masyarakat berpengeluaran rendah dengan outlier signifikan, sehingga diperlukan transformasi data sebelum clustering.
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
  <p>
    Menggunakan model Logistic Regression dan KNN, evaluasi menunjukkan akurasi dan F1-score >99%. Hyperparameter tuning dilakukan dengan GridSearchCV dan RandomizedSearchCV, disertai visualisasi confusion matrix dan learning curve untuk analisis performa.
  </p>

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
      Proyek ini menggunakan <strong>KMeans</strong> untuk segmentasi masyarakat berdasarkan pengeluaran tahunan. Tiga klaster terbukti optimal, dan <strong>PowerTransformer</strong> berhasil menormalkan data yang awalnya skewed.
    </p>
    <p>
      Hasil klaster digunakan sebagai label untuk klasifikasi. Dua model—<strong>Logistic Regression</strong> dan <strong>KNN</strong>—dibangun dengan <strong>F1-score >99%</strong> dan confusion matrix nyaris sempurna di semua kelas.
    </p>
    <p>
      Selain itu, <strong>learning curve</strong> menunjukkan performa stabil tanpa overfitting atau underfitting. Ini menandakan pipeline machine learning yang dibangun efektif, akurat, stabil, dan dapat direproduksi.
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
  <hr>
  <h2>📣 Kontak Saya</h2>
  <ul>
    <li><strong>Email:</strong> yorrissiagian@gmail.com</li>
    <li><strong>LinkedIn:</strong> <a href="https://linkedin.com/in/yorrissiagian" target="_blank">linkedin.com/in/yorrissiagian</a></li>
    <li><strong>GitHub:</strong> <a href="https://github.com/Yorrissiagian" target="_blank">github.com/Yorrissiagian</a></li>
  </ul>

</body>
</html>
