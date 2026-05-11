# 🧠 Prédiction de la Dépression chez les Étudiants

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
</div>

<br>

Ce projet d'analyse de données et d'apprentissage automatique (Machine Learning) a pour objectif de **prédire la dépression chez les étudiants** en se basant sur diverses caractéristiques démographiques, académiques et de style de vie.

## 🎯 Objectifs du Projet
- **Analyse Exploratoire des Données (EDA)** : Comprendre la distribution de la dépression en fonction du genre, des habitudes de sommeil, du stress académique et financier.
- **Prétraitement des Données** : Nettoyage des données, gestion des valeurs manquantes (ex: Durée de sommeil), et encodage des variables catégorielles.
- **Modélisation** : Entraînement et évaluation de modèles de classification tels que la **Régression Logistique** et le **Random Forest** pour détecter la présence de dépression.

## 📊 À Propos du Jeu de Données
Le jeu de données utilisé (`student_depression_dataset.csv`) comprend **27 901 enregistrements** et **18 colonnes** :
- **Démographie** : `Gender` (Genre), `Age`, `City` (Ville).
- **Parcours Académique/Professionnel** : `Profession`, `Degree` (Diplôme), `CGPA` (Moyenne), `Work/Study Hours` (Heures de travail/étude).
- **Indicateurs de Pression** : `Academic Pressure` (Pression académique), `Work Pressure` (Pression au travail), `Financial Stress` (Stress financier).
- **Santé Mentale & Mode de Vie** : `Sleep Duration` (Durée du sommeil), `Dietary Habits` (Habitudes alimentaires), `Study/Job Satisfaction`, `Family History of Mental Illness` (Antécédents familiaux), `Have you ever had suicidal thoughts ?` (Pensées suicidaires).
- **Variable Cible (Target)** : `Depression` (0 = Non, 1 = Oui).

## 🛠️ Outils et Bibliothèques
- **Analyse et Manipulation** : `Pandas`, `NumPy`
- **Visualisation** : `Matplotlib`, `Seaborn`, `Plotly`
- **Machine Learning** : `Scikit-Learn` (Logistic Regression, Random Forest, LabelEncoder, StandardScaler)

## 🚀 Comment utiliser ce projet ?

1. **Prérequis** : Assurez-vous d'avoir installé Python et les bibliothèques requises.
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn plotly
   ```

2. **Exécution du Notebook** : 
   Ouvrez le fichier `Student_Depression.ipynb` avec Jupyter Notebook ou Jupyter Lab :
   ```bash
   jupyter notebook Student_Depression.ipynb
   ```
   
3. **Déroulement de l'analyse** :
   - Étape 1 : Chargement et exploration initiale des données.
   - Étape 2 : Nettoyage (extraction des valeurs numériques de la durée de sommeil, imputation des valeurs manquantes).
   - Étape 3 : Visualisation (EDA) pour trouver les corrélations.
   - Étape 4 : Modélisation et évaluation des performances (Accuracy, Matrice de confusion, Courbe ROC).

---
*Projet développé dans le cadre de l'analyse des facteurs de risque de dépression en milieu étudiant.*
