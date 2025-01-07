##Projet Analyse des Offres d'Emploi en France avec Adzuna API
Ce projet vise à collecter et analyser des données relatives aux offres d'emploi en France en utilisant l'API publique d'Adzuna. Le processus complet suit un pipeline ETL (Extraction, Transformation, Chargement) pour extraire les données depuis l'API, les transformer pour les rendre adaptées à l'analyse, puis les charger dans Snowflake. Ensuite, nous utilisons dbt (Data Build Tool) pour effectuer des requêtes et calculer les métriques désirées.

##Objectif du Projet
L'objectif principal de ce projet est de traiter les données liées aux offres d'emploi en France pour en tirer des insights utiles. Ces données sont extraites de l'API Adzuna, puis transformées à l'aide de dbt pour répondre à des questions comme :

Les tendances de l'emploi dans différentes régions
Les catégories de métiers les plus populaires
L'évolution des offres d'emploi dans le temps
