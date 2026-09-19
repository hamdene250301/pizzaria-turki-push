# Pizzaria Turki — Site Web (Nouvelle Version)

## Structure des fichiers
```
pizzaria-turki/
├── index.html      ← la page complète (CSS + JS inclus)
└── assets/
    ├── hero.jpg    ← photo pizza du hero (enhancée)
    ├── menu.jpg    ← menu original boutique
    ├── story.jpg   ← photo calzone
    ├── g1.jpg      ← galerie
    ├── g2.jpg      ← galerie
    └── g3.jpg      ← galerie
```

## Publication depuis zéro sur GitHub Pages

1. Créer un nouveau repository nommé **pizzaria-turki** sur github.com
   (compte : hamdene250301 → Repositories → New → nom : `pizzaria-turki` → Public → Create)
2. Cliquer **"uploading an existing file"**
3. Glisser-déposer `index.html` puis le dossier `assets` avec les 6 images
4. Cliquer **Commit changes**
5. Activer Pages : Settings → Pages → Source : **Deploy from a branch** → Branch : **main** / (root) → Save
6. Attendre 1-2 minutes → le site est en ligne sur :
   **https://hamdene250301.github.io/pizzaria-turki/**

## Modifier le site
Tout est dans `index.html` (textes, prix, couleurs en haut dans `:root`).
- Téléphone : chercher `52235956`
- Prix/menu : chercher `const MENU={`
- Favoris du carrousel 3D : chercher `const FAVORIS=[`
