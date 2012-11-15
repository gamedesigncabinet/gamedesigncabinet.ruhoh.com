---
title: 'Agricola Express, quelques les modifications'
date: '2012-10-29'
description: 'Découverte du jeu Agricola Express... et discussion sur les améliorations qui peuvent y être apportées.'
categories: ['jeux et variantes']
tags: ['game design', 'print and play', 'boardgamegeek']

type: draft
---

Modification de l'iconographie
=======================

Les aide de jeu et les règles ne reflètent pas la règle 1.3 qui veut que les dés utilisé directement avec les dés d'action valent 1/2. En effet les actions sont notés avec un symbole rappelant une face de dé (un carré de couleur) tout comme les ressources à consommer... alors que justement on ne peut utiliser de face de dé pour les ressource (ou alors il en faut 2). 

Donc il faudrait remplacer le carré de couleur des ressources par un rond de couleur qui symboliserait "une ressource de ce type".


Modification de terminologie
=======================

Les 13 dés du jeu sont en fait classable en 2 catégorie distinctes que les règles peuvent traiter différemment :

*	les dés d'action qui permettent au joueur d'initier une action :
	*	les dés de ferme
	*	le dé de savoir faire
	*	le dé d'aménagement

*	les dés de ressources qui représente des ressources stockables ou utilisables en combinaison d'une action :
	*	les dés d'animaux
	*	les dés de productions
	*	les dés de matériaux (anciennement appelés dés de ressources)

On peut ainsi désigner sans ambiguité les 2 types de dés différents. Le changement d'appelation `ressources --> matériaux` permet juste d'utiliser le terme ressources qui est plus générique pour l'ensemble des dés de son groupe.


Malus de fin de partie
=======================

Au cours de la dernière récolte les joueur subissent un malus de :

*	-3 point si ils ont 0 pièces supplémentaires
*	-3 point si ils ont 0 champs labourés
*	-3 point si ils ont 0 paturages
*	-1 point si ils ont 0 céréale
*	-1 point si ils ont 0 légume
*	-1 point si ils ont 0 mouton
*	-1 point si ils ont 0 sanglier
*	-1 point si ils ont 0 boeuf


Attribution des paturages
=======================

Lorsque l'on acquière des animaux il faut préciser sr son plateau **dans quel paturage** on les place. Pour cela on _dessine_ l'animal à côté du paturage concerné (c'est provisoire il faudra adapter la fiche de score).

Il est impossible de changer le type d'un enclos une fois que celui-ci a été fixé. Par contre il est possible d'avoir plusieurs enclos de la même espèce de manière augmenter leur taux de reproduction.


Reproduction par enclos
=======================

Avec le système d'attribution des pâturage il devient possible d'avoir autant de naissance que d'enclos... et ce même si ils contiennent tous le même type d'animal. La règle est simple si on a 2 enclos de la même espèce il suffit d'avoir au moins 4 de ces animaux pour avoir 2 naissance (une dans chaque enclos).

Il n'est donc pas nécessaire de savoir combien il y a d'animaux dans chaque enclos mais juste quels types animaux il y a dans chaque.


Récoltes sur le long terme
=======================

L'utilisation de la face **champs** du dé ferme est modifiée.

*	si on l'utilise **seule** : on labourre un champ

*	si on l'utilise avec des **légumes**, on va consommer un légume par champ **disponible** que l'on souhaite planter : 
	1.	on labourre un champ
	2.	on consomme autant de légumes tout de suite qu'il y a de champ disponible (sans légume ou céréale planté dessus)
	3.	on **marque** chaque champ comme planté de légume en dessinant une carotte à côté. _C'est provisoire il faudra adapter la fiche de score_
	4.	**à toutes les prochaines récoltes** au cours de la phase de reproduction on récupère +1 légume par champ planté

*	si on l'utilise avec des **céréales**, on va consommer une céréale par champ **disponible** que l'on souhaite planter : 
	1.	on labourre un champ
	2.	on consomme autant de céréales tout de suite qu'il y a de champ disponible (sans légume ou céréale planté dessus)
	3.	on **marque** chaque champ planté en dessinant une céréale à côté. _C'est provisoire il faudra adapter la fiche de score_
	4.	**à toutes les prochaines récoltes** au cours de la phase de reproduction on récupère +3 céréales par champ planté

Ainsi les céréales gagnent en intéret par rapport qux légumes car elles sont facile à produire en quantité. Statistiquement une récolte de blé (3 blés) rapporte 1.5 points alors qu'une récolte de légumes (1 légume) rapporte 1 point. Les céréales peuvent donc dans certains cas être plus rentables que les légumes. On laisse le soin au joueur de voir ce qui sera le plus rentable pour lui !


Légumes et céréales crues
=======================

Les légumes et les céréales peuvent être convertis chacun en une nourriture sans matériel de cuisson.

Cela permet de varier les stratégies pour nourrir sa famille en début de partie et rentabilise les investissement sur les plantations.


Relancement
=======================

Coût du relancement
-----------------------

Si un joueur choisit de relancer les dés au lieu d'utiliser les dés laissés par son adversaire, il doit d'abord retirer au hasard un des dés disponible.


Nombre minimum de dés
-----------------------

Au début de la phase d'action d'un joueur, il doit y avoir au moins 6 dés en jeu (sans compter les dés de la zone "réserve x2"). Si ce n'est pas le cas, le joueur dois piocher les dés manquants au hasard dans la réserve puis les lancer.


Relancement à la fin de chaque tour
-----------------------

À la fin de chaque tour de jeu, l'ensemble des dés est relancé (pour compenser le fait qu'on ne relance jamais tous les dés).


