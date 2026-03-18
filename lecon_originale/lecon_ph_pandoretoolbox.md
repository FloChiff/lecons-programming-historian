---
title: EXTRAIRE, NETTOYER ET ANALYSER UN CORPUS AVEC PANDORE TOOLBOX 
collection: lessons  
layout: lesson  
authors:
- FLORIANE CHIFFOLEAU
- ALINA MIASNIKOVA
---

# Introduction

## Objectifs de la leçon
- Apprendre à utiliser Pandore Toolbox
- Découvrir diverses techniques d'analyses et de récupération d'informations

## Prérequis
- Simple connexion Internet

# L'outil : Pandore Toolbox
## Histoire de l'outil
- Genèse et création de l'outil
- Diverses formations faites dessus

## Composition de l'outil
- Présentation des tâches et des outils

# Extraction du corpus
## Récupération du corpus
### Choisir sa bibliothèque numérique
- Plusieurs choix à disposition : Projet Gutenberg, Wikisource, Google Books, Gallica
- Choix de Gallica pour la démonstration

### Collecte des images avec Gallica
- Accéder à l'outil
- Présentation du corpus choisi pour l'exemple
- Extraction du corpus
- Observer le dossier de sortie

## Transcription du corpus 
### Choisir son outil
- Deux choix à disposition : Tesseract et Kraken
- Text est imprimé donc choix de Tesseract

### Reconnaissance de texte avec Tesseract
- Accéder à l'outil
- Choisir la langue
- Importer les images
- Observer le fichier de sortie

# Nettoyage du corpus
## Prétraitement (1ère partie)
### Nettoyage de l'OCR bruité
- Caractéristiques d'une sortie d'OCR
- Accéder à l'outil de nettoyage
- Choix des options nécessaires
- Observer la sortie

### Correction post-OCR
- Accéder à l'outil
- Choisir la langue
- Choisir la sortie outil : ici avec les modifications apparentes
- Importer le texte
- Observer le fichier de sortie

## Comparaison des sorties
- Accéder à l'outil
- Importer sortie Tesseract et sortie correction
- Ouvrir HTML dans navigateur et observer différences
- Correction manuelle si nécessaire (éditeur de texte nécessaire)

## Prétraitement (2ème partie)
- Accéder de nouveau à l'outil
- Choisir les options nécessaires
- Observer la sortie

# Analyse du corpus
## Deux versions d'un même texte
- Analyse avec le texte tel quel (V1)
- Analyse avec le texte sans majuscule ponctuation et mots-vide (V2)

- Accéder de nouveau à l'outil
- Choisir les options nécessaires
- Observer la sortie

## Récupération d'informations et analyses
### Etiquetage morphosyntaxique et analyses des dépendances
- Accéder à l'outil de POS
- Importer le texte (V1)
- Observer la sortie

- Accéder à l'outil d'analyse des dépendances
- Choisir la bonne option
- Importer le texte (V1)
- Observer la sortie

### Reconnaissance d'entités nommées
- Accéder à l'outil
- Choisir la bonne option (Texte)
- Importer le texte (V1)
- Observer la sortie

### Topic Modelling
- Accéder à l'outil
- Importer le texte (V1)
- Observer la sortie

### Extraction des mots-clés
- Accéder à l'outil
- Importer le texte (V1)
- Observer la sortie

### Analysie linguistique et statistique
- Accéder à l'outil d'analyse linguistique
- Choisir les options voulues
- Importer le texte (V2)
- Observer la sortie

- Accéder à l'outil d'analyse statistique
- Choisir les options voulues
- Importer le texte (V1)
- Observer la sortie

## Visualisation
### Afficher les relations entre personnages
- Accéder à l'outil
- Choisir les options voulues
- Importer le texte (V1)
- Observer le graphe de sortie

### Cartographier les entités de lieux
- Accéder à l'outil
- Choisir les options voulues
- Importer le texte (V1)
- Observer la carte

# Conclusion
- Analyse assez complète et beaucoup d'informations récupérées
- Pandore Toolbox et ses autres outils non présentés