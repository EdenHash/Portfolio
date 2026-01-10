---
layout: page
title: À propos
permalink: /about/
weight: 3
---

<!-- prettier-ignore-start -->

# **À propos de moi**

<div class="text-center mb-4">
 <img src="{{ site.baseurl }}/{{ site.author.image }}" alt="Photo de {{ site.author. name }}" class="rounded-circle img-fluid" style="max-width: 200px; border:  4px solid #007bff;">
</div>

<div class="lead text-center mb-5">
  Bonjour, je m'appelle <strong>{{ site.author.name }}</strong> 👋
  <br>
  Étudiant en développement web à Epitech Lille
</div>

## _Compétences Techniques

<div class="row">
  <div class="col-md-6">
    {% include about/skills.html title="Compétences de Programmation" source=site.data.programming-skills %}
  </div>
  <div class="col-md-6">
    {% include about/languages.html title="Langues" source=site.data.languages %}
  </div>
</div>

## _Qualités Professionnelles

<div class="row mt-4">
  <div class="col-md-6">
    <h5><i class="fas fa-lightbulb text-warning"></i> Créativité</h5>
    <p>Capacité à proposer des solutions innovantes et à penser "outside the box" pour résoudre des problèmes complexes.</p>
  </div>
  <div class="col-md-6">
    <h5><i class="fas fa-graduation-cap text-primary"></i> Apprentissage Continu</h5>
    <p>Passion pour l'apprentissage de nouvelles technologies et l'amélioration constante de mes compétences.</p>
  </div>
  <div class="col-md-6">
    <h5><i class="fas fa-users text-success"></i> Travail d'Équipe</h5>
    <p>Excellentes compétences en communication et capacité à collaborer efficacement au sein d'équipes diverses.</p>
  </div>
  <div class="col-md-6">
    <h5><i class="fas fa-clock text-info"></i> Autonomie & Organisation</h5>
    <p>Capable de gérer mon temps efficacement et de mener des projets de manière autonome jusqu'à leur aboutissement.</p>
  </div>
  <div class="col-md-6">
    <h5><i class="fas fa-search text-danger"></i> Attention aux Détails</h5>
    <p>Souci du détail dans le code et l'interface utilisateur pour garantir une expérience optimale.</p>
  </div>
  <div class="col-md-6">
    <h5><i class="fas fa-puzzle-piece text-secondary"></i> Résolution de Problèmes</h5>
    <p>Approche méthodique et analytique pour identifier et résoudre les défis techniques.</p>
  </div>
</div>

## _Centres d'Intérêt

<div class="row mt-4 mb-4">
  <div class="col-md-4">
    <div class="text-center p-3">
      <h5>- Sport</h5>
    </div>
  </div>
  <div class="col-md-4">
    <div class="text-center p-3">
      <h5>- Technologies</h5>
    </div>
  </div>
  <div class="col-md-4">
    <div class="text-center p-3">
      <h5>- Pâtisserie</h5>
    </div>
  </div>
</div>

### _Autres Passions

-   **Gaming** : Passionné de jeux vidéo, ce qui nourrit ma créativité et ma compréhension des interfaces utilisateur
-   **Lecture** : J'aime lire pour m'instruire et pousser ma réflexion
-   **Technologie & Innovation** : Curiosité pour les nouvelles technologies et leur impact sur la société

## _Parcours et Chronologie

<div class="row">
{% include about/timeline.html %}
</div>

<div class="text-center mt-4 mb-4">
  <a href="{{ site.baseurl }}/projects" class="btn btn-primary btn-lg mx-2">
    <i class="fas fa-folder-open"></i> Voir mes projets
  </a>
  <a href="{{ site.baseurl }}/contact" class="btn btn-outline-primary btn-lg mx-2">
    <i class="fas fa-envelope"></i> Me contacter
  </a>
</div>

---
<!-- prettier-ignore-end -->
