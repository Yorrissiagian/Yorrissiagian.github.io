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
  <h3>Deteksi Penyakit Tanaman</h3>

  <p>
    <a href="https://github.com/Capstone-LAI25-SM015/Capstone_Project_LAI25" class="button" target="_blank">
      🔗 Lihat Proyek Lengkap di GitHub
    </a>
  </p>

  <p>
    <strong>Proyek ini merupakan Capstone Project dari program Laskar AI</strong>, yang berfokus pada penerapan deep learning di sektor pertanian. Tujuan utamanya adalah membangun sistem deteksi otomatis penyakit daun tanaman berbasis gambar, untuk lima komoditas utama: <em>tomat, cabai, kentang, terong, dan labu</em>.
  </p>

  <p>
    Sistem ini dilatih untuk mengenali 31 kelas berbeda — mencakup berbagai jenis penyakit dan juga kondisi daun sehat. Model inti yang digunakan adalah <strong>MobileNetV1</strong>, dipilih karena bobotnya yang ringan namun akurat, sehingga ideal untuk kebutuhan deteksi cepat di perangkat terbatas.
  </p>

  <p><strong>Peran saya:</strong> Pemimpin tim, bertanggung jawab atas pengujian model, tuning hyperparameter, dan deployment ke Streamlit Cloud.</p>

  <p>
    <span class="badge">Image Classification</span>
    <span class="badge">MobileNetV1</span>
    <span class="badge">Streamlit</span>
    <span class="badge">Transfer Learning</span>
    <span class="badge">Agritech</span>
  </p>

  <p>
    <a href="https://deteksipenyakittanaman.streamlit.app/" target="_blank">🔗 Coba Demo Aplikasinya</a>
  </p>

  <div class="image-block">
    <img src="Asset/Confusion matrix_mobilenet.png" alt="Confusion Matrix MobileNetV1"
         style="max-width:100%; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.2);">
    <p class="caption">
      <strong>Analisis Confusion Matrix:</strong><br>
      Confusion matrix ini menunjukkan performa model terhadap 31 kelas penyakit daun. <strong>Akurasi keseluruhan mencapai 82%</strong> dengan macro average F1-score sebesar 82%. Pola diagonal menunjukkan bahwa sebagian besar prediksi sesuai target. Namun, beberapa kelas seperti penyakit daun yang memiliki visual mirip—contohnya <em>mosaic</em> dan <em>leaf curl</em>—masih sering tertukar. Analisis ini kami gunakan sebagai dasar perbaikan preprocessing dan augmentasi untuk meningkatkan kemampuan generalisasi model ke data dunia nyata.
    </p>
  </div>

  <div class="image-block">
    <img src="Asset/streamlit_deteksi_penyakit_tanaman.jpeg" alt="Streamlit Deteksi Penyakit Tanaman"
         style="max-width:100%; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.2);">
    <p class="caption">
      <strong>Tampilan Aplikasi Streamlit:</strong><br>
      Aplikasi ini dirancang agar mudah digunakan oleh petani dan masyarakat umum. Cukup unggah foto daun yang ingin didiagnosa, sistem akan secara otomatis mengklasifikasikan jenis penyakit atau menyatakan bahwa daun tersebut sehat. Hasil prediksi disertai persentase akurasi dan notifikasi peringatan dini jika ditemukan penyakit. Aplikasi ini bertujuan untuk membantu petani mengambil tindakan cepat—seperti menyemprot fungisida atau berkonsultasi dengan penyuluh pertanian—sebelum penyakit menyebar dan menyebabkan kerugian panen.
    </p>
  </div>

</div>


