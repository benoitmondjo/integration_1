## Exercice : Création de la version Responsive du site

### Objectif

Votre mission est de proposer une **version responsive** du site web que vous avez réalisé précédemment.  
Le site doit pouvoir **s’adapter correctement aux différents types d’écrans** : ordinateur, tablette et smartphone.

### Consignes

1. Analysez la version actuelle du site.
2. Identifiez les éléments qui doivent être adaptés pour les petits écrans :
   - navigation
   - disposition des sections
   - images
   - textes
3. Mettez en place une **version responsive** en utilisant les techniques CSS appropriées :
   - **Media Queries**
   - **Flexbox et/ou Grid**
   - unités flexibles (`%`, `rem`, `vh`, `vw`, etc.).

### Livrables attendus

Vous devez fournir dans votre dépôt Git :

- Le **code mis à jour** du site avec la version responsive.
- Une **description dans ce README** expliquant :
  - les choix réalisés pour adapter le site
  - les breakpoints utilisés (mobile, tablette, desktop)
  - les principales modifications apportées au layout.

### Critères d’évaluation

- Bonne adaptation du site aux différents écrans
- Utilisation correcte de **Flexbox / Grid**
- Organisation et lisibilité du code
- Qualité de la documentation dans le README






## Explication des choix éffectués pour le responsive du site web

### Parites concernées par les modifications

   -Les modifications concernent en premier lieu la section ayant la classe **first-section**. Il était necéssaire de disposer en colone les sections enfants ayant les classes **left-section** et **right-section** pour que le site soit mieu présenté sur les smartphones.

   -Ensuite, il fallait améliorer la présentation des services de la section **services-section** pour que ces derniers soit mieu présenté sur les smartphones. Une disposition en colone est plus appropier. 

   -Toutes ces modifications s'appliquent aux smatphones, soit des écans compris entre *** 0px à 767px ***