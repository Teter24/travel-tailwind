# Horizon - Travel Website

Ce projet est une landing page moderne pour une agence de voyage fictive nommée "Horizon". Il met en avant des destinations exotiques, des témoignages clients et des offres de tours.

## Fonctionnalités

- **Design Responsive** : Adapté aux mobiles, tablettes et ordinateurs de bureau.
- **Menu Mobile** : Navigation fluide avec un menu déroulant sur les petits écrans.
- **Sections Clés** :
  - Hero Header avec image de fond immersive.
  - Section "About Us" avec statistiques.
  - "Popular Accommodation" avec cartes de présentation.
  - "Why Choose Us" avec accordéon interactif (visuel).
  - "Top Tours" avec mise en page personnalisée.
  - Témoignages clients.

## Technologies Utilisées

- **HTML5** : Structure sémantique.
- **Tailwind CSS** : Framework CSS utilitaire pour le style rapide et responsive.
- **Font Awesome** : Pour les icônes (via CDN).
- **Google Fonts** : Police "Poppins".
- **NestJS** : Utilisé comme serveur backend pour servir les fichiers statiques (structure du projet).

## Installation et Lancement

1.  **Installer les dépendances** :

    ```bash
    npm install
    ```

2.  **Lancer le serveur de développement** :

    ```bash
    npm run start:dev
    ```

3.  **Accéder au site** :
    Ouvrez votre navigateur et allez sur `http://localhost:3000`.

## Structure des Fichiers

- `public/index.html` : Le fichier principal contenant la structure et le contenu de la page.
- `public/tailwind.css` : Le fichier CSS généré par Tailwind (ou importé).
- `src/` : Code source du serveur NestJS.
