# specification

Specification for the la-titube awesome project

A quoi sert l'application La titube :

* connaître ses stocks en terme d'alcool mais aussi d'ingrédients.
* avoir accés à une multitude de recette de cocktail
* faire évoluer ses stocks en fonction de la soirée (faire un cocktail diminue les stocks)

Comment on accède à l'application :

* connexion & inscription classico del madrido

## User story

Un utilisateur inscrit peut accéder à sa cave et inviter des visiteurs dans sa cave.
Le visiteur peut simplement voir la carte des cocktails disponibles.

Un utilisateur peut modifier sa cave :

* gros CRUD sa mère

Un utilisateur peut ajouter des recettes aux recettes de base :

* gros CRUD sa mère aussi
* option de fork à un cocktail
* pour chaque recette des commentaires
* OPTIONNEL : notes ?

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

* --> [NODE](https://nodejs.org/en/docs/) : léger, moderne et on connait tous
* --> [MONGODB](https://docs.mongodb.com/) : moins de jointure, et puis esther quoi !
* --> [JEST](https://jestjs.io/docs/en/getting-started) : pour les tests, facile de mocker, c'est joli, du coup c'est cool

Frontend:

* --> [REACT](https://reactjs.org/docs/) : par défaut
* --> [REDUX](https://redux.js.org/introduction/getting-started) : par obligation

Gestion:

* --> [Gitflow](https://danielkummer.github.io/git-flow-cheatsheet/index.fr_FR.html)
* --> [Quire](https://quire.io/)

Déploiement

* --> [Docker](https://docs.docker.com/)
* --> [Docker-Compose](https://docs.docker.com/compose/)
