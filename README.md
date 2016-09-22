# Base Template

## Objectif
Une structure minimale pour débuter une intégration Web.

Le fichier css/base.css, devrait éviter les problèmes récurrents des ```reset.css```et ```normalize.css```, décrits dans cet article:

[FORGET NORMALIZE OR RESETS; LAY YOUR OWN CSS FOUNDATION](http://jaydenseric.com/blog/forget-normalize-or-resets-lay-your-own-css-foundation).

Comme conseillé par l'auteur, on rajoute les fondations qu'on juge indispensables:
* utilisation du modèle de boite **border-box**
* images et médias responsive
* taille de caractères de base à 62.5% de la taille par défaut, pour simplifier la conversion **px** vers **em**.

## Liens
* [* { Box-sizing: Border-box } FTW](http://www.paulirish.com/2012/box-sizing-border-box-ftw/)
* [L’astuce du font-size: 62.5%; oui, non ou « ça dépend » ?](https://blog.goetter.fr/2016/07/05/lastuce-du-font-size-62-5-oui-non-ou-ca-depend/)
