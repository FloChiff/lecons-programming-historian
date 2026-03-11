{% include toc.html %}

## Introduction

Dans cette leçon, vous apprendrez à organiser un ensemble de textes pour de la recherche ; c'est-à-dire que vous allez apprendre les étapes basiques de la création d'un 'corpus'. Vous apprendrez également les métriques principales de l'analyse quantitative de texte. Pour cela, vous utiliserez [Voyant Tools](http://voyant-tools.org/),[^1] une plateforme Internet qui ne requiert aucune installation et qui fonctionne avec chaque navigateur Internet doté d'une connexion internet.

Cette leçon est conçue comme une introduction à l'analyse de corpus, adaptée pour les débutants, et elle fait partie d'un écosystème grandissant d'outils et de méthodes pour les humanités numériques. Pour un outil plus avancé, vous pouvez consulter la leçon Programming Historian sur [l'analyse de corpus avec AntConc](fr/lecons/analyse-corpus-antconc). Vous pouvez également être intéressé par d'autres leçons *Programming Historian* sur [l'exploration de texte](), le [traitement automatique des langues]() ou [*topic modeling*](/en/lessons/topic-modeling-and-mallet).

### Prérequis et lectures approfondies

Aucune expérience préalable en analyse de texte n'est requise. Cependant, pour ceux qui veulent aller plus loin, nous recommandons les ressources suivantes :

- [Documentation de Voyant Tools](https://perma.cc/6CRX-9B9D)
- [Hermeneuti.ca](https://perma.cc/93VW-WC8V), le site d'accompagnement du livre *Hermeneutica: Computer-Assisted Interpretation in the Humanities* de Sinclair et Rockwell[^2]

### Analyse de corpus

L'analyse de corpus est un type d'[analyse de contenu](https://perma.cc/Y8B2-RL89) qui permet la comparaison, à grande échelle, d'un ensemble de textes ou d'un corpus.

Depuis l'avènement de l'informatique, les linguistes informatiques et les spécialistes dans la [recherche d'informations](https://perma.cc/3F3M-3JV3) ont créé et utilisé des logiciels pour repérer des motifs qui ne se distinguent pas à l'oeil nu, ou pour corroborer les hypothèses pressenties en lisant certains textes mais dont la réponse nécessitait un travail laborieux, coûteux et répétitif. Par exemple, pour obtenir des motifs dans l'accroissement et le déclin de l'usage de certains termes sur une période donnée, il était nécessaire d'engager des gens pour relire manuellement un texte et noter toutes les fois où le terme choisi apparaissait. Très tôt, en observant les capacités de calcul des ordinateurs, ces spécialistes ont rapidement écrit des programmes informatiques pour faciliter les tâches de création de [listes de fréquences](https://perma.cc/F472-XM7K) ou de [tables de concordances](https://perma.cc/AYP4-PVKR). Le programme que vous apprendrez à utiliser avec cette leçon s'inscrit dans ce contexte historique.

### Ce que vous apprendrez dans cette leçon

Voyant Tools est un outil du web qui ne requiert l'installation d'aucun logiciel spécialisé, puisqu'il fonctionne sur tout ordinateur muni d'une connexion Internet.

Comme cela a été mentionné dans l'[Analyse de corpus avec AntConc](fr/lecons/analyse-corpus-antconc), cet outil est un bon point d'entrée vers des méthodes plus complexes. 

À la fin de cette leçon, vous serez capable :

- d'assembler un corpus de texte brut
- de charger votre corpus dans Voyant Tools
- de comprendre et d'appliquer diverses techniques de segmentation selon le corpus
- d'identifier les caractéristiques de base de votre ensemble de texte :
  - la longueur des documents chargés
  - la densité lexicale (appelé "densité du vocabulaire" sur l'interface)
  - du nombre moyen de mots par phrase
- de lire et comprendre les différentes statistiques à propos des mots : fréquence absolue, fréquence normalisée, asymétrie statistique and mots distincts
- de chercher des mots-clés en prenant en compte le contexte et d'exporter des données et des visualisations dans des formats variés (CSV, PNG, HTML)

## Créer un corpus de texte brut

### 1. Choisir vos textes
### 2. Le copier dans un éditeur de texte
### 3. Sauvegarder le fichier
## Charger le corpus
## Explorer le corpus
## Résumé du document : les caractéristiques basiques de votre ensemble de textes
### Nombre de textes, de mots et de mots uniques
### Longueur de document
### Densité du vocabulaire
### Mots par phrase
## Cirrus et résumé : filtres de fréquences et de mots-vide
### Fréquences non filtrées
### Mots-vide
### Fréquences avec le filtre de mots-vide
## Termes
### Fréquences normalisées
### Asymétrie statistiques
### Mots différenciés
## Mots dans leur contexte
## Exporter les tables
## Réponses des activités
## Notes de bas de page