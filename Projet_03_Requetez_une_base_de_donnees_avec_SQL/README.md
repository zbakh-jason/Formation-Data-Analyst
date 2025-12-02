# 🏠 Projet 3 : Requêtez une base de données avec SQL

> **Création d'une base de données et analyse du marché des assurances habitation.**

Ce projet consiste à aider une entreprise d'assurance à mieux accompagner ses clients en analysant le marché des assurances habitation. L'objectif est de concevoir une base de données relationnelle à partir de fichiers clients et géographiques, puis d'extraire des indicateurs précis à l'aide de requêtes SQL.

---

## 🛠 Compétences Techniques (Hard Skills)
* **SQL (Structured Query Language) :** Rédaction de requêtes pour explorer et extraire des informations (SELECT, JOIN, GROUP BY, HAVING, ORDER BY).
* **Modélisation de données (3NF) :** Conception d'un schéma relationnel normalisé respectant l'atomicité et les dépendances des données.
* **Administration de BDD (SGBD SQLite) :** Création de tables, définition des contraintes (Clés primaires/étrangères) et import de données CSV.
* **Dictionnaire des données :** Identification des types de variables (INT, VARCHAR, FLOAT) et définition des contraintes de taille.

## 🧠 Compétences Générales (Soft Skills)
* **Logique :** Construction d'un cheminement logique pour traduire des besoins d'analyse en requêtes techniques.
* **Rigueur :** Respect des normes réglementaires et vérification de l'intégrité des données (30 335 contrats, 38 916 régions).
* **Pédagogie :** Explication de la méthodologie technique et présentation synthétique des résultats.

---

<details>
<summary>📂 <b>Cliquez ici pour voir le contexte et les fichiers</b></summary>
<br>

### 📄 Contexte du projet
Dans le cadre de ce projet, l'entreprise souhaite analyser le marché des assurances habitation pour mieux accompagner ses clients. Il est nécessaire de structurer les données brutes (Contrats et Régions) dans un système de gestion de base de données (SQLite) afin de pouvoir les interroger efficacement.

### 🎯 Objectifs de la mission
1. **Exploration des données :** Création d'un dictionnaire de données et identification des clés primaires et étrangères.
2. **Modélisation :** Réalisation d'un schéma relationnel normalisé en 3ème forme normale (3NF).
3. **Implémentation :** Écriture du code SQL de création des tables et chargement des données.
4. **Analyse SQL (12 Requêtes) :**
   * Analyse des surfaces (Moyenne à Paris, Top 5 des surfaces les plus élevées).
   * Analyse des coûts (Prix moyen de cotisation, classement des départements par prix).
   * Segmentation (Nombre de contrats par catégorie de prix, par région, par type de résidence).
   * Ciblage géographique (Contrats à Caen, Maisons dans le 71, Communes avec >150 contrats).

### 📂 Contenu du dossier
* `Zbakh_Jason_1_document technique_112023.pdf` : Document technique contenant le dictionnaire des données, le schéma relationnel en 3NF, le code SQL de création (DDL) et les preuves d'import des données.
* `Zbakh_Jason_2_liste_112023.docx` : Liste complète des 12 requêtes SQL réalisées avec le code source et les captures d'écran des résultats obtenus.
* `Zbakh_Jason_3_méthodologie_112023.pdf` : Support de présentation détaillant les étapes de réalisation : identification des données, modélisation, création des tables et interrogation de la base.
* `Zbakh_Jason_4_check_list_auto_evalution_112023.pdf` : Grille d'auto-évaluation validant les critères de réussite (respect 3NF, fonctionnalité des requêtes, structure de la présentation).

> *Note : Ce projet a été réalisé dans le cadre de la formation Data Analyst d'OpenClassrooms.*

</details>