# Prediction_Nombre_de_Medailles

Le but de ce projet est de prédire le nombre de médailles remportées par différents pays lors de compétitions sportives, en utilisant des données sur les pays, le nombre d'athlètes, leur âge, et d'autres facteurs pertinents. Le modèle utilisé est une régression linéaire, qui permet d'analyser les relations entre les variables d'entrée et le nombre de médailles gagnées.
## Technologies Utilisées

- **Python** : Langage de programmation principal.
- **Pandas** : Pour la manipulation et l'analyse des données.
- **NumPy** : Pour les calculs numériques et la gestion des tableaux.
- **Scikit-learn** : Pour la création et l'évaluation du modèle de régression linéaire.

## Bibliothèques

Voici les principales bibliothèques utilisées dans ce projet :

```python
import pandas as pd
import numpy as np
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_absolute_error
```

## Fonctionnalités
-**Chargement des Données** : Les données sont chargées à partir d'un fichier CSV contenant des informations sur les pays, les médailles gagnées, le nombre d'athlètes, et leur âge.

-**Prétraitement des Données** : Les données sont nettoyées et préparées pour l'analyse, y compris le traitement des valeurs manquantes et la normalisation des données si nécessaire.

-**Séparation des Données** : Les données sont divisées en ensembles d'entraînement et de test.

-**Création du Modèle** : Un modèle de régression linéaire est créé à l'aide de Scikit-learn.

-**Entraînement du Modèle** : Le modèle est entraîné sur l'ensemble d'entraînement.

-**Prédiction et Évaluation** : Les prédictions sont effectuées sur l'ensemble de test et l'erreur absolue moyenne (MAE) est calculée pour évaluer la performance du modèle.

## Résultats
Après l'exécution du projet, le nombre prédit de médailles sera affiché, accompagné de l'erreur absolue moyenne calculée, permettant ainsi d'évaluer la précision des prédictions.
