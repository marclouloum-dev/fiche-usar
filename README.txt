# Fiche USAR — PWA

Application web progressive (PWA) de la fiche technique de détachement USAR.

## Installation
1. Décompresser le dossier.
2. Héberger son contenu sur un serveur HTTPS (ou utiliser localhost pour les tests).
3. Ouvrir `index.html` via l'adresse du serveur.
4. Sur Android/Chrome ou Edge : utiliser « Installer l'application » / « Ajouter à l'écran d'accueil ».

La fiche fonctionne hors connexion après sa première ouverture grâce au Service Worker.

## Fichiers
- index.html : application
- manifest.webmanifest : configuration PWA
- sw.js : fonctionnement hors connexion et cache
- icon.svg : icône de l'application
