#Web Sequence Diagram DSL

Ce projet permet de créer des [diagrammes de séquences](http://fr.wikipedia.org/wiki/Diagramme_de_s%C3%A9quence) à partir d'une formulation textuelle.


##Introduction

Bien que ce type de service existe déjà (à cette [adresse](https://www.websequencediagrams.com/)), ce projet est parfait pour se familiariser avec plusieurs technologies ou concepts, tels que :
- les DSL ou Domain Specific Languages 
- Yeoman et autres dépendances (npm, grunt, bower, less, etc.)
- AngularJS
- la création d'applications noBackend
- ...

... et pourquoi pas la création d'une application Google Chrome App, d'une application PhoneGap, ... nous verrons bien où le vent nous porte.

Vous l'aurez compris, ce projet est surtout orienté comme un atelier/tutoriel qui, je l'espère, sera utile pour maîtriser ces technologies.

##Pré-requis

Afin de générer/tester l'application, il est nécessaire d'installer [NodeJS](http://nodejs.org/).

###Installation des packages NodeJS

L'installation des packages Node se fait grâce à l'utilitaire `npm`. 
Vous pouvez vous reporter à la [documentation](https://npmjs.org/doc/cli/npm.html) pour obtenir plus d'informations sur les différents arguments de la ligne de commande ou tapez en ligne de commande `npm help`.

Donc, afin d'installer les packages utilisés par le projet, exécutez en ligne de commande :
```
npm install -g yo generator-angular less
```

###Clonage du projet
```
git clone https://github.com/aptea/simuferro.git
```

###Dépendances du projet
Placez-vous dans le répertoire du projet et exécutez la ligne de commande :
```
npm install & bower install
```
Cela va télécharger les dépendances et alimenter les dossiers `node_modules` et `app\components`.

###Lancement de l'application Web
Eexécutez la commande `grunt server` afin de lancer l'application.
