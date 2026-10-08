# Personal Portfolio (exercice freeCodeCamp)

Page de portfolio personnelle en HTML et CSS, présentant trois de mes projets, réalisée pour le lab « Build a Personal Portfolio » de freeCodeCamp.

> C'est un exercice d'entraînement : la structure demandée (navbar, accueil, grille de projets, contact) vient du lab, et les trois tuiles pointent vers mes vrais projets.

![Statut](https://img.shields.io/badge/statut-terminé-brightgreen)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222?logo=github&logoColor=white)

## Ce que j'ai mis en pratique

- **Transitions CSS** : `transition` sur `transform` et `box-shadow` pour soulever les tuiles au survol, et sur la couleur du bouton de contact.
- **Accessibilité des animations** : un bloc `prefers-reduced-motion` désactive les transitions et le déplacement pour les personnes qui demandent moins de mouvement.
- **Grid et Flexbox** : grille `repeat(auto-fit, minmax(250px, 1fr))` pour les tuiles, Flexbox pour la navbar et le centrage des sections.
- **Variables CSS** : trois couleurs d'accent centralisées dans `:root`.
- **Responsive et bases d'accessibilité** : media query à 600 px, `alt` descriptifs, `:focus-visible`, `<header>` et `<main>`, `rel="noopener noreferrer"` sur les liens externes.

## Démo en ligne

[https://docaridr.github.io/personnal-portfolio-freecodecamp/](https://docaridr.github.io/personnal-portfolio-freecodecamp/)

## Technologies utilisées

HTML5 et CSS3, sans JavaScript ni bibliothèque externe.

## Installation locale

```bash
git clone https://github.com/DocariDR/personnal-portfolio-freecodecamp.git
cd personnal-portfolio-freecodecamp
```

Puis ouvre `index.html` dans ton navigateur.

## Structure des fichiers

```
personnal-portfolio-freecodecamp/
├── index.html
├── styles.css
├── images/
│   ├── magazine.png
│   ├── ferris-wheel.png
│   └── flappy-pinguin.png
└── README.md
```

## Auteur

**Ricardo Dovonou** (DocariDR)

- GitHub : [github.com/DocariDR](https://github.com/DocariDR)
- LinkedIn : [linkedin.com/in/ricardo-dovonou](https://linkedin.com/in/ricardo-dovonou)
- X : [x.com/DocariDR](https://x.com/DocariDR)
- Bluesky : [bsky.app/profile/docaridr.bsky.social](https://bsky.app/profile/docaridr.bsky.social)
- Portfolio : [portfolio-docaridr.vercel.app](https://portfolio-docaridr.vercel.app)