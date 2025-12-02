# ⚖️ Projet 8 : Analysez des indicateurs de l'égalité femme-homme avec Knime

> **Construction d'un workflow ETL automatisé pour le calcul de l'Index de l'égalité professionnelle.**

Ce projet vise à auditer l'égalité salariale au sein d'une entreprise de services. La mission consiste à construire une chaîne de traitement de données (pipeline ETL) sur l'outil KNIME pour unifier les sources RH dispersées, anonymiser les informations personnelles et calculer les indicateurs légaux de l'index femmes-hommes.

---

## 🛠 Compétences Techniques (Hard Skills)
* **KNIME (Low-Code ETL) :** Conception d'un workflow complexe assurant la lecture, la transformation et l'exportation des données sans script de code.
* **Fusion de données (Data Merging) :** Jointure de multiples sources de données hétérogènes (`Info_Pro`, `Rémunération`, `Salarié`) pour reconstituer une base unique et cohérente.
* **Anonymisation (RGPD) :** Mise en place de techniques de masquage ou de suppression des données identifiantes pour garantir la confidentialité des salariés.
* **Dataviz & Reporting :** Création de graphiques analytiques pour visualiser les écarts de rémunération et production d'un fichier de synthèse CSV.

## 🧠 Compétences Générales (Soft Skills)
* **Rigueur réglementaire :** Respect strict des normes RGPD lors de la manipulation de données sensibles (Ressources Humaines).
* **Esprit d'analyse :** Interprétation des indicateurs calculés pour fournir un diagnostic clair sur la parité dans l'entreprise.
* **Organisation :** Structuration logique du workflow pour qu'il soit auditable et réutilisable.

---

<details>
<summary>📂 <b>Cliquez ici pour voir le contexte et les fichiers</b></summary>
<br>

### 📄 Contexte du projet
En tant que consultant Data Analyst dans un cabinet de conseil, je dois aider un client (entreprise de services de +50 salariés) à calculer son Index de l'égalité Femmes-Hommes. Les données RH sont fragmentées en plusieurs fichiers (Infos pro, Rémunération, Salariés) et nécessitent un retraitement complet avant analyse.

### 🎯 Objectifs de la mission
1. **Consolidation des données :** Réunir les trois fichiers sources (`Info_Pro.csv`, `Rémunération.csv`, `Salarié.csv`) en une seule base de travail via des jointures.
2. **Conformité RGPD :** Anonymiser les données personnelles avant toute étape de partage ou de visualisation.
3. **Calcul de l'Index :** Configurer le workflow pour automatiser le calcul des indicateurs officiels (écarts de salaire, augmentations, promotions, etc.).
4. **Visualisation :** Générer des graphiques illustrant les disparités et exporter les données nettoyées pour le client.

### 📂 Contenu du dossier
* `Zbakh_Jason_1_workflow_KNIME_052024.knwf` : Le workflow KNIME complet intégrant les nœuds de lecture, jointure, anonymisation et calcul.
* `Zbakh_Jason_2_fichier_csv_042024.csv` : Le fichier de sortie au format CSV, contenant les données agrégées et anonymisées.
* `Zbakh_Jason_3_support_presentation_042024.pptx` : Support de présentation détaillant la méthodologie ETL, les choix d'anonymisation et les résultats de l'index.

> *Note : Ce projet a été réalisé dans le cadre de la formation Data Analyst d'OpenClassrooms.*

</details>