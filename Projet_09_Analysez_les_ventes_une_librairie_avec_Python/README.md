# 📚 Projet 9 : Analysez les ventes d'une librairie avec Python

> **Analyse exploratoire, nettoyage de données et tests statistiques pour la librairie Lapage.**

Ce projet consiste à analyser les données de ventes de la librairie en ligne **Lapage**. L'objectif est d'auditer les données, d'analyser les indicateurs de performance (Chiffre d'affaires, comportements clients) et de vérifier des hypothèses marketing via des tests statistiques pour orienter la stratégie de l'entreprise.

---

## 🛠 Compétences Techniques (Hard Skills)
* **Data Cleaning (Python/Pandas) :** Fusion des fichiers (`Transactions`, `Products`, `Customers`), gestion des valeurs manquantes, traitement des dates et identification des incohérences (ex: problème de données en octobre 2021).
* **Analyse Statistique :**
    * **Concentration :** Calcul de la courbe de Lorenz et du coefficient de Gini pour mesurer la répartition des ventes entre les clients (ou produits).
    * **Tests d'hypothèses :** Utilisation de tests adaptés aux types de variables : Test de **Chi-2** (variables qualitatives), **ANOVA** (qualitative/quantitative) et corrélation de **Pearson**.
* **Time Series :** Analyse de l'évolution temporelle du chiffre d'affaires et lissage par moyenne mobile.
* **Data Visualization :** Création de graphiques analytiques (Histogrammes, Boxplots, Heatmaps) avec Matplotlib et Seaborn.

## 🧠 Compétences Générales (Soft Skills)
* **Esprit critique :** Détection et interprétation d'anomalies dans les données (chute brutale du CA liée à un problème technique/logistique).
* **Vulgarisation :** Présentation des résultats statistiques complexes de manière accessible pour les équipes Marketing (Julie) et la Direction (Antoine).
* **Compréhension métier :** Traduction des besoins marketing (profils clients, succès des catégories) en analyses techniques.

---

<details>
<summary>📂 <b>Cliquez ici pour voir le contexte et les fichiers</b></summary>
<br>

### 📄 Contexte du projet
L'entreprise **Lapage**, librairie en ligne, souhaite faire le point sur ses indicateurs de vente. N'ayant pas mis à jour son tableau de bord depuis un moment, la direction a besoin d'une analyse ponctuelle complète. Julie (Marketing) et Antoine (Manager) sollicitent cette étude pour comprendre qui sont les clients et comment se répartissent les ventes.

### 🎯 Objectifs de la mission
1.  **Nettoyage et Préparation :**
    * Importer et fusionner les exports (`customers`, `products`, `transactions`).
    * Analyser les erreurs potentielles et nettoyer le jeu de données.
2.  **Analyse des Indicateurs de Vente :**
    * Calculer le Chiffre d'Affaires (CA) total et son évolution mensuelle.
    * Analyser les Tops/Flops des livres et la répartition par catégorie.
    * Comprendre la chute des ventes observée en octobre 2021.
3.  **Analyse du Comportement Client :**
    * Utiliser la courbe de Lorenz et le coefficient de Gini pour étudier la répartition du CA par client.
    * Analyser les profils d'âge et de sexe.
4.  **Tests Statistiques (Corrélations) :**
    * Lien entre le **Sexe** et la **Catégorie** de livre achetée (Test Chi-2).
    * Lien entre l'**Âge** et le **Montant total** des achats.
    * Lien entre l'**Âge** et la **Fréquence** d'achat.
    * Lien entre l'**Âge** et la **Taille du panier moyen**.
    * Lien entre l'**Âge** et la **Catégorie** de livre (ANOVA).

### 📂 Contenu du dossier
* `Zbakh_Jason_1_notebook_052024.ipynb` : Notebook Python contenant l'intégralité du code (nettoyage, graphiques, calculs statistiques).
* `Zbakh_Jason_2_presentation_052024.pptx` : Support de présentation résumant la méthodologie, les graphiques clés et l'interprétation des tests statistiques.

> *Note : Ce projet a été réalisé dans le cadre de la formation Data Analyst d'OpenClassrooms.*

</details>