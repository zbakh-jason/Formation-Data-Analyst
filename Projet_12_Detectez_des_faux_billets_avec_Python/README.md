# 💸 Projet 12 : Détectez des faux billets avec Python

> **Développement d'un algorithme de détection de faux billets pour l'ONCFM.**

Ce projet final consiste à développer une solution d'intelligence artificielle pour l'Organisation nationale de lutte contre le faux-monnayage (ONCFM). La mission est de construire un modèle capable de prédire l'authenticité de billets de banque en analysant leurs caractéristiques géométriques grâce à des algorithmes de classification.

---

## 🛠 Compétences Techniques (Hard Skills)
* **Machine Learning (Scikit-learn) :** Entraînement et comparaison de modèles prédictifs : Classification supervisée (**Régression Logistique**) et Classification non supervisée (**K-Means**).
* **Data Cleaning & Imputation :** Traitement avancé des valeurs manquantes via une **Régression Linéaire** pour conserver l'intégrité statistique du jeu de données.
* **Analyse de données (Pandas/Seaborn) :** Exploration des données et visualisations pour comprendre la distribution des dimensions (longueur, hauteur, marges).
* **Réduction de dimension (ACP) :** Utilisation de l'Analyse en Composantes Principales pour visualiser la séparabilité des classes (Vrais vs Faux) sur un plan factoriel.
* **Déploiement :** Création d'un script d'application fonctionnel capable de traiter de nouveaux fichiers de production.

## 🧠 Compétences Générales (Soft Skills)
* **Rigueur méthodologique :** Comparaison des performances des modèles via des matrices de confusion pour sélectionner l'algorithme le plus robuste.
* **Vulgarisation :** Présentation des résultats techniques et des recommandations à une audience métier non-experte.
* **Esprit de synthèse :** Rédaction d'une conclusion argumentée justifiant le choix du modèle final.

---

<details>
<summary>📂 <b>Cliquez ici pour voir le contexte et les fichiers</b></summary>
<br>

### 📄 Contexte du projet
L'**ONCFM** souhaite s'équiper d'un outil performant pour automatiser la détection des contrefaçons. En tant que Data Analyst, la mission consiste à analyser un jeu de données de 1500 billets contenant des mesures géométriques précises (longueur, hauteur, marges, diagonale). L'objectif est de produire un algorithme capable de distinguer les vrais billets des faux avec une haute précision.

### 🎯 Objectifs de la mission
1. **Exploration et Nettoyage :** Analyser les statistiques descriptives et combler les valeurs manquantes (imputation) grâce à une régression linéaire.
2. **Analyse visuelle :** Réaliser une Analyse en Composantes Principales (ACP) pour observer les différences géométriques et la séparation des groupes.
3. **Modélisation :**
   * Tester une approche par Clustering (**K-Means**) pour voir si les groupes se forment naturellement.
   * Entraîner une **Régression Logistique** pour prédire la nature des billets.
4. **Mise en production :** Livrer un programme qui prend en entrée un fichier de production (ex: `billets_production.csv`) et génère les prédictions d'authenticité.

### 📂 Contenu du dossier
* `Zbakh_Jason_1_Notebook_analyse_102024.ipynb` : Le notebook principal contenant l'analyse exploratoire, l'imputation par régression, l'ACP et la comparaison des modèles.
* `Zbakh_Jason_2_Notebook application_102024.ipynb` : Le notebook d'application permettant de lancer le modèle final sur de nouvelles données.
* `Zbakh_Jason_3_presentation_082024.pdf` : Support de présentation résumant la méthodologie, les résultats de l'ACP et la performance du modèle retenu.

> *Note : Ce projet a été réalisé dans le cadre de la formation Data Analyst d'OpenClassrooms.*

</details>