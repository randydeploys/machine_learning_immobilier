# Roadmap du projet

## 1. Cadrage et Vision
- [ ] Définir l'objectif métier (À quoi sert le modèle ?).
- [ ] Identifier l'utilisation finale (API, rapport, batch ?).
- [ ] Analyser l'état de l'art (Solutions actuelles).
- [ ] Déterminer le type de problème (Supervisé, Régression, etc.).
- [ ] Choisir la mesure de performance (RMSE, MAE...).
- [ ] Lister et vérifier les hypothèses.

## 2. Récupération des Données
- [ ] Identifier les sources de données (StatLib / Census).
- [ ] Vérifier les contraintes légales/accès.
- [ ] Créer l'environnement de travail.
- [ ] Convertir les données (CSV/Pandas).
- [ ] **Créer un jeu de test (Test Set) et le mettre de côté (NE PAS TOUCHER).**

## 3. Exploration des Données (EDA)
- [ ] Étudier chaque attribut (Type, manquants, bruit).
- [ ] Visualiser les distributions (Histogrammes).
- [ ] Étudier les corrélations (Matrice de corrélation).
- [ ] Visualiser les données géographiques (Latitude/Longitude).
- [ ] Identifier les valeurs aberrantes (Outliers).

## 4. Préparation des Données
- [ ] Nettoyage : Gérer les valeurs manquantes (Imputation).
- [ ] Nettoyage : Gérer les outliers.
- [ ] Feature Engineering : Créer de nouvelles variables (ex: pièces par ménage).
- [ ] Feature Selection : Supprimer les variables inutiles.
- [ ] Encodage : Transformer les variables catégorielles (OneHotEncoder).
- [ ] Scaling : Standardisation ou Normalisation.
- [ ] *Optionnel : Créer un Pipeline de transformation.*

## 5. Sélection des Modèles (Shortlist)
- [ ] Entraîner plusieurs modèles rapides (Linéaire, SVM, Arbre, Forêt...).
- [ ] Comparer via Validation Croisée (Cross-Validation).
- [ ] Analyser les types d'erreurs pour chaque modèle.
- [ ] Sélectionner les 3 à 5 meilleurs modèles.

## 6. Affinage (Fine-tuning)
- [ ] Optimiser les hyperparamètres (GridSearchCV / RandomizedSearchCV).
- [ ] Essayer les méthodes d'ensemble (Random Forest, Boosting...).
- [ ] Évaluer la performance finale sur le **Jeu de Test**.

## 7. Présentation
- [ ] Documenter la méthode et les résultats.
- [ ] Créer une présentation impactante (Focus métier).
- [ ] Expliquer ce qui a fonctionné et ce qui a échoué.

## 8. Déploiement
- [ ] Nettoyer le code pour la production.
- [ ] Sauvegarder le modèle final (Joblib/Pickle).
- [ ] (Optionnel) Créer une API ou un script de prédiction.