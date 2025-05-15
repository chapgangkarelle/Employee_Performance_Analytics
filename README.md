# Analyse des Performances Employés & Satisfaction au Travail

## 🎯 Objectif
Évaluer les écarts de performance et de satisfaction entre les départements afin d’orienter des décisions RH basées sur des données concrètes.

## 🧠 Problématique
L’entreprise a constaté des différences de performance entre les départements. Cette étude vise à confirmer l'existence de ces écarts et à comprendre les facteurs qui influencent la performance et la satisfaction des employés.

## 📊 Données utilisées
- 10 000 employés
- 20 variables (âge, département, score de performance, salaire, satisfaction, heures travaillées, etc.)
- Fichier source : `Extended_Employee_Performance_and_Productivity_Data.csv`

## 🔍 Méthodologie
- Nettoyage des données (valeurs manquantes, doublons)
- Analyse descriptive : distributions, écarts entre départements
- Tests statistiques :
  - Kruskal-Wallis (comparaison de groupes)
  - Test post-hoc de Dunn
  - Corrélation Spearman

## 📈 Résultats clés
- **Performance & Départements** : Différences significatives détectées, nuances entre certains départements.
- **Salaire & Performance** : Corrélation modérée, une performance plus élevée tend à être associée à un salaire plus élevé.
- **Heures travaillées & Performance** : Relation positive.
- **Satisfaction & Départements** : Variabilité significative détectée.

## 💡 Recommandations
- Repenser le système de récompenses pour valoriser la performance réelle
- Ajuster les salaires selon les niveaux de performance
- Identifier les départements à faible satisfaction et mener des enquêtes internes
- Promouvoir une culture de reconnaissance et de feedback constructif

## 📊 Visualisations
Le projet contient plusieurs visualisations pertinentes :
- Distribution des performances
- Boxplots de la satisfaction par département
- Corrélation entre variables clés (heatmap)
- Salaire mensuel selon le score de performance

## 🛠️ Technologies
Python – Pandas, Seaborn, Matplotlib

## ▶️ Exécution
1. Ouvrir le fichier `analyse.ipynb` sur Jupyter ou Google Colab
2. Suivre les étapes de nettoyage, analyse, et visualisation
3. Consulter les résultats et recommandations dans le notebook ou le rapport final
