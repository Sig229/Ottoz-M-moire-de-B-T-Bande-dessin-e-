# OTTOZ : La Mémoire de BÂT — Lecteur BD en 3D

Lecteur interactif en 3D pour la bande dessinée « Mémoire de BÂT », en lien avec l'univers du jeu **OTTOZ**.

## 🚀 Voir le lecteur en ligne

Une fois GitHub Pages activé sur ce dépôt (voir plus bas), le lecteur sera accessible à :

```
https://VOTRE-PSEUDO-GITHUB.github.io/NOM-DU-DEPOT/
```

## 📦 Contenu du dépôt

- `index.html` — le lecteur BD complet (3D, Three.js, images encodées directement dans le fichier)
- `.nojekyll` — désactive le traitement Jekyll de GitHub Pages (nécessaire pour servir le fichier tel quel)

## 🛠️ Activer GitHub Pages

1. Sur GitHub, ouvrez ce dépôt puis allez dans **Settings** (Paramètres)
2. Dans le menu de gauche, cliquez sur **Pages**
3. Sous **Build and deployment** → **Source**, sélectionnez **Deploy from a branch**
4. Choisissez la branche `main` et le dossier `/ (root)`, puis cliquez sur **Save**
5. Patientez 1 à 2 minutes : l'URL de votre site apparaît en haut de la page Pages

## ⚠️ À savoir

- Le lecteur nécessite une **connexion internet** au chargement : il utilise la bibliothèque graphique Three.js chargée depuis un CDN (jsDelivr). Sans connexion, un message d'erreur clair s'affiche avec un bouton pour recharger.
- Le fichier `index.html` fait environ 9 Mo (images de la BD encodées en base64 à l'intérieur du fichier). GitHub accepte les fichiers jusqu'à 100 Mo, donc aucun souci pour l'héberger.
- Compatible Safari, Chrome, Firefox et autres navigateurs modernes supportant WebGL.

## ✍️ Autrice

Sigrid-Solène Shirley HEKPAZO (@shirley_officiel00 sur Instagram)
