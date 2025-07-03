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
<!-- Proyek lainnya tetap -->

<!-- Proyek: Membangun Proyek ML Terintegrasi -->
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
  <!-- Seluruh konten clustering & klasifikasi + hasil & kesimpulan dimasukkan di sini (seperti versi final sebelumnya) -->
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
