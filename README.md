# specification

Specification for the la-titube awesome project

A quoi sert l'application La titube :
 _ connaître ses stocks en terme d'alcool mais aussi d'ingrédients.
 _ avoir accés à une multitude de recette de cocktail
 _ faire évoluer ses stocks en fonction de la soirée (faire un cocktail diminue les stocks)

Comment on accède à l'application :
 _ connexion & inscription classico del madrido

## User story

Un utilisateur inscrit peut accéder à sa cave et inviter des visiteurs dans sa cave.
Le visiteur peut simplement voir la carte des cocktails disponibles.

Un utilisateur peut modifier sa cave :
 _ gros CRUD sa mère

Un utilisateur peut ajouter des recettes aux recettes de base :
 _ gros CRUD sa mère aussi
 _ option de fork à un cocktail
 _ pour chaque recette des commentaires
 _ OPTIONNEL : notes ?

Un utilisateur peut faire un cocktail (conséquences: cave en pls)

Un utilisateur peut voir les cocktails disponibles

Un utilisateur peut voir les cocktails presque disponibles (il manque des ingrédients : à définir)

Un utilisateur peut être averti lorsque cave connaît la prohibition (seuil à définir)

Un utilisateur peut exporter la liste des cocktails disponibles dans sa cave. (avec option de presque disponible)

## DICTIONNAIRE

__cave__ : une cave est le stock en ressources que l'utilisateur possède (alcool, citron, orange, olives ...)

__recette__ : une recette est composée des informations suivantes ==>> alcool primaire, comment s'est servi (avec glaçons, sans etc ...), garniture standard, le verre, les ingrédients (Volume), une petite explication de comment faire (et une petite photo).

__visiteur__ : un visiteur est une personne qui a accés à la cave d'un autre utilisateur ce qui lui permet de voir ce qui est disponible.

__utilisateur__ : un utilisateur est une personne qui possède une cave, et qui peut réaliser des cocktails avec cette dernière.

## TechnoProps

Backend : stack classique 2020
 --> NODE léger, moderne et on connait tous
 --> MONGODB : moins de jointure, et puis esther quoi !
 --> JEST : pour les tests, facile de mocker, c'est joli, du coup c'est cool

Frontend:
 --> REACT : par défaut
 --> REDUX : par obligation
 --> 