# Week-end JAP 2026

Appli mobile du Week-end JAP (Jeunes Adultes à Paris), 23–25 octobre 2026 à Mandres-les-Roses.

Tout tient dans un seul fichier : `index.html`. Il s'ouvre dans n'importe quel navigateur, sans installation.

## Contenu

- Accueil : compte à rebours, « En ce moment / À suivre », verset du jour, annonces
- Planning jour par jour
- Ateliers et lien de réservation
- Plan du lieu
- Le Mur : liens vers le Padlet (témoignages et photos)
- Versets (Louis Segond 1910) et lien vers la Bible complète
- Récap des célébrations et ateliers

## Installer l'appli sur son téléphone

Une fois le site en ligne sur GitHub Pages, ouvre le lien sur ton téléphone :

- **iPhone (Safari)** : bouton Partager › « Sur l'écran d'accueil ».
- **Android (Chrome)** : menu ⋮ › « Installer l'application » (ou « Ajouter à l'écran d'accueil »).

L'icône JAP apparaît avec les autres applis et l'appli s'ouvre en plein écran.
Les fichiers `manifest.webmanifest`, `icon-192.png` et `icon-512.png` doivent être à côté de `index.html`.

## Modifier le contenu

Le contenu (planning, ateliers, annonces, versets, liens, plan) est rangé dans le bloc
`<script type="application/json" id="app-data">` de `index.html`.

- **Version hébergée sur Claude** : le bouton « Modifier » permet de tout changer sans toucher au code, puis « Publier ».
- **Cette copie GitHub** : le bouton « Modifier » n'apparaît pas. Pour la mettre à jour, remplace `index.html` par la dernière version (ou modifie le bloc `app-data`).

## Charte

Couleurs : Pomelo `#FF744F`, Charcoal `#1B0300`, Blues `#CAE7F7`, Mocha `#822E13`.
Typographies : Archivo Black, Instrument Sans, Instrument Serif (Google Fonts).