### 🎓 Prediksi Dropout Mahasiswa
<div class="project">
  <div class="subtitle">Laskar AI x Dicoding — Proyek Akhir Kelas Belajar Penerapan Data Science</div>
  <h3>Prediksi Dropout Mahasiswa</h3>
  <p>
    <a href="https://github.com/Yorrissiagian/Prediksi-Dropout-Mahasiswa" class="button" target="_blank">
      🔗 Lihat Proyek Lengkap di GitHub
    </a>
  </p>
  <p>
    Proyek ini bertujuan untuk memprediksi risiko dropout mahasiswa Jaya Jaya Institut berdasarkan faktor akademik, demografis, dan finansial. Model machine learning yang digunakan adalah <strong>Random Forest Classifier</strong> dengan pipeline lengkap untuk preprocessing, evaluasi, dan deployment.
  </p>

  <h4>📊 Business Dashboard</h4>
  <p>Dashboard interaktif dibangun dengan Metabase dan menampilkan:</p>
  <ul>
    <li><strong>Distribusi Dropout vs Lulus:</strong> 39.1% mahasiswa tercatat dropout dari total 3.630.</li>
    <li><strong>Dropout Berdasarkan Gender:</strong> Visualisasi perbandingan jumlah dropout laki-laki dan perempuan.</li>
    <li><strong>Nilai Akademik dan Unit Lulus:</strong> Perbandingan nilai rata-rata masuk, unit lulus, dan IPK akhir antara mahasiswa dropout dan graduate.</li>
    <li><strong>Distribusi Usia Masuk Mahasiswa:</strong> Dropout didominasi oleh usia <em>early twenties</em>.</li>
    <li><strong>Faktor Ekonomi:</strong> Mahasiswa dengan tunggakan dan tanpa beasiswa memiliki risiko dropout tertinggi.</li>
  </ul>
  <div class="image-block">
    <img src="Asset/jayainstitut_dashboard.jpg" alt="Dashboard Dropout Mahasiswa" style="max-width:100%; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.2);">
    <p class="caption">
      Dashboard Metabase menampilkan metrik penting seperti rasio dropout, distribusi berdasarkan gender dan usia, serta pengaruh faktor ekonomi.
    </p>
  </div>

  <h4>🧠 Prediksi Model</h4>
  <p>Model dibangun dengan <strong>Random Forest</strong> dan mencapai performa sebagai berikut:</p>
  <ul>
    <li><strong>Akurasi:</strong> 91.87%</li>
    <li><strong>F1-Score (Dropout):</strong> 0.89</li>
    <li><strong>Precision:</strong> 0.95</li>
    <li><strong>Recall:</strong> 0.84</li>
  </ul>
  <p>Fitur paling berpengaruh terhadap prediksi dropout:</p>
  <ol>
    <li>Status keterlambatan pembayaran (tuition fees)</li>
    <li>Status beasiswa</li>
    <li>Status utang (debtor)</li>
    <li>Usia saat mendaftar</li>
    <li>Nilai masuk (admission grade)</li>
  </ol>

  <h4>🖥 Aplikasi Streamlit</h4>
  <p>
    Aplikasi prediksi dibuat dengan Streamlit dan dapat digunakan oleh staf kampus untuk menguji risiko dropout berdasarkan data input mahasiswa. Sistem akan menampilkan status prediksi (DROPOUT / GRADUATE) secara instan.
  </p>
  <div class="image-block">
    <img src="Asset/streamlit_JayaInstitut.png" alt="Streamlit Prediksi Dropout" style="max-width:100%; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.2);">
    <p class="caption">
      Form interaktif yang memungkinkan pengguna memasukkan data mahasiswa dan langsung melihat prediksi dropout.
    </p>
  </div>
  <p>
    <a href="https://jayajayainstitut-k75cbyntzam6qn66aabwtv.streamlit.app/" target="_blank">🔗 Lihat Demo Aplikasi Streamlit</a>
  </p>

  <p>
    <span class="badge">Classification</span>
    <span class="badge">Metabase</span>
    <span class="badge">Streamlit</span>
    <span class="badge">Random Forest</span>
    <span class="badge">Data Science</span>
  </p>
</div>


