# Description du dossier

Ce dossier est une analyse de l'oeuvre de fiction *Voyage au centre de la Terre* de Jules Verne. J'ai récupéré les données puis encodé l'œuvre de façon à ce que l'on puisse retrouver la structure des chapitres en introduisant une variable par chapitre. Par la suite, j'ai réalisé une analyse sur Iramuteq avec plusieurs types de visualisations, puis j'ai mis les résultats sous forme d'infographie.

## Version texte

Afin de pouvoir obtenir la version .txt de l'oeuvre, je suis allée sur [Wikisource](https://fr.wikisource.org/wiki/Voyage_au_centre_de_la_Terre/Texte_entier).

Par la suite, afin de pouvoir l'utiliser dans Iramuteq, j'ai __formaté__ le texte de façon à ce que celui-ci soit compatible, selon la syntaxe suivante :

~~~~
**** *chapitreX
texte texte texte texte

**** *chapitreY
texte texte texte

A noter que :
**** : introduit chaque texte
*nomvariable : crée une variable
~~~~

## Version epub

blabla

## Visualisation de données

### Statistiques

J'ai réalisé ce type d'analyse pour avoir plus de __lisibilité__. La *lemmatisation* permet de réduire les verbes à leurs formes infinitives. J'ai alors obtenu un shcéma aussi aussi un tableau qui permet de voir la fréquence des mots dans l'oeuvre ainsi que leurs types (verbe, adjectif...).

### Nuages de mots

Cette analyse n'apporte pas vraiment d'information pertinente par elle-même, mais je pense qu'il peut être intéressant de la __coupler avec un autre type d'analyse__ afin d'apporter un aspect visuel.

### Analyses de similitudes

Ici, j'ai réglé les paramètres de façon à ce que l'analyse se fasse sur la *cooccurence* (combien de fois des éléments apparaissent en même temps, présence simultanée de deux ou plusieurs mots dans un même énoncé - [Source](https://fr.wikipedia.org/wiki/Cooccurrence)). 

J'ai choisi la présentation __fruchterman reingold__

## Fichier Question

lien

## Fichier Gephi

fnjnze
