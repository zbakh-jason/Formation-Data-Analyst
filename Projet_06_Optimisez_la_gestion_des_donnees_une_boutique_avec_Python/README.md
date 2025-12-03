# 🍷 Projet 6 : Optimisez la gestion des données d'une boutique

> **Rapprochement de bases de données et analyse des ventes pour le marchand de vin Bottleneck.**

Ce projet consiste à unifier les données de gestion de stock (ERP) et de vente en ligne (CMS) de l'entreprise Bottleneck. L'objectif est de rendre les données exploitables pour calculer le chiffre d'affaires et analyser la cohérence des prix des produits.

---

## 🛠 Compétences Techniques (Hard Skills)
* **Data Visualization :** Représentation graphique de la répartition des prix (Boxplot, Scatterplot) pour identifier les écarts.
* **Nettoyage de données (Pandas) :** Traitement des fichiers, gestion des erreurs de saisie et vérification des clés primaires.
* **Rapprochement de données (Merging) :** Fusion des exports ERP et Web via une table de liaison pour créer un jeu de données unique (`df_web_erp`).
* **Analyse de données (Data Analysis) :** Calcul des indicateurs de vente et du chiffre d'affaires total.
* **Statistiques descriptives :** Détection des valeurs aberrantes (outliers) sur les prix via la méthode de l'écart interquartile (IQR).
* **Data Visualization :** Représentation graphique de la répartition des prix (Boxplot) et des corrélations (Scatterplot) pour identifier les écarts.

## 🧠 Compétences Générales (Soft Skills)
* **Rigueur :** Vérification minutieuse de l'unicité des clés et de la qualité du rapprochement entre deux sources déconnectées.
* **Esprit d'analyse :** Interprétation des écarts de prix pour distinguer les erreurs techniques des spécificités métier.
* **Synthèse :** Présentation structurée des résultats financiers et des anomalies détectées à la direction.

---

<details>
<summary>📂 <b>Cliquez ici pour voir le contexte et les fichiers</b></summary>
<br>

### 📄 Contexte du projet
L'entreprise **Bottleneck**, marchand de vin, souhaite analyser ses ventes en ligne. La manager, Sylvie, demande de réaliser un rapprochement manuel entre l'export de l'ERP et celui du site web (CMS) car les bases ne communiquent pas.

### 🎯 Objectifs et Résultats
1. **Rapprochement des exports :** Fusion des fichiers `erp.xlsx` et `web.xlsx` pour obtenir une base consolidée de **713 produits**.
2. **Calcul du Chiffre d'Affaires :** Le calcul sur les données rapprochées aboutit à un CA total de **143 505,09 €**.
3. **Analyse des prix :** L'analyse statistique a permis de détecter **31 outliers** (valeurs atypiques). Ces produits correspondent à des vins à forte valorisation et non à des erreurs.

### 📂 Contenu du dossier
* `Zbakh_Jason_1_notebook_022024.ipynb` : Le notebook Jupyter contenant le code Python pour l'importation, le nettoyage, la jointure des tables et l'analyse exploratoire.
* `Zbakh_Jason_2_presentation_022024.pptx` : Support de présentation résumant la méthodologie de rapprochement et l'analyse des résultats (CA de 143k€).

> *Note : Ce projet a été réalisé dans le cadre de la formation Data Analyst d'OpenClassrooms.*

</details>