---
layout: help
category: Help
title: Bonnes pratiques
permalink: fr/help/1_5/best_practices/
---

[<< Retour][3]  

Si tu veux améliorer l'apparence de tes nouvelles galeries dans l'app et utiliser le filtre de contenu explicite, cette section décrit comment sont interprétées les dossiers de galeries dans l'app. Grâce à ces infos, tu pourras les peaufiner à leur plein potentiel.

### Anatomie d'une galerie

Voici un schema montrant comment les informations du dossier et ses images sont utilisées pour afficher le contenu de la galerie dans l'app :

![Montre comment la liste des fichiers correspond au rendu de la galerie dans l'app][1]

Voici la description de chaque élément :

- **Nom de la galerie :** le nom de la galerie est simplement le nom du dossier, tel quel.
- **Imagette :** Pour l'imagette, il y a deux options :
    - Si rien de spécial n'est fait, l'app utilise une image du dossier au hasard et la recadre au format carré.
    - Pour avoir un meilleur rendu, ajoute simplement une image supplémentaire dans ton dossier. Nomme-là exactement `gallery_thumb.jpg`. Pour de meilleures performances et un meilleur rendu, cette image doit être _carrée avec une taille de 500x500px_.
- **Images de la galerie :** Les images utilisées comme poses dans tes sessions de dessins, inclus toutes les images présentes directement dans le dossier de galerie à l'exception de l'image nommée `gallery_thumb.jpg` si elle existe.
- **Filtre de contenu explicite:** Par défaut, toutes les images sont considérées comme explicites. Donc, si rien de spécial n'est fait, quand tu actives le filtrage dans l'app, tes galeries seront grisées avec la mention "0 pose" sous leur nom. Pour marquer une image comme sûre, ajoute simplement les caractères `-safe-` n'importe où dans le nom du fichier de celle-ci. Toutes les images marquées ainsi resterons disponibles quand le filtrage est activé.

![montre comment le nom de l'image est utilisé dans les résultats d'une session][2]

Note également que, comme montré dans l'image ci-dessus, le nom des fichiers est utilisé quand l'app affiche les résultats d'une session.

**Note:**
> Tu peux faire ses changements directement dans le dossier de ta galerie situé à l'emplacement `Sur mon iPad/QuickPoses`, pas besoin de remplacer le dossier complètement à chaque fois si ce n'est pas absolument nécessaire.

[<< Retour][3]

[1]: ../../../../img/help/anatomy-gallery.png "Anatomie d'une galerie"
[2]: ../../../../img/help/image-name-usage.png "Comment est utilisé le nom d'une image"
[3]: ../add_more_galleries/