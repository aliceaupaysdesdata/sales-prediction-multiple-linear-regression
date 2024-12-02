# sales_prediction_multiple_linear_regression
Ce projet, intitulé "Regression House Sales", est un exercice réalisé dans le cadre de la formation "Data analyst" suivie à la Wild Code School. L'exercice a été conçu pour développer une compréhension approfondie de l'exploration de bases de données et de la prédiction à l'aide de la régression linéaire multiple. L'objectif principal était de prédire les prix des maisons à partir d'un jeu de données. 

# Objectifs pédagogiques

A partir d'un notebook vierge : 
Maîtriser la manipulation et l'exploration de données avec Python (via pandas, numpy, et seaborn).
Identifier et corriger les problèmes dans les données (valeurs manquantes, doublons, types de colonnes incorrects).
Comprendre les relations entre variables (corrélations, distributions, et outliers).
Mettre en place une modélisation prédictive à l'aide de la régression linéaire multiple.


# Détails du jeu de données

Le jeu de données utilisé (« kc_house_data.csv ») comprend 21 colonnes et 21 613 entrées représentant les caractéristiques et les prix des maisons dans une région spécifique. Voici un échantillon des colonnes disponibles :

price : Prix de vente de la maison.
bedrooms : Nombre de chambres.
bathrooms : Nombre de salles de bain.
sqft_living : Superficie habitable en pieds carrés.
floors : Nombre d'étages.
waterfront : Présence d'une vue sur le bord de mer (booléen).
condition et grade : Qualité de la maison.

# Méthodologie

## 1. Exploration des données

Inspection initiale : Dimensions, types de données, et valeurs manquantes.

Visualisations : Histogrammes, boxplots, scatterplots et matrice de corrélation.

Nettoyage des données : Gestion des doublons, traitement des valeurs manquantes, et conversion des types incorrects.

## 2. Analyse des variables

Catégorisation des variables qualitatives et quantitatives.

Identification des relations entre variables (corrélation, moyennes par catégorie).

## 3. Modélisation prédictive

Implémentation d'une régression linéaire multiple.

Évaluation des performances du modèle (erreur quadratique moyenne, coefficient de détermination R²).

# Prérequis

Python 3.8+

Bibliothèques Python : pandas, numpy, matplotlib, seaborn, scikit-learn

# Utilisation

## Clonez ce dépôt :

git clone <URL-du-dépôt>

## Installez les dépendances :

pip install -r requirements.txt

## Lancez le notebook :

jupyter notebook "Regression House sales - Alice GONTIER.ipynb"

Suivez les étapes dans le notebook pour exécuter les analyses et le modèle.

# Structure du dépôt

Regression House sales - Alice GONTIER.ipynb : Notebook Jupyter contenant les analyses et modèles.

README.md : Documentation du projet.

# Résultats

Le modèle de régression linéaire multiple présente une bonne robustesse entre l'entrainement et le test. La qualité des prédictions reste moyennement performante avec des métriques d'évaluation acceptables pour un premier modèle. Les observations sur la qualité des données et les caractéristiques influentes permettent d'envisager des modèles plus avancés pour des prédictions encore plus précises.

# Auteur

Ce projet a été réalisé par Alice Gontier dans le cadre d'un exercice d'apprentissage des méthodologies d'analyse de données et de modélisation prédictive.

Licence

Ce projet est sous licence GPL.
