# Spotify-Data-Analysis-Using-SQL
![image alt](https://github.com/iammigjoe/Spotify-Data-Analysis-Using-SQL/blob/main/spotify_logo.jpg)
Project Overview

In this project, I worked with a large Spotify dataset containing information about artists, tracks, albums, streaming metrics, and audio features. I downloaded the dataset, created a PostgreSQL database, and imported the data into a structured SQL table.

During the import process, I initially encountered an issue related to quotation marks (double quotes vs. single quotes) when loading the CSV file. After resolving the formatting problem, I successfully imported the dataset and performed a complete analytical study using advanced SQL queries.

This project helped me explore SQL concepts ranging from basic analysis to complex window functions and CTEs (Common Table Expressions).

⸻

Technologies Used
• PostgreSQL (main database engine)
• SQL (DDL, DML, window functions, CTEs, aggregates)
• pgAdmin / psql CLI (for managing the database)
• CSV dataset (for importing Spotify data)

⸻

What I Did in This Project
• Designed and created a Spotify table with appropriate data types
• Cleaned the dataset (checking missing values, removing invalid rows such as duration = 0, checking distinct categories)
• Performed Exploratory Data Analysis (EDA): counts, distinct values, descriptive exploration, validation of data quality
• Wrote Easy, Medium, and Advanced SQL queries, including:
• Aggregations (SUM, COUNT, AVG)
• Filtering and grouping (WHERE + GROUP BY)
• Sorting, limiting, and ranking
• Advanced calculations using CTEs
• Window functions (DENSE_RANK, cumulative sums, frame clauses)
• Computed advanced metrics such as: top tracks per artist, energy-to-liveness ratios, difference between highest and lowest energy per album, cumulative likes ordered by views
• Implemented query optimization using indexes (CREATE INDEX)

⸻

Skills Acquired

Database & SQL Skills
• Creating tables and designing schemas
• Data cleaning and validation
• Aggregate functions & grouping
• JOINS & subqueries
• CTEs (WITH clauses)
• Window functions (DENSE_RANK, SUM OVER, ROWS BETWEEN…)
• Query optimization using indexes
• Understanding execution plans (EXPLAIN ANALYZE)

Data Analysis Skills
• Exploratory Data Analysis (EDA)
• Identifying trends and metrics in large datasets
• Extracting actionable insights from structured data
• Working with real-world, noisy datasets

Technical & Problem-Solving Skills
• Troubleshooting CSV import issues (quote handling, formatting)
• Managing large datasets in PostgreSQL
• Improving performance through indexing
• Writing clean, efficient, and scalable SQL queries

⸻

Version Française

Analyse de Données Spotify — Projet SQL Avancé

Présentation du projet

Dans ce projet, j’ai travaillé sur un dataset Spotify contenant des informations sur les artistes, les titres, les albums, les statistiques de streaming et plusieurs caractéristiques audio.
J’ai téléchargé le dataset, créé une table dans PostgreSQL puis importé les données.

Lors de l’import, j’ai rencontré un problème lié à l’utilisation des guillemets (double quotes au lieu de single quotes) dans le fichier CSV. Après correction du format, j’ai pu charger le dataset correctement et mener l’ensemble de l’analyse SQL.

Ce projet m’a permis d’appliquer et d’approfondir mes compétences en SQL, de l’exploration simple jusqu’aux requêtes avancées avec CTE et fonctions fenêtre.

⸻

Technologies utilisées
• PostgreSQL (moteur de base de données)
• SQL (DDL, DML, CTE, fonctions fenêtre)
• pgAdmin / psql (outils de gestion de la base)
• Fichier CSV Spotify (importation des données)

⸻

Travaux réalisés
• Création d’une table structurée correspondant au dataset Spotify
• Nettoyage des données (suppression des lignes invalides, vérification des champs, contrôle des valeurs distinctes)
• Réalisation d’une analyse exploratoire (EDA) : comptages, valeurs distinctes, vérification de la qualité des données
• Développement d’un ensemble de requêtes SQL de plusieurs niveaux :
• Niveau facile : filtres, agrégations, classements simples
• Niveau intermédiaire : moyennes par album, top 5 énergie, agrégations conditionnelles
• Niveau avancé : utilisation de CTE (WITH), fonctions fenêtre (DENSE_RANK, cumul de likes, frames ROWS BETWEEN…), calculs avancés (ratio energy/liveness, différence d’énergie par album)
• Mise en place d’une optimisation de requêtes via la création d’index
• Analyse des performances avec EXPLAIN ANALYZE

⸻

Compétences acquises

Compétences SQL
• Création de schémas et tables
• Nettoyage et préparation de données
• Requêtes avancées : GROUP BY, HAVING, sous-requêtes
• CTE (WITH) pour structurer des requêtes complexes
• Fonctions fenêtre (ranking, sommes cumulées, partitions)
• Optimisation SQL avec les index
• Lecture d’execution plans (EXPLAIN ANALYZE)

Compétences en analyse de données
• Analyse exploratoire sur un dataset réel
• Identification des métriques clés
• Analyse comparative (Spotify vs YouTube)
• Détection des valeurs extrêmes et anomalies
• Interprétation de résultats statistiques

Compétences techniques & résolution de problèmes
• Gestion d’import CSV et correction d’erreurs liées aux guillemets
• Manipulation d’un dataset volumineux
• Structuration logique d’un projet SQL
• Rédaction de requêtes performantes et lisiblesjet SQL
	•	Rédaction de requêtes performantes et lisibles
