# Devoir maison n°2 : Analyse Discriminante PLS exploratoire (ADPLS)

## Description

Ce projet a été réalisé dans le cadre du cours Analyse et Modélisation Multivariées du Master 2 SSD à l'Université de Montpellier.  
L'objectif de ce TP est de mettre en œuvre l'Analyse Discriminante PLS exploratoire (ADPLS), une méthode permettant de représenter et d'interpréter la structure discriminante d'un ensemble d'individus à partir de variables quantitatives et d'une variable qualitative de classes.

L'approche consiste à extraire des composantes linéaires des variables explicatives \( X \) maximisant simultanément la variance expliquée dans \( X \), et la séparation entre les groupes définis par la variable qualitative \( Y \).

## Objectifs

L'objectif du TP est double :
1. **Implémenter la méthode ADPLS** à partir des formules théoriques du cours, en construisant un programme R complet :
   - calcul des composantes discriminantes \( f_h = X M u_h \),
   - calcul des indicateurs \( S(f_h) \) et \( R^2(f_h, Y) \),
   - calcul des centres de gravité des classes et des coordonnées des variables.
2. **Appliquer la méthode** aux données écologiques du bassin du Congo pour interpréter la différenciation entre types forestiers.

## Données

Les données utilisées proviennent du jeu de données **Datagenus**, issu du projet **CoForTips**, qui décrit la composition en espèces d’arbres de différentes parcelles forestières du bassin du fleuve Congo.

## Packages R

### Packages utilisés
- `stats` : fonctions de base pour les calculs matriciels.  
- `graphics` : visualisations des plans discriminants.  
- `base` : manipulation des matrices et vecteurs.  

## Structure du projet

```
.
├── Consignes.pdf         # consignes données pour ce devoir
├── Datagenus.csv         # données pour l'analyse ADPLS
├── README.md 
├── TP2_AL.pdf           
└── TP2_AL.Rmd                            
```

## Auteurs

- AIGOIN Emilie
- STETSUN Kateryna
- THOMAS Anne-Laure
Master 2 SSD - Université de Montpellier  
Année universitaire 2024-2025

## Références

- Cours d'Analyse Multivariée - X. Bry
- Projet CoForTips - Données du bassin du fleuve Congo
- Documentation R : [CRAN](https://cran.r-project.org/)