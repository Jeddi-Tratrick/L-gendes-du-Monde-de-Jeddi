# Légendes du Monde

Ce projet comprend un formulaire HTML pour soumettre des légendes du monde entier, connecté à un backend Express.js.

## Structure du projet

- `public/` : Contient le formulaire HTML
- `server/` : Contient le backend Node.js

## Déploiement

### 1. Backend (Render)
- Créez un compte sur [render.com](https://render.com)
- Créez un nouveau Web Service connecté au dossier `server/`
- Build command : `npm install`
- Start command : `node index.js`
- Port : `3000`

### 2. Frontend (Render Static Site)
- Créez un nouveau site statique sur Render
- Connectez le dossier `public/` comme racine

## Exemple
L'URL du backend doit être renseignée dans le `fetch(...)` du fichier HTML.
