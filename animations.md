fil---
layout: page
permalink: /animations/
title: A Propos
description: "Nos animations"
imagefeature: fourseasons.jpg
chart: true
---


Attention, cette page est en construction !
=============


Nos animations
--------------

VOus trouvez ici les fiches ateliers des différentes animations que nous proposons, au fablab ou à l'extèrieur.
La liste présentée ici ne sera pas exaustive.
Vous avez un projet? une idée? Vous souhaitez un devis? Contactez-nous !

 < !-- tentative de carroussel défilant à la souris pour afficher les fiches ateliers en partant de https://nickpiscitelli.github.io/Glider.js/ -- >
 
<!DOCTYPE html>
<html lang="fr">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Au Fablab ou dans vs locaux!</title>
<!-- Glider.js CSS -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/glider-js@1/glider.min.css">
  </head>
  <body>
<!-- Glider.js JS -->
<script src="https://cdn.jsdelivr.net/npm/glider-js@1/glider.min.js"></script>

<div class="glider-contain">
  <button aria-label="Previous" class="glider-prev">«</button>
  <div class="glider">
    <div><img src="{{ site.static_url }}/fa_enceintebt.png" alt="Icone d'horloge"></div>
    <div><img src="{{ site.static_url }}/fa_histoire.png" alt="Icone d'horloge"></div>
    
    
  </div>
  <button aria-label="Next" class="glider-next">»</button>
  <div role="tablist" class="dots"></div>
</div>

<script>
  window.addEventListener('load', function(){
    new Glider(document.querySelector('.glider'), {
      slidesToShow: 1,
      dots: '.dots',
      arrows: {
        prev: '.glider-prev',
        next: '.glider-next'
      }
    });
  });
</script>
  </body>

   <div class="glider-contain">
  <button aria-label="Previous" class="glider-prev">«</button>
  <div class="glider">
    <div><img src="{{ site.static_url }}/fa_enceintebt.png" alt="Icone d'horloge"></div>
    <div><img src="{{ site.static_url }}/fa_histoire.png" alt="Icone d'horloge"></div>
    
    
  </div>
  <button aria-label="Next" class="glider-next">»</button>
  <div role="tablist" class="dots"></div>
</div>
 
</html>

