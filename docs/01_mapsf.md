---
output: html_document
editor_options: 
  chunk_output_type: console
---



# mapsf  {#chapitre1}

L’écosystème spatial du logiciel libre R est riche, dynamique et mature et plusieurs packages permettent d’importer, de traiter et de représenter les données spatiales. Le package [`mapsf`](https://CRAN.R-project.org/package=maps) [@R-mapsf] s’appuie sur cet écosystème pour intégrer la création de cartes thématiques de qualité dans les chaines de traitement avec R.  

Dautres packages peuvent être utilisés pour réaliser des cartes thématique. Le package `ggplot2` [@Wickham16], en association avec le package `ggspatial` [@R-ggspatial], par exemple permet d'afficher des objets spatiaux et de réaliser des cartes thématiques simples. Le package `tmap` [@Tennekes18] est dédié à la création de cartes thématiques, il utilise une syntaxe proche de celle de `ggplot2` (enchaînement d'instructions combinées avec le signe '+'). La documentation et les tutoriels pour utiliser ces deux packages sont facilement accessibles sur le web.

Ici nous utiliserons principalement le package `mapsf` dont les fonctionnalités sont assez complètes et la prise en main assez simple. De plus le package est assez léger. 



## Présentation

<img src="img/logo.png" align="right" alt="" width="120" />

`mapsf` permet de créer la plupart des types de carte utilisés habituellement en cartograpie statistique (carte choroplèthes, typologies, symboles proportionnels ou gradués…).  
Pour chaque type de carte plusieurs paramètres permettent de personnaliser la représentation cartographique, ces paramètres sont les même que ceux que l’on retrouve dans les logiciels de SIG ou de cartographie usuels (par exemple le choix des discrétisations et des palettes de couleurs, modifications des taille des symboles ou la personnalisation des légendes).  
Associées aux fonctions de représesentation des données d’autres fonctions sont dédiées à l’habillage cartographique (thèmes ou chartes graphiques, légendes, échelles, flèches d’orientation, titre, crédits, annotations...), à la création de cartons ou à l’export des cartes.   
`mapsf` est le successeur de [`cartography`](http://riatelab.github.io/cartography/docs/) [@R-cartography], il offre les mêmes fonctionnalités principales tout en étant plus léger et plus ergonomique.   






## Documentation 

Pour utiliser ce package plusieurs sources peuvent être consultées :

* La documentation du package accessible [sur internet](http://riatelab.github.io/mapsf/) ou directement dans R (`?mapsf`),  
* Les [vignettes](https://riatelab.github.io/mapsf/articles/) associées au package présentent des exemples de scripts,  

* Le blog [R Géomatique](https://rgeomatic.hypotheses.org/) qui met à disposition ressources et exemples liés au package et plus généralement à l'écosystème spatiale de R.  







