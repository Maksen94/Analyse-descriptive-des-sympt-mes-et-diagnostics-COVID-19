📊 Analyse Descriptive : Symptômes et Diagnostics COVID-19

Ce projet constitue ma première réalisation pratique en analyse de données. L'objectif principal était de maîtriser le cycle de vie complet de la donnée, de l'extraction à la visualisation, en respectant un cahier des charges fonctionnel strict.

🔗 Accès au Projet

* [Lien vers le Google Sheet](https://docs.google.com/spreadsheets/d/1s1ESg7HM7SulELOBB_1KzpHCFWjwXttk_07mKrzgXFo/edit?usp=sharing) 

🎯 Objectifs du projet

* Explorer un jeu de données clinique pour identifier des tendances.
* Nettoyer et Normaliser des données brutes pour les rendre exploitables.
* Visualiser les corrélations entre l'âge, la zone géographique et la prévalence des symptômes (fièvre, toux).

📂 Source des Données

Le jeu de données utilisé est issu de la plateforme Kaggle : "COVID-19 Patient Symptoms and Diagnosis Dataset".
Il recense les données démographiques et cliniques de patients répartis sur plusieurs zones géographiques.

* Lien Kaggle : https://www.kaggle.com/datasets/shraddha4ever20/covid-19-patient-symptoms-and-diagnosis-dataset

🛠️ Outils & Méthodologie

Ce projet a été réalisé intégralement sur Google Sheets, utilisé comme outil central pour toutes les étapes du traitement.

 1. Préparation des données (Data Cleaning)
* Nettoyage des entrées erronées.
* Normalisation des unités de mesure, notamment la conversion des températures de Fahrenheit (F°) vers Celsius (C°).
  
2. Ingénierie des fonctionnalités (Feature Engineering)
* Création de colonnes calculées pour faciliter l'analyse.
* Utilisation de fonctions logiques avancées comme `NB.SI.ENS` (COUNTIFS) pour croiser les variables (ex: Âge vs Diagnostic / Ville vs Symptômes).

3. Visualisation (Data Viz)
* Conception de graphiques comparatifs (histogrammes) pour identifier les corrélations majeures.
  
💡 Résultats & Insights Clés

L'analyse des 482 cas a permis de mettre en lumière les points suivants :

🩺 1. Facteur Âge
* Tendance lourde : La tranche d'âge des 31-85 ans est systématiquement la plus touchée, représentant environ 65% à 70% des cas positifs.
* À l'inverse, les 5-30 ans ne représentent qu'un tiers des contaminations (env. 30-35%).

📍 2. Disparités Géographiques (Toux & Fièvre)
Il existe une forte disparité des symptômes selon les villes :
* Toux : À Delhi et Mumbai, la toux forte est majoritaire. À l'inverse, à Kolkata et Bangalore, la majorité des cas positifs présentent une toux faible ou absente.
* Fièvre : Indicateur plus constant que la toux. Elle est présente majoritairement dans 3 villes sur 4, avec un pic à près de 60% à Bangalore.
* Exception : Kolkata se distingue par une absence de fièvre majoritaire chez les patients positifs.

📝 Conclusion

Cette analyse démontre que si l'âge est un facteur de risque constant, la symptomatologie varie fortement selon les zones géographiques. Cela suggère l'importance d'adapter les protocoles de détection aux spécificités locales plutôt que d'appliquer un modèle unique.


---
*Projet réalisé par Maksen Benkerrou - Étudiant en Bachelor Data & IA*
