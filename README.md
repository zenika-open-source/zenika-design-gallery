# 🎨 Zenika Design Gallery

Ce projet est une vitrine regroupant nos plus beaux visuels créés pour les conférences (DevFest, Mix-IT, Devoxx, etc.) et les événements Zenika.

## 📸 Comment ajouter un nouveau visuel ?

1.  Ajoutez votre image dans le dossier `public/img/visuals/`.
2.  Ajoutez une nouvelle entrée dans `src/data/visuals.json` :
    ```json
    {
      "id": "nom-unique",
      "title": "Titre du Visuel",
      "occasion": "Courte description de l'événement",
      "year": 2024,
      "image": "/img/visuals/votre-image.png"
    }
    ```

##  Genie Commands

| Commande                  | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Lance le serveur local sur `localhost:4321`      |
| `npm run build`           | Compile le site statique dans `./dist/`          |
| `npm run preview`         | Prévisualise le build localement                 |

## 🚢 Déploiement

Le site est configuré pour se déployer automatiquement sur **GitHub Pages** via GitHub Actions à chaque push sur la branche `main`.

![with love by zenika](https://img.shields.io/badge/With%20%E2%9D%A4%EF%B8%8F%20by-Zenika-b51432.svg?link=https://oss.zenika.com)
