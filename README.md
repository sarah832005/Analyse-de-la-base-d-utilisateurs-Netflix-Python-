
# 🎬 Analyse de la base d'utilisateurs Netflix (Python)

## 🎯 Objectif du projet
Ce projet consiste à analyser et explorer le dataset **Netflix Userbase** afin d’en extraire des insights sur les abonnés :  
- Répartition des types d’abonnement  
- Revenus mensuels  
- Comportements selon les pays, genres, et appareils utilisés  
- Relations entre âge, durée d’abonnement et revenus  

L’analyse repose sur la **manipulation de données avec Pandas/Numpy**, la **visualisation avec Matplotlib et Seaborn**, ainsi que la **préparation des données pour l’intelligence artificielle** (encodage, normalisation, standardisation).  

---

## ⚙️ Étapes principales

### 📂 Préparation et exploration
- Importation et chargement du fichier `Netflix Userbase.csv`  
- Aperçu des données (`head`, `tail`, `info`, `describe`)  
- Détection des **valeurs manquantes** et **doublons**  
- Conversion des colonnes de dates (`Join Date`, `Last Payment Date`)  
- Création d’une nouvelle variable : **durée d’abonnement en jours**  

### 📊 Analyses descriptives
- Distribution de l’**âge** et du **revenu mensuel** (histogrammes)  
- Analyse des colonnes catégorielles (pays, type d’abonnement, genre, appareil, durée du plan)  
- Boxplots pour visualiser la dispersion des variables numériques  

### 🌍 Analyses approfondies
- Identification du **pays générant le plus/moins de revenus**  
- Étude des corrélations (matrice et heatmap)  
- Relations :  
  - Revenu mensuel ↔ Durée d’abonnement  
  - Âge ↔ Revenu mensuel  
- Visualisation de la répartition des abonnements par **pays** et **type d’abonnement** (heatmaps, diagrammes en barres, camemberts)  
- Analyse par **genre**, **appareil**, **durée d’abonnement**  

### 🤖 Préparation pour le Machine Learning
- Encodage des variables catégorielles :  
  - **OneHotEncoder**  
  - **OrdinalEncoder**  
- Normalisation et standardisation des données numériques (`MinMaxScaler`, `StandardScaler`)  
- Préparation des données pour une éventuelle modélisation (classification ou clustering).  

---

## 🛠️ Technologies et bibliothèques
- **Python 3**  
- **Pandas, Numpy** → manipulation de données  
- **Matplotlib, Seaborn** → visualisation des données  
- **Scikit-learn (sklearn)** → prétraitement (encodage, normalisation, standardisation)  

---
