# Projet de Modélisations, Optimisation, Graphes et Programmation Linéraire (MOGPL) - Sorbonne Université
# Optimisation équitable 

Les décisions prises au sein des organisations ont souvent un impact qui s’apprécie
selon plusieurs individus et donc plusieurs points de vue, qu’il convient de considérer de
manière équitable.
Dans les problèmes de décision ou d’optimisation multiagents, l’équité est souvent au
cœur des préoccupations, qu’il s’agisse de répartir des ressources, d’allouer des tâches, de
partager des bénéfices ou plus généralement de prendre en compte les préférences individuelles.

L’optimisation équitable consiste donc, à trouver des solutions efficaces en apportant un
soin particulier à préserver l’équilibre entre la satisfaction des différents points de vue
considérés.

De manière générale, nous nous intéressons dans ce projet, à un problème d’optimisation multi-dimensionnel sur un ensemble X (continu ou discret) défini par un système de
contraintes dont chaque solution réalisable x est évaluée par n fonctions représentant n
points de vues potentiellement différents sur le coût de la solution x. Ainsi, toute solution
x sera évaluée par un vecteur z(x) représentant le coût ou performance de x selon le point
de vue i.

A noter que ces points de vus représentent des évaluations ou critères d’évaluation en
fonction des problèmes considérés.
C’est ainsi que l’optimisation équitable vise à trouver une solution efficace équitable, que
l’on ne peut améliorer sur une composante sans la dégrader sur une autre (d’après la
définition de l’équité), et qui conduit à un vecteur z(x) équilibré.


Notre travail portera tout d’abord sur la linéarisation de la fonction objectif du problème d’optimisation équitable puis, traitera de ses différentes applications que voici :

— Le partage équitable de biens indivisibles

— La sélection multicritère de projets

— La recherche d’un chemin robuste dans un graphe
