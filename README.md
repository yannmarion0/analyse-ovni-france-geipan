# 🛸 Analyse des Observations d'OVNIs en France (GEIPAN)

![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-BigQuery-4169E1?style=for-the-badge&logo=google-cloud&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)

## 📌 Présentation du Projet
Ce projet propose une analyse complète des données du **GEIPAN** (Groupe d'Études et d'Informations sur les Phénomènes Aérospatiaux Non identifiés). L'objectif est de transformer des données brutes complexes en un dashboard interactif permettant d'explorer les observations d'OVNIs en France de 1937 à nos jours.

**🔗 Liens rapides :**
* [Notebook complet sur Kaggle](https://www.kaggle.com/code/yannmarion/observations-france)
* [Dashboard Interactif Tableau](https://public.tableau.com/views/Observations_ovnis/Tableaudebord1?:language=fr-FR&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## Pipeline Technique (Stack Data)

Le projet est divisé en trois étapes majeures illustrant une maîtrise complète de la chaîne de donnée :

### 1. Data Cleaning & Preprocessing (R)
Traitement d'un dataset brut avec des séparateurs complexes (`|`) et des problèmes d'encodage.
* Utilisation du **Tidyverse** pour le nettoyage des colonnes.
* Formatage des dates et gestion des valeurs manquantes.

### 2. Data Transformation & Cloud Data Warehouse (SQL / BigQuery)
Importation des données nettoyées dans **Google BigQuery** pour un enrichissement structuré.
* Création d'une logique de **Mapping Géographique** (via `CASE WHEN`) pour regrouper les départements en régions françaises.
* Agrégation des données pour optimiser les performances de visualisation.

### 3. Visualisation Interactive (Tableau)
Conception d'un dashboard décisionnel pour l'exploration des données.
* **Carte de chaleur (Heatmap)** des observations par région.
* **Analyse temporelle** des pics d'activité.
* Filtres dynamiques par classification de phénomène.

---

## Aperçu du Dashboard
*(Remplace l'image ci-dessous par une capture d'écran de ton dashboard)*
[![Tableau Dashboard](https://github.com/yannmarion0/analyse-ovni-france-geipan/blob/main/ca.JPG)

---

## Key Findings (Aperçu)
* **Clusters Géographiques :** Identification de zones de forte activité (notamment le Sud-Est et l'Occitanie).
* **Qualité des données :** Plus de 50% des cas sont désormais classés comme identifiés, reflétant l'amélioration des outils d'analyse au fil des ans.

---

## 👤 Contact
**Yann Marion** *Data Analyst Junior | Spécialiste R, SQL & Tableau* [Mon profil Fiverr](https://fr.fiverr.com/sellers/yann_marion) | [Mon LinkedIn](https://www.linkedin.com/in/yann-marion-42b8a2256/)
