# BagAway

Site vitrine BagAway — location de bagages premium.

## Structure du projet

```text
BagAway/
├── index.html
├── README.md
└── assets/
    ├── css/
    │   └── styles.css
    ├── js/
    │   └── main.js
    └── images/
        └── ... images du catalogue
```

## Lancer le site en local

Ouvre simplement `index.html` dans ton navigateur. Pour un aperçu plus fiable, tu peux aussi utiliser l'extension **Live Server** de Visual Studio Code.

## Publier sur GitHub Pages

1. Crée un dépôt GitHub, par exemple `bagaway`.
2. Envoie tous les fichiers et dossiers de ce projet à la racine du dépôt.
3. Dans le dépôt, ouvre **Settings → Pages**.
4. Dans **Build and deployment**, choisis **Deploy from a branch**.
5. Sélectionne la branche `main` et le dossier `/ (root)`, puis valide.
6. Attends la publication : GitHub affichera l'adresse de ton site dans cette même page.

Le fichier d'entrée doit rester nommé `index.html` et se trouver à la racine du dépôt.

## À savoir

- Les styles sont dans `assets/css/styles.css`.
- Les interactions JavaScript sont dans `assets/js/main.js`.
- Les images JPEG intégrées à l'ancien fichier HTML ont été extraites dans `assets/images/`.
- Les polices Google Fonts sont chargées depuis Internet ; elles nécessitent une connexion.
- Les liens et fonctionnalités qui nécessitent un vrai service serveur (authentification, paiement ou réservation réelle) doivent être reliés à un backend avant une mise en production.
