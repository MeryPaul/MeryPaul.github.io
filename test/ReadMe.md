# Méthode numérique pour la résolution du système Prey-taxis
Dernière mise a jour 27/10/2025 

## Introduction 
Ce code a pour objectif de centraliser les codes produit dans le cadre du stage ainsi que du début de la thèse. Il contient une méthode de volume finis implicite sur maillage régulier en 1D avec des conditions de Dirichlet ainsi que une méthode de différence finie explicite avec condition aux bords de Dirichlet ou de Neumann. Il est aussi inclu une méthode de résolution du modèle de Lotka-Volterra a 3 espèce. 

## Utilisation
Ce code est séparé en 4 fichier:
- main.py contient les coefficient du système et sert a appeler les méthode de résolution. 
- solve.py contient les différente méthode de résolution. 
- fonction.py contient différente fonction utilisé dans le code ainsi que les fonctions pour les méthodes de Newton 
- CI.py contient les différentes conditions initiales. 
