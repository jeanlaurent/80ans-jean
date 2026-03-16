# Projet : Landing page 80 ans Jean Fabre de Morlhon

## Contexte du projet

Site web statique (`index.html`) servant de landing page pour une collecte cadeau à l'occasion des **80 ans de Jean Fabre de Morlhon**, célébrés le **12 août 2026** à **Villefranche-de-Panat, Aveyron**.

La famille Fabre de Morlhon est enracinée en Aveyron depuis plus d'1 siècle. Le rassemblement a lieu chaque été dans deux maisons familiales rénovées pouvant accueillir 20+ personnes.

## Fichiers du projet

- `index.html` — page unique, entièrement statique (HTML/CSS/JS pur)
- `IMG_*.jpeg` — 6 photos utilisées dans le diaporama hero
- `CNAME` — domaine custom `80ans.morlhon.net` pour GitHub Pages

## Déploiement

- Repo GitHub : `git@github.com:jeanlaurent/80ans-jean.git`
- URL GitHub Pages : `https://jeanlaurent.github.io/80ans-jean/`
- Domaine custom configuré : `https://80ans.morlhon.net` (DNS CNAME à pointer vers `jeanlaurent.github.io`)
- Branche : `main`, source `/` (root)

## Lien collecte

`https://www.leetchi.com/fr/c/80-ans-de-jean-1594489`

## Contact

`80ans-jean@morlhon.net`

## Conventions de style

- **Langue** : français uniquement
- **Ton** : sobre, élégant, chaleureux — style maison de famille française
- **Typographie** : Cormorant Garamond (Google Fonts)
- **Palette** : tons pierre et nature — beige lin (`#f0e9dc`), taupe, or discret (`#b8966e`), fond crème
- **Ponctuation** : utiliser `;` à la place des tirets `—` dans les textes
- **Vocabulaire** : dire "collecte" et non "cagnotte" (trop familier)
- Pas d'emojis, pas de fioritures

## Structure de la page

1. **Hero plein écran** — diaporama des 6 photos (10s/photo), fondu 1.6s, bouton pause + dots de navigation
2. **Section principale** — annonce de l'événement, texte sobre, bloc collecte avec bouton Leetchi
3. **Section lieu** — Villefranche-de-Panat, histoire de la famille
4. **Footer** — copyright 2026 + email cliquable

## Points importants

- La participation à la collecte est **entièrement facultative** — ce qui compte avant tout c'est la présence des gens
- Le site est **public** : rester sobre, ne pas mentionner de détails privés
- Toujours pousser sur GitHub après modifications : `git add <fichiers> && git commit -m "..." && git push`
