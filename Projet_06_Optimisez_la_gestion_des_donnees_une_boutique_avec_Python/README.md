# 🍷 Projet 6 : Optimisez la gestion des données d'une boutique

> **Rapprochement de bases de données et analyse des ventes pour le marchand de vin Bottleneck.**

Ce projet consiste à unifier les données de gestion de stock (ERP) et de vente en ligne (CMS) de l'entreprise Bottleneck. L'objectif est de rendre les données exploitables pour calculer le chiffre d'affaires et analyser la cohérence des prix des produits.

---

## 🛠 Compétences Techniques (Hard Skills)
* **Nettoyage de données (Pandas) :** Importation et nettoyage des fichiers Excel (ERP, Web, Liaison), gestion des doublons et vérification de l'unicité des clés primaires (product_id).
* **Rapprochement de données (Merging) :** Fusion des tables pour créer un jeu de données unique reliant les références produits aux ventes en ligne.
* **Analyse statistique :** Calcul du chiffre d'affaires et détection des valeurs aberrantes (outliers) sur les prix via la méthode de l'écart interquartile (IQR).
* **Data Visualization :** Représentation graphique de la répartition des prix (Boxplot, Scatterplot) pour identifier les écarts.

## 🧠 Compétences Générales (Soft Skills)
* **Rigueur :** Vérification minutieuse des clés de liaison pour garantir l'intégrité du rapprochement entre l'ERP et le site Web.
* **Esprit d'analyse :** Interprétation des outliers pour distinguer les erreurs potentielles des produits à forte valeur ajoutée.
* **Synthèse :** Présentation claire des résultats financiers (CA) et de l'analyse des prix à la direction.

---

<details>
<summary>📂 <b>Cliquez ici pour voir le contexte et les fichiers</b></summary>
<br>

### 📄 Contexte du projet
L'entreprise **Bottleneck**, marchand de vin, souhaite analyser ses ventes. La manager, Sylvie, demande de réaliser un rapprochement entre l'export de l'ERP et celui du site de vente en ligne (CMS), car ces bases ne communiquent pas nativement.

### 🎯 Objectifs de la mission
1. **Rapprochement des exports :** Fusionner les fichiers `erp.xlsx` et `web.xlsx` via la table de correspondance `liaison.xlsx`. Résultat : 714 produits rapprochés.
2. **Calcul du Chiffre d'Affaires :** Calculer le CA par produit et le CA total réalisé en ligne, qui s'élève à 70 568,6 €.
3. **Analyse des prix :** Détecter les prix aberrants. L'analyse a révélé 32 outliers, correspondant principalement à des vins haut de gamme, expliqués et justifiés graphiquement.

### 📂 Contenu du dossier
* `Zbakh_Jason_1_notebook_022024.ipynb` : Notebook Jupyter contenant le code Python pour l'importation, le nettoyage, le rapprochement des fichiers et l'analyse exploratoire (CA et Outliers).
* `Zbakh_Jason_2_presentation_022024.pptx` : Support de présentation résumant la méthodologie, le chiffre d'affaires global et l'analyse des outliers (méthode interquartile).

> *Note : Ce projet a été réalisé dans le cadre de la formation Data Analyst d'OpenClassrooms.*

</details>