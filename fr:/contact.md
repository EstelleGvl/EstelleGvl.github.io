---
layout: page
lang: fr
ref: contact
title: Contact
subtitle:
permalink: /fr/contact/
---

{% include parallax.html src="/assets/img/pizan.jpg" %}

<p style="text-align:center;">Merci de votre visite !</p>

<br>

<section class="contact-card">
  <h2 style="text-align:center;">Pour toute demande concernant ma recherche, mes activités de conseil, mes conférences ou l’enseignement d’un cours, n’hésitez pas à me contacter ici.</h2>
  <br>
  <form id="contact-form" action="https://formspree.io/f/xyzdybkd" method="POST" novalidate>
    <div class="two-col">
      <label>
        Prénom
        <input type="text" name="first_name" autocomplete="given-name" required>
      </label>
      <label>
        Nom
        <input type="text" name="last_name" autocomplete="family-name" required>
      </label>
    </div>
    <label>
      Adresse e-mail
      <input type="email" name="email" autocomplete="email" required>
    </label>
    <label>
      Téléphone
      <input type="tel" name="phone" autocomplete="tel">
    </label>
    <label>
      Votre message
      <textarea name="message" rows="6" required></textarea>
    </label>
    <!-- Anti-spam honeypot (kept hidden) -->
    <input type="text" name="website" tabindex="-1" autocomplete="off" style="position:absolute;left:-5000px;opacity:0">
    <!-- Optional: set email subject in your inbox -->
    <input type="hidden" name="_subject" value="Nouveau message depuis votre site web">
    <button class="btn btn-primary" type="submit">Envoyer</button>
    <p id="form-status" class="form-status" aria-live="polite"></p>
  </form>
</section>