Accumulation des ressources inutilisées
-----------------------

À la fin d'un tour de jeu les dés restant qui ne sont pas des dés d'action (ressource, nourriture, animaux) sont placé sur un mini plateau "réserve x2" et ne sont pas relancés.

Les joueurs pourront les utiliser comme des dés normaux (il retournent alors avec la défausse des dés normaux et perdent leur stats "réserve x2") mais leurs valeur est doublée :
*	2 unité au lieu de 1 si il sont stockés (sauf la double nourriture qui vaudra alors 4)
*	1 unité au lieu de 1/2 si ils sont utilisés directement (sauf la double nourriture qui vaudra alors 2)

Lors du relancement des dés en début de tour, on ne relance pas les dés qui sont en zone "réserve x2".


Changement de premier joueur
=======================

Avec l'incapacité de revenir à 13 dés en jeu n'importe quand dans la partie, il devient primordial de pouvoir se battre pour être dans les premiers à jouer... il faut donc ajouter une règle permettant au joueur de "prendre" la place de premier joueur en cours de jeu.

Lorsqu'un joueur effectue une des actions suivante, il devient le premier joueur dès le tour de jeu suivant :

*	labourage sans semaille
*	construction de barrières sans ajouter d'animaux

Comme ces actions sont des "versions limitées" de "labourage et semaille" et "construction de barrière et ajout d'animaux" l'acquisition du status de premier joueur vient le compenser.


(À TESTER) Jouer à plus de 4 joueurs
=======================

Selon le nombre de joueurs on ajuste le nombre minimum de dés en jeu :

*	1 joueur	:	5 dés minimum
*	2 joueurs	:	6 dés minimum
*	3 joueurs	:	6 dés minimum
*	4 joueurs	:	7 dés minimum
*	5 joueurs	:	7 dés minimum


(À TESTER) Atelier de vannerie plus rentable
=======================

L'atelier de vannerie rapporte 1 point par roseau au lieu de 2 points par 2 roseaux.

Comme le roseau est actuellement la ressource la moins rentable à posséder du jeu (on ne l'utilise que pour agrandir sa maison) il apparaît comme intéressant d'augmenter sa rentabilité en terme de points de victoire.


(À TESTER) Atelier d'artisanat en roseau ou en bois
=======================

Les quatre ateliers d'artisanat sont possible à construire soit avec 1 bois (comme dans la règle de base) soit avec 1 roseau.

Comme le roseau est actuellement la ressource la moins rentable à posséder du jeu (on ne l'utilise que pour agrandir sa maison) il apparaît comme intéressant de lui donner une autre utilisation. de plus dans la construction des aménagement on retrouve le couple "pierre - argile" pour es aménagement de cuisson alors que les aménagement ateliers d'artisanat ne peuvent eux être construit qu'avec du bois. C'est en partie ce qui crée une grande inégalité d'utilisation entre la pierre et le roseau (qui pourtant ont la même fréquence d'apparition sur les dés).

(À TESTER) Ateliers d'artisanat au choix des joueur
=======================

Pour permettre au joueurs de choisir leur orientation plutôt que d'être dépendant purement du lancer du dé "Aménagements" on remplace par une face générique "atelier d'artisanat" les faces suivantes :

*	menuiserie
*	atelier de potterie
*	atelier de tailleur de pierre
*	atelier de vannerie

Lorsque la face "atelier d'artisanat" est disponible un joueur peut l'utiliser pour construire n'importe lequel des ateliers. Mais pour éviter que cela soit trop facile on augmente le coût de chaque atelier d'une ressource qui lui est spécifique.


(À TESTER) Ateliers d'artisanat source de nourriture
=======================

Les ateliers d'artisanat permettent de générer de la nourriture :

*	menuiserie :					+1 nourriture / 1 bois

*	atelier de potterie :			+1 nourriture / 1 argile

*	atelier de tailleur de pierre :	+2 nourriture / 1 pierre

*	atelier de vannerie :			+2 nourriture / 1 roseau

Peut-être faudrait-il alors augmenter leur coût pour éviter de rendre le jeu trop facile ? Par exemple une ressource spécifique de l'atelier de plus..?