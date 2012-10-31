---
title: Guide d'utilisation du blog
date: '2012-10-31'
description: Comment utiliser le blog du Cabinet de GameDesign Clandestin au jour le jour.
categories: tutoriels
tags: ['documentation', 'ruhoh']

type: draft
---

Guide d'utilisation du blog
===================

Maintenant que tu as tout ce qu'il faut pour utiliser le blog, je vais te donner les instruction pour l'utiliser.

Récupérer le blog en local (à faire une seule fois)
---------------------

C'est pour cette étape que j'avais besoin d'avoir ton compte GitHub sinon

blablabla


Rédiger un post
---------------------

blablabla


Rédiger un brouillon
---------------------

blablabla


Modifier un texte
--------------------

blablabla


Partager des ressource sans rien publier
--------------------

blablabla


Annexe 1 : les modèles
-------------------

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

Et pour un artcle tout court... donc qui va être publié sur le blog... c'est la même chose mais en supprimant la ligne `type: draft` :


	---
	title: 'Un titre complet'
	date: '2012-10-31'
	description: 'Une description longue du contenu de l\'article'
	categories: 'tutoriels'
	tags: ['documentation', 'ruhoh']
	---

	blablabla


Annexe 2 : les bonus
-------------------

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