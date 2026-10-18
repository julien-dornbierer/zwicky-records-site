# Zwicky Records : site zwickyrecords.com

Site du label Zwicky Records (Biel/Bienne), le label de The Clive. Ce dépôt est **public** : n'y mets
jamais de contrats, de chiffres, de stratégie interne ni de musique non sortie.

## Publication
- `site/` est publié tel quel sur GitHub Pages par `.github/workflows/deploy.yml` à chaque push sur `main`
  (environ 1 minute). Pas de build, pas de dépendances.
- Domaine `www.zwickyrecords.com` (fichier `site/CNAME`). Le domaine nu redirige vers www.
- Après modification : vérifier le rendu (desktop 1280 px + mobile 390 px, aucun scroll horizontal),
  puis commit + push. Rappeler à Julien de recharger avec Ctrl+F5.

## Structure
- `site/index.html` (catalogue), `site/about.html`, `site/booking.html`, `site/style.css`, `site/favicon.svg`.
- Liens relatifs entre pages. GitHub Pages sert aussi `/booking` sans extension : le site the-clive.com
  pointe vers https://www.zwickyrecords.com/booking, cette URL doit rester valide.
- Polices : Archivo et IBM Plex Mono via Google Fonts.
- Charte : manuel de corporate design dans le Drive (PRIVATE EPK > Z999999 __ ZWICKY-RECORDS).

## Contenu
- Catalogue : ZWR 001, The Clive, CGCG Volume IX.
- Booking : Nora Weber, booking@zwickyrecords.com (Switzerland and international).
- Site en anglais uniquement.
