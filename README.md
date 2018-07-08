# birdoffice-test

Ce projet a été réalisé en vuejs


Avant toute chose, veuillez installer les dépendances en faisant un "npm install" dans votre terminal 
si vous n'avez pas node d'installé sur votre machine, téléchargez-le à cet adresse "https://nodejs.org/en/" puis refaites un "npm install"

une fois que cela sera fait, vous allez lancer votre serveur en tapant dans votre terminal "npm run dev" ou "npm start"

Et vous voilà avec votre serveur fonctionnel. Allez à cet adresse pour voir le site "localhost:8080"


Pour toute modification, veuillez acceder au fichier Home.vue au chemin suivant "src/components/Home.vue"

en ce qui concerne l'architechture, j'ai utilisé Boootstrap 4 et SASS

j'ai imbriqué directment les media queries dans le scss principal de la manière suivante:

```html
.class {
	margin:0;
	@media screen and (max-width: 978px){
		margin:30px
	}
}
```

Comme ça il vous sera plus simple de trouver ce que vous voulez modifier, sans forcement passer par un autre fichier et chercher la classe ou l'id en question.

Si un jour vous voulez mettre le projet en ligne vous devrez faire la commande suivant "npm run build" puis aller dans le dossier dist, et prendre le fichier index.html, le dossier static et les mettre sur votre serveur.
