---
title: Guide d'utilisation du blog
date: '2012-10-31'
description: Comment utiliser le blog du Cabinet de GameDesign Clandestin au jour le jour.
categories: tutoriels
tags: ['documentation', 'ruhoh']

type: draft
---

Maintenant que tu as tout ce qu'il faut pour utiliser le blog, je vais te donner les instruction pour l'utiliser.

Commençons par mettre le contexte :

*	tu as fait tout le tutoriel précédent
*	tu va mettre le blog sur ta machine où tu veux mais moi je noterais ce chemin comme ça `chemin/ou/tu/a/mis/leblog`
*	tu accèpte solennellement d'utiliser le terminal !

Enfin un petit détail sur une commande que je vais utiliser souvent la commande `cd` dans le terminal. Elle sert simplement à changer de répertoire. Par défaut le terminal souvre dans ton répertoire utilisateur grâce à `cd` on peut se déplacer ailleurs. À chaque fois que je mettrai cette commande, inutile de la faire si tu es déjà là où il faut (moi j'ai supposer à chaque fois que tu avais refermé le terminal donc que tu ne restais pas dans le bon répertoire, si tu es intelligent tu laisse le terminal ouvert et tu n'as à faire le `cd` qu'une seule fois).


Récupérer le blog en local (à faire une seule fois)
=====================

C'est pour cette étape que j'avais besoin d'avoir ton compte GitHub sinon

blablabla


Rédiger un post
=====================

1.	Avant de commencer à rédiger quoi que ce soit il faut récupérer la dernière version (au cas où j'aurais fait des modifs sur le site) pour ça hop un coup de terminal :

		$ cd chemin/ou/tu/a/mis/leblog
		$ git pull

2.	Ensuite tu crée un fichier `titre de mon post.md` (si tu n'est pas sûr du titre final c'est pas grave là c'est à titre indicatif... ben oui faut bien lui donner un nom)
3.	Tu écrit l'en-tête du fichier au début de celui-ci :

		---
		title: 'Un titre complet'
		date: '2012-10-31'
		description: 'Une description longue du contenu de l\'article'
		categories: 'tutoriels'
		tags: ['documentation', 'ruhoh']
		---

4.	Tu écrit ton post... là je te fais confiance... et tu le sauve !
5.	On va envoyer tout ça sur le blog grâce à ton ami le terminal :

		$ cd cd chemin/ou/tu/a/mis/leblog
		$ git commit -a -m "voilà les changements que j'ai fait"
		$ git push

	Pour info ça sert respectivement à :

	1.	aller dans le répertoire du blog (si tu n'y es pas déjà)
	2.	valider l'ensemble des changements (`-a` c'est pour dire `all`) en leur donner une description (`-m` c'est pour dire `message` si tu ne le met pas il te le demandera en ouvrant un éditeur de texte imbitable de linuxien borné !). C'est obligatoire et ça permet de s'y retrouver dans l'historique.
	3.	envoyer tout ça sur le serveur GitHub qui va instantannément publier ton post sur le blog (et au passage les autre rédacteurs recevront tes modifications à leur prochain `pull`)

Le workflow est exactement le même tout le temps ! Si je le résume c'est : **PULL EDIT COMMIT PUSH**. Et il faut faire des commit super souvent ! Comme ça notre historique est hyper détaillé (c'est important). La règle de base c'est : si tu as édité un truc tu dois le commiter avant d'éteindre ton ordi !


Rédiger un brouillon
=====================

blablabla


Modifier un texte
=====================

blablabla


Partager des ressource sans rien publier
=====================

blablabla


Annexe 1 : les modèles
=====================

Voilà le modèle d'en-tête pour un **brouillon d'article** :

	---
	title: 'Un titre complet'
	date: '2012-10-31'
	description: 'Une description longue du contenu de l\'article'
	categories: 'tutoriels'
	tags: ['documentation', 'ruhoh']

	type: draft
	---

	blablabla

Et pour un **article à publier** c'est la même chose mais en supprimant la ligne `type: draft` :


	---
	title: 'Un titre complet'
	date: '2012-10-31'
	description: 'Une description longue du contenu de l\'article'
	categories: 'tutoriels'
	tags: ['documentation', 'ruhoh']
	---

	blablabla

Donc convertir un brouillon en article, ça revient simplement à supprimer la ligne `type: draft`.


Annexe 2 : les bonus
=====================

### <Gestion de liste de TODO LIST partagée ###

GitHub intègre un petit outil de gestion de "tickets" hyper bien fait et intégré à notre blog/dépôt : <https://github.com/dashboard/issues>

Son principe est simple, quand on a un truc à faire/corriger il suffit de :

*	noter ce qu'il y a à faire [sur la pages des issues](https://github.com/dashboard/issues) 
*	GitHub va lui attribuer un **numéro** par exemple `#18`
*	on **fait la tâche** avec nos petits doigts (genre en rédigeant un post adéquat ou en mettant une image dans la zone de partage)
*	au moment de **commiter** le changement on met dans le message de commit `fixed #18` et hop c'est fait ! La tâche sera affichée comme réalisée !
*	si jamais on veut juste signaler qu'on a bossé sur une tâche sans la finir le message de commit doit juste contenir son numéro `#18`

**AJOUTER UN EXEMPLE**

Pour plus d'info tu peux regarder ça : <https://github.com/blog/831-issues-2-0-the-next-generation>