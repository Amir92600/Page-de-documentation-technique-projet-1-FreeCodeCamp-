# Documentation Technique

Ce projet est réalisé dans le cadre de ma certification **Responsive Web Design** sur FreeCodeCamp. Il s'agit d'une page de documentation technique construite en HTML et CSS qui présente, de manière claire et structurée, les différents aspects d'une application fictive ou d'un projet technique.

---

## Objectifs du Projet

Le projet doit répondre aux consignes suivantes :

- **Structure HTML conforme aux user stories**  
  - Un élément `<main>` avec l'id `main-doc` qui contient le contenu principal.
  - Au moins cinq `<section>` avec la classe `main-section`.
  - Chaque section commence par un `<header>` décrivant son sujet.
  - L'attribut `id` de chaque section correspond au texte de son `<header>` (les espaces sont remplacés par des traits de soulignement).
  - Les sections contiennent au moins dix `<p>`, cinq `<code>` et cinq `<li>` au total.
- **Navigation**  
  - Un élément `<nav>` avec l'id `navbar` toujours visible sur le côté gauche sur grand écran.
  - Le `<nav>` contient un `<header>` et des liens `<a>` (classe `nav-link`) qui correspondent chacun à une section.
  - Le texte des liens correspond exactement au texte des `<header>` de chaque section, et leur attribut `href` pointe vers l'id de la section associée.
- **Responsive Design**  
  - Une ou plusieurs requêtes média sont utilisées pour adapter l’affichage sur différents types d’appareils.

---

## Structure du Projet

L'arborescence du répertoire est la suivante :

Documentation-Technique/ 

├── index.html # La page HTML principale 

├── styles.css # La feuille de style CSS 

└── README.md # Ce fichier de documentation
