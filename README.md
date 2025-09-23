# SAFEBASE

## Introduction

Dans le monde de l'entreprise, la gestion des bases de données et la sécurisation des données sont des enjeux cruciaux. Les données sont souvent l'un des actifs les plus précieux pour une organisation et leur perte peut engendrer des conséquenses désatreuses.
Pour cette raison, il est essentiel de mettre en place des système permettant de garantir la sauvegarde régulière des données et d'assurer leur restauration en cas de besoin.

## Objectif du Projet

Le projet vise à développer une solution complète de gestion de sauvegarde et de la restauration de base de données sous forme d'une API REST. Cette solution devra répondre aux besoins suivants :
* **Ajout de base de données :** Ajouter une connexion à la base de données.
* **Automatisation des sauvegardes régulières :** Planifier et effectuer des sauvegardes périodiques des bases de données, en utilisant le stantard cron et les utilitaires système de MySQL et postgress.
* **Gestion des versions :** Conserver l'historique des différentes version sauvegardées, avec des options pour choisir qu'elle version restaurer.
* **Surveillance et alertes :** Générer des alertes en cas de problème lors des processus de sauvegarde ou de restauration.
* **Intergace utilisateur :** Proposer une interface simple pour permettre aux utilisateurs de gérer facilement les processus de sauvegarde et de restauration.
* **Intégration de tests :** 2crire des tests fonctionnels permettant de s'assurer du bon fonctionnement de l'API, ainsi que la bonne exécution des sauvegardes et restaurations.
* **Conteneurisation :** Le projet devra être conteneurisé incluant l'API, une base MySQL, une base postgres, et le frontend.

