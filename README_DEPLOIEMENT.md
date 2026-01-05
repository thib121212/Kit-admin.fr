# Déploiement du site « Kit Admin France »

Ce dossier contient le site statique prêt à publier.

## Étapes GitHub Pages
1. Créez un dépôt GitHub (ex. `kit-admin-fr`).
2. Ajoutez tous les fichiers du dossier (ou utilisez l'archive `.zip`).
3. Validez sur la branche `main`.
4. Allez dans **Settings → Pages**.
   - **Source** : *Deploy from a branch*
   - **Branch** : `main`, **Folder** : `/ (root)`
5. Sauvegardez. L'URL publique sera de la forme : `https://<votre-pseudo>.github.io/kit-admin-fr/`.

## Intégration Gumroad
- Remplacez les URLs de placeholder :
  - Kit Base : `https://gum.co/kit-base-placeholder`
  - Kit Plus : `https://gum.co/kit-plus-placeholder`
- Par vos liens réels Gumroad (ex. `https://gum.co/xxxxxx`).

## Personnalisation email de contact
- Dans `assets/script.js`, remplacez `contact@votre-email.exemple` par votre adresse.

## Pages légales
- Complétez `mentions.html` (Nom, adresse, SIREN le cas échéant).
- Adaptez `confidentialite.html` et `cgv.html` à votre situation.
