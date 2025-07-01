---
layout: default
title: "Portofolio Yorrissiagian"
---

<style>
body {
  background-color: #e0f7fa;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
  color: #2c3e50;
  padding: 2rem;
}

h1, h2, h3 {
  text-align: center;
  color: #01579b;
}

.intro {
  text-align: center;
  margin-bottom: 2rem;
}

.projects {
  max-width: 800px;
  margin: 0 auto;
}

.project {
  background: #ffffff;
  border-radius: 8px;
  padding: 1.5rem;
  margin-bottom: 2rem;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

.project h3 {
  margin-top: 0;
}

.badges {
  margin: 0.5em 0;
}

.badge {
  display: inline-block;
  background: #0288d1;
  color: white;
  padding: 0.3em 0.6em;
  border-radius: 5px;
  margin: 0.2em;
  font-size: 0.85em;
}

.read-more {
  text-decoration: none;
  color: #01579b;
  font-weight: bold;
}
</style>

# 👋 Halo, saya Yorrissiagian

<div class="intro">
Saya adalah fresh graduate yang mengembangkan sistem AI & Machine Learning end-to-end — dari EDA, modeling, deployment, hingga monitoring.<br>
Lihat kode, demo, dan detail proyek saya di bawah atau kunjungi GitHub dan kontak saya lewat LinkedIn/email.
</div>

---

<div class="projects">

## 🚀 Proyek Unggulan

{% assign projects = site.data.projects %}
{% for p in projects %}
<div class="project">
  {% if p.image %}<img src="{{ p.image }}" alt="{{ p.title }}" style="max-width:100%;border-radius:5px;margin-bottom:1rem;">{% endif %}
  <h3><a href="{{ p.repo }}" target="_blank">{{ p.title }}</a></h3>
  <p>{{ p.summary }}</p>
  <div class="badges">
    {% for tag in p.tags %}<span class="badge">{{ tag }}</span>{% endfor %}
  </div>
  {% if p.demo %}<p><a class="read-more" href="{{ p.demo }}" target="_blank">🔗 Lihat Demo</a></p>{% endif %}
</div>
{% endfor %}

</div>

---

## 📢 Kontak Saya
- ✉️ Email: yorrissiagian6@email.com  
- LinkedIn: [linkedin.com/in/yorris-siagian-9a4756243](https://linkedin.com/in/yorris-siagian-9a4756243)  
- GitHub: [github.com/Yorrissiagian](https://github.com/Yorrissiagian)

---

> Portofolio ini dibangun dengan GitHub Pages + Jekyll.  
> Terakhir diperbarui: {{ "now" | date: "%d %B %Y" }}
