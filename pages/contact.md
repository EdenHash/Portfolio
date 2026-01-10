---
layout: page
title: Contact
permalink: /contact/
weight: 5
---

# **Contactez-moi**

Je suis toujours ouvert aux opportunités professionnelles, aux collaborations sur des projets ou simplement pour échanger sur le développement web. N'hésitez pas à me contacter !

<div class="row align-items-start">
  <div class="col-md-6 mb-4">
      <h2 class="h3">Informations de Contact</h2>
      <div class="contact-info">
        <div class="card">
          <div class="card-body d-flex align-items-center">
            <i class="fas fa-envelope fa-3x text-danger mr-4"></i>
            <div class="flex-grow-1">
              <h5 class="card-title mb-1">Email</h5>
              <p class="card-text mb-2">Pour toute demande professionnelle</p>
              <a href="mailto:{{ site.author.email }}" class="btn btn-outline-primary btn-sm">M'envoyer un email</a>
            </div>
          </div>
        </div>
        <div class="card">
          <div class="card-body d-flex align-items-center">
            <i class="fab fa-github fa-3x text-secondary mr-4"></i>
            <div class="flex-grow-1">
              <h5 class="card-title mb-1">GitHub</h5>
              <p class="card-text mb-2">Mes projets</p>
              <a href="https://github.com/{{ site.author.github }}" class="btn btn-outline-primary btn-sm" target="_blank" rel="noopener noreferrer">Voir mon profil</a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="col-md-6">
      <h2 class="h3">Formulaire de Contact</h2>
      <form>
        <div class="form-group mb-3">
          <label for="name">Nom <span class="text-danger">*</span></label>
          <input type="text" class="form-control" id="name" name="name" required placeholder="Votre nom">
        </div>
        <div class="form-group mb-3">
          <label for="email">Email <span class="text-danger">*</span></label>
          <input type="email" class="form-control" id="email" name="_replyto" required placeholder="votre.email@exemple.com">
        </div>
        <div class="form-group mb-3">
          <label for="subject">Sujet <span class="text-danger">*</span></label>
          <input type="text" class="form-control" id="subject" name="_subject" required placeholder="Objet de votre message">
        </div>
        <div class="form-group mb-3">
          <label for="message">Message <span class="text-danger">*</span></label>
          <textarea class="form-control" id="message" name="message" rows="6" required placeholder="Votre message..."></textarea>
        </div>
        <input type="text" name="_gotcha" style="display:none">
        <input type="hidden" name="_subject" value="Nouveau message depuis le portfolio">
        <button type="submit" class="btn btn-primary btn-lg">
          <i class="fas fa-paper-plane"></i> Envoyer le message
        </button>
      </form>
    </div>
  </div>
