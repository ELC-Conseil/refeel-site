# Site de Refeel

Le site de l'application Refeel, en ligne sur https://getrefeel.app (hébergé gratuitement par GitHub Pages, qui construit le site avec Jekyll).

- `index.html` : accueil (fond animé de captures, téléphone, détail de l'app, offre, questions) · `en/index.html` : la même en anglais
- `confidentialite/` · `conditions/` · `aide/` et leurs équivalents dans `en/`
- `blog/` : la liste des articles et le flux RSS ; les articles eux-mêmes sont dans `_posts/` (voir `LISEZMOI-blog.md`)
- `_layouts/` : l'enveloppe commune (en-tête, menu, pied de page, aperçu de partage) et la mise en page des articles
- `_data/textes.yml` : menus et pied de page en français et en anglais · `_data/ecrans.yml` : les captures du fond animé
- `_config.yml` : réglages, dont l'identifiant App Store qui alimente les boutons et la bannière Safari
- `img/ecrans/` : les captures de l'app (fr, en) · `img/partage.jpg` : l'image des aperçus de partage
- `style.css` : reprend la charte de l'app (fond pêche, cartes en verre, police Newsreader, corail)
- `CNAME` : le nom de domaine

Pour voir le site en local : `jekyll serve`, puis http://localhost:4000
