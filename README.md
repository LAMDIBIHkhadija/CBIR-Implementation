# Projet de Recherche d'Images Basée sur le Contenu (CBIR)

## Vue d'ensemble

Ce projet démontre un système de Recherche d'Images Basée sur le Contenu (CBIR), qui permet de rechercher et récupérer des images à partir d'une base de données en se basant sur le contenu visuel des images. Le système utilise diverses techniques d'extraction de caractéristiques pour comparer l'image requête avec les images de la base de données.

## Fonctionnalités

- **Chargement d'Images** : Lit toutes les images d'un répertoire spécifié et affiche six images aléatoires.
- **Recherche par Image Complète** : Calcule la distance euclidienne entre l'image requête et toutes les images de la base.
- **Recherche par Couleur** : Utilise les moments de couleur et les caractéristiques d'histogramme HSV pour trouver des images similaires.
- **Recherche par Texture** : Utilise les propriétés de la GLCM (Matrice de Co-occurrence de Niveaux de Gris) pour comparer les textures.
- **Recherche par Forme** : Utilise les Moments de Hu pour la comparaison des formes.
- **Robustesse aux Transformations Géométriques** : Teste la robustesse du système face à des transformations géométriques telles que la rotation.

