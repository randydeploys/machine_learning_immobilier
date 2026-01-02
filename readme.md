# Projet : Prédiction des Prix Immobiliers en Californie

Ce projet constitue votre première mission : construire un modèle de Machine Learning capable de prédire le prix médian des habitations en Californie.

## Objectif du projet

L'objectif est de créer un modèle qui apprend à partir des données pour **prédire le prix médian des logements** dans n'importe quel district, en fonction des autres variables fournies.

## Données utilisées

Nous utilisons le jeu de données **California Housing Prices** provenant de l'entrepôt *StatLib*.

* Source : Données du recensement californien de 1990. (https://www.kaggle.com/datasets/camnugent/california-housing-prices?select=housing.csv)

* Granularité : Les données sont regroupées par « districts » (la plus petite subdivision du recensement, regroupant généralement entre 600 et 3 000 personnes).

* Actualité : Bien que les données datent de 1990, nous les traiterons comme des données récentes à des fins pédagogiques.

* Modifications : Pour les besoins de l'exercice, une variable qualitative a été ajoutée et certaines variables ont été supprimées par rapport au jeu de données original.

## Variables et caractéristiques

Le modèle s'appuie sur plusieurs variables quantitatives pour chaque district, dont :

* 👥 **Population**
* 💰 **Revenu médian** (*Median Income*)
* 📍 **Localisation** (Latitude / Longitude)
* 🏠 **Prix médian des habitations** (Variable cible)

## Installation et Prérequis

Pour exécuter ce projet, vous aurez besoin de Python et des librairies standards de Data Science :

```bash
pip install numpy pandas matplotlib scikit-learn
```

et du fichier "housing.csv" dans le dossier "data".