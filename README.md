# Foyer – Tâches ménagères

PWA de gestion des tâches ménagères pour une famille de 5 (Ludivine, Mickael, Tess, Lukas, Manon).
Objectif de répartition : 40 % parents / 60 % enfants. Base de données : Firebase Firestore.

## Installation
1. Créer un projet Firebase et une base Firestore.
2. Renseigner `FIREBASE_CONFIG` dans `index.html`.
3. Copier `firestore.rules` dans l'onglet Règles de Firestore.
4. Publier avec GitHub Pages (Settings > Pages > Deploy from a branch > main / root).

## Fichiers
- `index.html` : application
- `sw.js` : service worker (mode hors ligne)
- `manifest.json`, `icon.svg` : installation PWA
- `firestore.rules` : règles de sécurité de la base
