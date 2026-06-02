# Mini-Site Personnel - Exercice 10

Ce projet est un mini-site personnel réalisé dans le cadre du module Développement Web 1. Il regroupe les concepts vus dans les exercices précédents (HTML5, CSS3, Flexbox, Grid, Formulaires).

## Structure du Projet

- `index.html` : Page d'accueil avec une présentation et une photo.
- `projets.html` : Galerie de projets présentée sous forme de grille CSS Grid.
- `cv.html` : CV complet incluant la formation (sous forme de tableau), les compétences et les expériences.
- `contact.html` : Formulaire de contact avec validation native HTML5.
- `style.css` : Fichier de styles unique regroupant toute la mise en forme.
- `CVimage.png` : Photo de profil utilisée sur la page d'accueil.

## Choix de Design (Redesign Style Roadmap.sh)

- **Palette de couleurs** : Thème sombre profond (`#0b0b0b`) avec un accent **Vert Lime** (`#c5ff41`) pour un contraste maximal et un aspect technologique moderne.
- **Typographie** : Utilisation de polices sans-serif audacieuses (`Inter`) avec des titres massifs et un espacement généreux.
- **Mise en page** : 
    - **Header** : Minimaliste et collant (sticky) avec effet de flou (glassmorphism).
    - **Hero** : Titre percutant avec typographie de grande taille.
    - **Cards** : Bordures arrondies (20px) et effets de survol élégants.
- **Responsivité** : Entièrement repensée pour conserver l'impact visuel sur tous les écrans.
- **Bonus** : Mode sombre natif et animations de transition fluides.

## Bonus Implémentés

- **Mode Sombre** : Support automatique du mode sombre via la media query `prefers-color-scheme`.
- **Animations** : Animation `@keyframes` d'apparition (`fadeIn`) sur l'image de profil en page d'accueil.
