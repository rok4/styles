# Styles

Ces styles sont utilisés dans le projet ROK4 au niveau de la génération des pyramides de données raster (styles "complexes", quand le valeur finale d'un pixel dépend des valeurs initiales du voisinage, comme le calcul de pente ou d'ombrage), ou à la volée au niveau du serveur à la diffusion (styles "simple", quand la valeur finale d'un pixel de dépend que de sa valeur initiale, comme l'application d'une palette).

## Installation via le paquet debian

Télécharger le paquet [sur GitHub](https://github.com/rok4/styles/releases/).

```
apt install ./rok4-styles_4.0_all.deb
```

Les fichiers seront installés dans le dossier `/etc/rok4/styles`.
