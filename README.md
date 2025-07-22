# Projet Rest

L'objectif du projet sera de créer une API Rest avec Spring Boot permettant de calculer et partager un budget entre ami⋅es

## Fonctionnalités

* Créer un groupe de dépenses
* Entrer des dépenses dans un groupe (Ex: `Billet de Train 25€ - Marc`, `Sac de pomme pour le pique nique 2.99€ - Hamza`)
* Consulter la liste et le total des dépenses, filtrer par personnes et montant (supérieur/inférieur à...)
* Pouvoir consulter le compte indiquant le total des dépenses et qui doit combien à qui, et pouvoir indiquer qu'on a payé son dû
* S'authentifier pour pouvoir voir les différents groupes dont on fait parti

## Réalisation

* Commencer par créer un diagramme d'entité
   <img width="715" height="729" alt="image" src="https://github.com/user-attachments/assets/5f38872d-b592-415e-931d-8b362bad98a4" />
* Initialiser un projet Spring Boot avec les dépendances nécessaires
* Faire une architecture Controller -> Business -> Repository avec des DTO dans les contrôleurs, toute la logique et l'accès aux repositories dans le Business
* Faire des tests fonctionnels pour quelques endpoints





