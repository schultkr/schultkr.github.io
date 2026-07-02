---
layout: single
permalink: /card/
title: "Contact Card"
author_profile: false
sitemap: false
---
{% include base_path %}

<div class="business-card">

  <img class="business-card__avatar" src="{{ base_path }}/images/Christoph_Schult.jpg" alt="Christoph Schult">

  <h1 class="business-card__name">Christoph Schult</h1>
  <p class="business-card__title">Postdoctoral Researcher</p>
  <p class="business-card__org">Halle Institute for Economic Research (IWH)</p>
  <p class="business-card__location"><i class="fas fa-fw fa-location-dot" aria-hidden="true"></i> Halle (Saale), Germany</p>

  <a class="btn btn--large business-card__save" href="{{ base_path }}/files/Christoph_Schult.vcf" download>
    <i class="fas fa-fw fa-address-card" aria-hidden="true"></i> Save to Contacts
  </a>

  <ul class="business-card__links">
    <li><a href="mailto:Christoph.Schult@iwh-halle.de"><i class="fas fa-fw fa-envelope" aria-hidden="true"></i> Email</a></li>
    <li><a href="https://schultkr.github.io"><i class="fas fa-fw fa-link" aria-hidden="true"></i> Website</a></li>
    <li><a href="https://www.linkedin.com/in/christoph-schult-56aa83147"><i class="fab fa-fw fa-linkedin" aria-hidden="true"></i> LinkedIn</a></li>
    <li><a href="https://orcid.org/0009-0009-1118-2923"><i class="ai ai-orcid ai-fw" aria-hidden="true"></i> ORCID</a></li>
    <li><a href="https://github.com/schultkr"><i class="fab fa-fw fa-github" aria-hidden="true"></i> GitHub</a></li>
    <li><a href="https://scholar.google.com/citations?user=9tm-bzQAAAAJ&hl=en"><i class="ai ai-google-scholar ai-fw" aria-hidden="true"></i> Google Scholar</a></li>
  </ul>

  <div class="business-card__qr">
    <img src="{{ base_path }}/images/card-qr.png" alt="QR code linking to this contact card">
    <p>Scan to save my contact info</p>
  </div>

</div>
