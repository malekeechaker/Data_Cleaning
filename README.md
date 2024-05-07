
# Traitement des données pour l'analyse des prix de l'immobilier

## Description
Ce projet présente le processus de nettoyage et de prétraitement des données basé sur un ensemble de données de prix de maisons. Le script permet de lire des données brutes et de les transformer pour un usage ultérieur, comme l'analyse des données ou la création de modèles prédictifs.

## Caractéristiques du jeu de données
- Données sur des propriétés immobilières, incluant des caractéristiques physiques, des finitions, des équipements, et des données sur les ventes.
- Initialement, 81 colonnes et 1460 lignes.
- Utilisé pour des analyses de marché ou des modèles prédictifs liés à l'immobilier.

## Étapes du traitement des données
1. **Lecture du jeu de données** : Le fichier CSV `house_prices.csv` est lu dans un DataFrame Pandas.
2. **Exploration initiale** : Affichage des premières lignes, des dimensions, et des types de données.
3. **Traitement des valeurs manquantes** :
   - Suppression des colonnes avec plus de 80% de valeurs manquantes.
   - Imputation des valeurs manquantes pour les colonnes catégoriques avec le mode.
   - Imputation des valeurs manquantes pour les colonnes numériques avec la moyenne ou la médiane.
   - Utilisation de modèles de régression pour combler les valeurs manquantes dans certaines colonnes.
4. **Gestion des doublons** : Vérification et suppression des lignes en double.
5. **Encodage des variables catégoriques** :
   - Utilisation de mappings pour encoder les colonnes ayant des valeurs ordonnées.
   - Utilisation de One-Hot Encoding pour les colonnes sans ordre spécifique.
6. **Normalisation/Standardisation** : Préparation des données numériques pour l'analyse ou les modèles prédictifs.

## Installation et exécution
- Pour exécuter le script, assurez-vous d'avoir Python installé avec Pandas, Numpy, Seaborn, et Scikit-learn.
- Copiez le script dans un fichier `.py`.
- Assurez-vous que le fichier `house_prices.csv` est présent dans le même répertoire que le script.
- Exécutez le script avec `Data_Cleaning_Project.py`.

## Contributions
Les contributions sont les bienvenues. Veuillez soumettre des demandes de tirage (pull requests) ou signaler des problèmes (issues) pour suggérer des améliorations.

## Contact
Pour toute question ou commentaire, veuillez contacter [votre adresse e-mail ou un autre point de contact].
