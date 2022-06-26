# Styles ROK4

## Summary

Le projet ROK4 a été totalement refondu, dans son organisation et sa mise à disposition. Les composants sont désormais disponibles dans des releases sur GitHub au format debian.

Cette release contient les styles, utilisés par les outils de génération (styles "complexes", quand le valeur finale d'un pixel dépend des valeurs initiales du voisinage, comme le calcul de pente ou d'ombrage) et le serveur de diffusion (styles "simple", quand la valeur finale d'un pixel de dépend que de sa valeur initiale, comme l'application d'une palette).

## Changelog

### [Changed]

* Tous les styles ont été mis au format JSON, dont les spécifications sont décrites sous forme de [schéma JSON](style.schema.json) dans le projet.

<!-- 
### [Added]

### [Changed]

### [Deprecated]

### [Removed]

### [Fixed]

### [Security] 
-->