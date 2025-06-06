# fablablannion.github.io


fablablannion.github.io est le site web du FabLab de Lannion (France)
Ce site web est libre et basé sur Jekyll et le superbe theme Notepad.
Les lecteurs du Fablab étant majoritairement francophones, la documentation
de ce projet est en français.

---

fablablannion.github.io is the static website for the FabLab of Lannion (France).
This website is free and base on Jekyll and the awesome Notepad theme. The people
reading this website is mainly french speaking, so the documentation is in
french.


# Comment contribuer à la ligne éditoriale ?

Il y a trois solutions pour écrire un article:
* être un contributeur du projet fablablannion.github.io
* faire une contribution externe via un *pullrequest* sur GitHub
* envoyer l'article par mail à l'adresse contact AT fablab-lannion.org

## Créer un nouvel article

Pour créer un article, il faut avant tout créer un fichier enregistrer dans
le dossier ```_posts``` avec un nom de fichier formater de cette manière:

```
 YEAR-MONTH-DAY-title.md
```

Comme par exemple:

```
 2011-12-31-new-years-eve-is-awesome.md
 2012-09-12-how-to-write-a-blog.md
```

## Rédiger un article:

Les articles sont à rédiger au format *MarkDown*:
* [Markdown sur Wikipedia](https://fr.wikipedia.org/wiki/Markdown)
* [Markdown sur OpenClassRoom](https://openclassrooms.com/courses/redigez-en-markdown)

Le fichier doit commencer par un bloc *Front Matter* avec au minimum les
informations suivantes:

```
  ---
  author: johndoe
  layout: post
  title: "Le titre du billet de blog"
  comments: True
  share: True
  ---
```

* **author**: Le pseudo de l'auteur. Ce pseudo doit correspondre à la description de l'auteur renseignée dans le fichier *_config.yaml*.
si vous n'apparaissez pas dans ce fichier de configuration, n'hésitez pas à le modifier
* **description**: Description de l'article, utilisé par Facebook Opengraph & Twitter
* **layout**: \[post, page\] le format de la page, laisser *post* pour un billet de blog
* **title**: Titre du billet
* **comment**: \[True, False\] Activer ou non les commentaires sur la page
* **share**: \[True, False\] Activer ou non les boutons de partage sur la page

Plusieurs options sont disponibles:

* **tags**: \[tag1, tag2\] liste des étiquettes à attacher à l'article
* **headline**: Sous titre
* **modified**: Date corrigée de l'article, au format ```YEAR-MONTH-DAY``` (2016-10-16 par exemple)
* **imagefeature**: *filename.jpg* d'une image du dossier ```/image``` ou l'*url*
d'une image utilisée pour la couverture


## Formatage avancé

Le formatage [Foundation Grid](https://get.foundation/sites/docs/grid.html) est
possible, ou tout autre formatage HTML

## Insérer une image

Pour insérer une image, il faut utiliser la syntaxe suivante:

```
 ![cover-image](https://path-to-your-image.jpg)
```

si l'image est incluse dans le site:

```
 ![cover-image]({{ site.url }}/images/filename.jpg)
```

si elle est issue de notre stockage statique sur OVH:

```
 ![cover-image]({{ site.static_url }}/filename.jpg)
```

## Ajouter un auteur

Completer le fichier *_config.yml*:

```
authors:
    [...]
    johndoe:
        name: John Doe
        function: Dictateur
        description: Dictateur
        gravatar: 1055c2123456d9878befb9c8810eda96dc
        twitter: johndoe
        github: johndoe
        facebook: johndoe
        google_plus: +johndoe
```

# Comment contribuer au design et fonctionnalité du site

Nous sommes ouvert à tout *Pull Request* :)

Les principales sources de documentations sont ici:

* [Jekyll](https://jekyllrb.com/docs/home/)
* [Notepad Theme](https://github.com/hmfaysal/Notepad)

Pour tester les modifications il y a deux solutions:

* [Tester le site en local](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/)
* Forker sur votre compte github et tester les modifications sur votre site:
 * [Forker](https://guides.github.com/activities/forking/) le projet fablablannion/fablablannion.github.io sur votre compte
 * Renommer le projet de la manière suivante: ```<votrecompte>.github.io```
 * modifiez la configuration du projet:
```
title:            association KerNEL - site de test
repository:       <votrecompte>/<votrecompte>.github.io
url:              https://<votrecompte>.github.io
```
