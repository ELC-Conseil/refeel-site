# Écrire un article de blog

Les articles sont dans le dossier `_posts`. Pour en ajouter un :

1. Crée un fichier `_posts/AAAA-MM-JJ-titre-court.md` (par exemple `_posts/2026-12-01-dormir-et-humeur.md`).
   La date du nom de fichier est la date de publication, le titre court devient l'adresse : getrefeel.app/blog/dormir-et-humeur/
2. Commence le fichier par ces lignes :

```
---
title: "Le titre de l'article"
description: "Une ou deux phrases qui résument l'article (affichées dans la liste et dans l'aperçu de partage)."
image: /img/pose-reflexion.webp
teinte: bleu
---
```

   L'image de la carte est la mascotte (`image`) posée sur un fond doux (`teinte` : peche, vert, lavande, bleu ou jaune).
   Poses disponibles dans `img/` : pose-accueil, pose-calme, pose-decouverte, pose-journal, pose-lecture, pose-parametres, pose-reflexion, pose-stats, serenite.
   Pour une vraie photo à la place, dépose-la dans `img/blog/` et ajoute la ligne `couverture: /img/blog/ma-photo.jpg`.

3. Écris le texte en dessous, en Markdown :
   - `## Intertitre` pour un intertitre
   - `**gras**`, `*italique*`
   - `- ` en début de ligne pour une liste, `1. ` pour une liste numérotée
   - `> ` en début de ligne pour une citation mise en avant
   - `[texte du lien](https://adresse)` pour un lien

L'article apparaît automatiquement sur la page Blog, sur l'accueil (le plus récent) et dans le flux RSS, une ou deux minutes après l'enregistrement sur GitHub.