### 🧑‍💼 Analisis Attrition Human Resources
<div class="project">
  <div class="subtitle">Laskar AI x Dicoding</div>
  <h3>Attrition Analysis - Jaya Jaya Maju</h3>
  <p>
    <a href="https://github.com/Yorrissiagian/Permasalahan-Human-Resources" class="button" target="_blank">
      🔗 Lihat Proyek Lengkap di GitHub
    </a>
  </p>
  <p>
    Proyek akhir dari kelas <strong>Belajar Penerapan Data Science</strong> yang diselenggarakan oleh <strong>Laskar AI x Dicoding</strong>. 
    Proyek ini berfokus pada analisis penyebab tingginya <em>attrition</em> (>12%) di perusahaan fiktif Jaya Jaya Maju, menggunakan pendekatan 
    <strong>Logistic Regression</strong> dan visualisasi interaktif via <strong>Metabase</strong>.
  </p>
  <p><strong>Peran:</strong> Exploratory Data Analysis, pemodelan, dan visualisasi bisnis.</p>
  <p>
    <span class="badge">HR Analytics</span>
    <span class="badge">Logistic Regression</span>
    <span class="badge">Metabase</span>
  </p>

  <p><strong>Fitur Utama:</strong></p>
  <ul>
    <li>Melakukan <em>exploratory data analysis</em> untuk mengidentifikasi pola attrition berdasarkan lembur, promosi terakhir, dan masa kerja.</li>
    <li>Mengembangkan dua model Logistic Regression (default & class-balanced) untuk membandingkan trade-off antara akurasi dan recall.</li>
    <li>Model seimbang dipilih karena meningkatkan <strong>recall dari 50% menjadi 72%</strong>, penting untuk mendeteksi risiko keluar lebih akurat.</li>
    <li>Dashboard Metabase menampilkan metrik kunci seperti attrition per departemen, dampak lembur, dan tren promosi.</li>
  </ul>

  <p><strong>Hasil Insight:</strong></p>
  <ul>
    <li><strong>Lembur (OverTime)</strong> dan <strong>tidak adanya promosi dalam 0–2 tahun terakhir</strong> menjadi dua penyebab utama tingginya attrition.</li>
    <li>Departemen <strong>Sales</strong> menunjukkan attrition tertinggi (~22%) dibandingkan departemen lain.</li>
    <li>Rekomendasi mencakup pengurangan beban kerja lembur dan program promosi terjadwal.</li>
  </ul>

  <p><strong>Model Disimpan:</strong> logistic_attrition_model.pkl (class-balanced version)</p>

  <p><strong>Visualisasi Dashboard Metabase:</strong></p>
  <img src="Asset/Metabase.png" alt="Visualisasi Dashboard Metabase - Attrition Analysis" style="max-width:100%; border: 1px solid #ccc; border-radius: 8px; margin-top: 1rem;" />
  <p style="font-size: 0.9rem; margin-top: 0.5rem;">
    Visual ini menampilkan ringkasan attrition rate perusahaan, distribusi berdasarkan lembur, masa kerja, promosi terakhir, dan departemen. 
    Tujuannya adalah memberi wawasan cepat dan actionable kepada tim HR melalui tampilan interaktif berbasis Metabase.
  </p>
</div>


### 🖼 Klasifikasi Penyakit Daun Tomat
<div class="project">
  <div class="subtitle">Laskar AI x Dicoding</div>
  <h3>Klasifikasi Daun Tomat Menggunakan CNN</h3>
  <p>
    <a href="https://github.com/Yorrissiagian/Proyek-Klasifikasi-Gambar" class="button" target="_blank">
      🔗 Lihat Proyek Lengkap di GitHub
    </a>
  </p>
  <p>
    Proyek akhir dari kelas <strong>Belajar Fundamental Deep Learning</strong> yang membangun model CNN untuk mengklasifikasikan 10 jenis penyakit daun tomat. 
    Dataset berisi 10.000 gambar yang dibagi dalam train, validation, dan test. 
    Augmentasi digunakan untuk meningkatkan generalisasi model.
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
    <img src="Asset/training_validation_plot.png" alt="Training vs Validation Accuracy and Loss"
      style="max-width:100%; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.2);">
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
