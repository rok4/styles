# Styles

Ces styles sont utilisés dans le projet ROK4 au niveau de la génération des pyramides de données raster (styles "complexes", quand le valeur finale d'un pixel dépend des valeurs initiales du voisinage, comme le calcul de pente ou d'ombrage), ou à la volée au niveau du serveur à la diffusion (styles "simple", quand la valeur finale d'un pixel ne dépend que de sa valeur initiale, comme l'application d'une palette).

## Comment définir un style ?

Pour la palette des couleurs, on a les 4 canaux: rouge, bleu, vert et alpha.

L'objet Style contient la palette à créer.

Les paramètres de pente contiennent une valeur maximale de pente et des valeurs "flag" ou nodata "9999".

Les paramètres d'exposition contiennent des paramètres de valeur de pente pour laquelle l'exposition est calculée, le nom de

l'algorithme de calcul de la pente.

Les paramètres d'estompage contiennnet les valeurs azimuthales du soleil et la position zénithale du Soleil en degrés, le facteur

d'exagération de la pente, et des valeurs flag pour l'estompage.

Pour la légende du style, elle contient :
*   la légende et l'url de l'image,
*   la hauteur et la largeur du pixel de l'image,
*   l'échelle minimale et maximale pour laquelle la légende est appliquée.

![ROK4 STYLE](https://github.com/rok4/core-python/tree/feature/doc-new-users/HOWTO.md#exemple-de-style-du-projet-rok4-)

## Installation via le paquet debian

Télécharger le paquet [sur GitHub](https://github.com/rok4/styles/releases/).

```
apt install ./rok4-styles-4.0-linux-all.deb
```

Les fichiers seront installés dans le dossier `/etc/rok4/styles`.
