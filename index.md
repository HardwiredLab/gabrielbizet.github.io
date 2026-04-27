---
layout: default
title: Accueil
permalink: /
---

<style>

/* ===== ESPACEMENT SOUS LA NAVIGATION ===== */
.site-header {
  padding-bottom: 28px !important;
  margin-bottom: 45px !important;
}

/* ===== HERO / INTRO ===== */
.intro {
  background: linear-gradient(135deg, #1b1b1b 0%, #111 100%);
  padding: 100px 40px;
  border-radius: 18px;
  border: 1px solid #2d2d2d;
  box-shadow: 0 0 32px rgba(200,160,100,0.22);
  text-align: center;
  margin-bottom: 80px;
}

.intro h1 {
  font-size: 3.2rem;
  font-weight: 700;
  color: #e8cfa3;
  margin-bottom: 36px;
  letter-spacing: 0.7px;
}

.intro p, .intro br {
  color: #e8e8e8;
  font-size: 1.55rem; /* encore augmenté */
  line-height: 2;
  font-weight: 300;
}

/* ===== SECTIONS ===== */
.section {
  background: #1b1b1b;
  padding: 32px 34px;
  border-radius: 16px;
  border: 1px solid #3d3d3d;
  box-shadow: 0 0 18px rgba(200,160,100,0.18);
  margin-bottom: 50px;
  transition: transform 0.25s ease, box-shadow 0.25s ease;
}

.section:hover {
  transform: translateY(-6px);
  box-shadow: 0 0 26px rgba(200,160,100,0.28);
}

.section h3 {
  margin-top: 0;
  font-size: 1.45rem;
  color: #e8cfa3;
  margin-bottom: 10px;
}

.section p {
  margin: 0 0 14px;
  color: #e8e8e8;
  line-height: 1.6;
}

.section a {
  color: #e8cfa3;
  font-weight: 600;
  text-decoration: none;
}

.section a:hover {
  color: #f5e7d3;
}

/* ===== BANNIÈRE ===== */
.banner {
  width: 100%;
  height: 520px; /* beaucoup plus grande */
  border-radius: 18px;

  /* Affichage propre */
  background-size: cover; /* couvre sans déformer */
  background-position: center 15%; /* remonte ton visage */
  background-repeat: no-repeat;

  /* Suppression du bandeau */
  border: none;
  box-shadow: none;

  margin-bottom: 50px;
}

/* ===== BOUTONS ===== */
.buttons {
  margin-top: 40px;
  display: flex;
  gap: 18px;
  flex-wrap: wrap;
}

.buttons a {
  background: #1b1b1b;
  padding: 12px 22px;
  border-radius: 10px;
  border: 1px solid #3d3d3d;
  color: #e8cfa3;
  text-decoration: none;
  font-weight: 600;
  transition: 0.25s ease;
}

.buttons a:hover {
  background: rgba(200,160,100,0.12);
  border-color: #e8cfa3;
  transform: translateY(-3px);
}

</style>



<div class="intro">
    <h1>Portfolio de compétences</h1>
   
 Bienvenue sur mon portfolio académique<br>
 Il propose une vue d’ensemble de mes travaux, de mes engagements et des compétences mobilisées dans le cadre de mon activité professionnelle

 </div>



<div class="section">
<h3>👤 À propos</h3>
<p>Quelques repères sur mon identité professionnelle et mon projet de carrière</p>
<a href="{{ "/about/" | relative_url }}">Voir →</a>
</div>

<div class="section">
<h3>🎓 Cursus académique</h3>
<p>Présentation de mon parcours universitaire et des compétences clés qui y sont associées</p>
<a href="{{ "/formation/" | relative_url }}">Voir →</a>
</div>

<div class="section">
<h3>🏥 Pratique clinique</h3>
<p>Mon activité de sage-femme</p>
<a href="{{ "/pratique-clinique/" | relative_url }}">Voir →</a>
</div>

<div class="section">
<h3>🔬 Recherche</h3>
<p>Mes travaux en cours et publications</p>
<a href="{{ "/recherche/" | relative_url }}">Voir →</a>
</div>

<div class="section">
<h3>📚 Enseignement</h3>
<p>Les compétences liées à mon activité d'enseignement</p>
<a href="{{ "/enseignement/" | relative_url }}">Voir →</a>
</div>

<div class="section">
<h3>🚀 Projets transversaux</h3>
<p>Mes engagements et projets connexes</p>
<a href="{{ "/projets-transversaux/" | relative_url }}">Voir →</a>
</div>

<div class="section">
<h3>📬 Contact</h3>
<p>Pour échanger et collaborer</p>
<a href="{{ "/contact/" | relative_url }}">Voir →</a>
</div>

<br><br>

<div class="banner" style="background-image: url('{{ "/assets/assets/img/LKD_v2.jpg" | relative_url }}');"></div>

<br><br>

Ce site a été réalisé dans le cadre du projet **COMPEDOC** mené par l'Université de Lille


 <div class="buttons">
        <a href="https://www.linkedin.com/in/gabriel-bizet-3872aa286/" target="_blank">LinkedIn</a>
        <a href="https://www.researchgate.net/profile/Gabriel-Bizet" target="_blank">ResearchGate</a>
        <a href="https://orcid.org/0000-0001-8758-6056" target="_blank">ORCID</a>
    </div>
