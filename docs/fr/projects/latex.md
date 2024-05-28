---

## CV

Pour mon CV? j'ai principalement utilisé le très populaire modèle altacv, et ce, afin de garder l'identité visuel charactéristique de LaTeX sans avoir quelque chose de trop simple. Un compromis entre un CV très académique et un modèle utilisable par mes proches non-informaticiens était recherché. Afin de rester encore plus ésthétique, j'ai décide d'ajouter 6 différentes palettes de couleurs pour rapidement changer de thème. J'ai également utilisé la fameuse bibliothèque Tikz to ajouter deux blocks de couleur : un pour l(en-tête et un pour la colonne de droite, afin d'imiter certain modèle Canvas à la mode.

!!! warning
    Ce modèle est assez ancien et ne respecte pas mes attentes actuelles en terme d'organisation et de propreté du code. Une nouvelle version avec une nouvelle classe de document devrait arriver rapidement. :octicons-clock-16:

---

## Cartes de visite

TeX, en tant que language de balisage, et LaTex par extension, ont été crée afin de gérer automatiquement la typographie et la mise en page de document, et de manière générale, à quoi ils ressemblent visuellement. Cependant, au fur et à mesure de mes rencontres avec des types de documents où je devais faire manuellement la mise en page (les diapositives avec Beamer, les CV avec AltaCV), j'ai décidé de m'attaquer à une tâche un peu plus difficile en terme de mise en page : créer des cartes de visites avec LaTeX.

![Image title](../../assets/card.png)

Ce modèle est inspiré les modèles [business-cards-latex](https://github.com/aorthey/business-cards-latex) d'Andreas Orthey et [business-card](https://github.com/opieters/business-card) d'Olivier Pieters. Mon modèle utilise principalement la bibliothèque Tikz pour la partie graphique. La bibliothèque Qrcode a été utilisé pour généré un qrcode renvoyant vers ce site. Enfin, toutes les icones proviennent de la bibliothèque Fontawesome.

!!! note
    La bibliothèque Qrcode permet de créer de nombreux qrcodes différents, notamment des qrcodes renvoyant une vCard(Virtual Contact File). C'est une bibliothèque assez intéressante que je recommande sincérement. Je pense qu'il est toujours mieux d'utiliser LaTeX pour générer des qrcodes que de les télécharcher d'un site web externe. (Après tout si LaTeX est Turing complet[^1], nous serions fou de ne pas en profiter plainement.)

[^1]:
    Si le site web d'Overleaf nous dit que le lien vers l'artivle original est mort, iels nous donnent un [article complémentaire](https://pbelmans.ncag.info/blog/2010/12/12/a-turing-machine-in-latex-follow-u/) par Pieter Belmans (2010). Je recommande cette lecture particulièrement intéressante. Pour plus de drôlerie Turing compléte (toujours fourni par le site web d'Overleaf), l'on peut aussi lire : 

    * [This is a Universal Turing Machine (UTM) implemented in Conway's Game of Life](http://rendell-attic.org/gol/utm/index.htm) (Ceci est une Machine de Turing Universelle implémenté dans le Jeu de la Vie de Conway)
    * [La playlist Youtube des Machines de Turing dans Minecraft](https://www.youtube.com/results?search_query=minecraft+turing+machine)