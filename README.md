# Prédiction de la valeur des logements (Boston Housing)

Ce projet utilise un modèle de régression linéaire pour estimer la valeur médiane des logements à Boston, basé sur plusieurs caractéristiques telles que la criminalité, la pollution, etc.

## Fichiers

- `modele_boston.pkl` : modèle de régression linéaire entraîné
- `predict_boston.py` : script pour faire une prédiction
- `boston_clean.csv` : données nettoyées
- `README.md` : ce fichier

## Comment faire une prédiction

```python
import joblib
import pandas as pd

model = joblib.load("modele_boston.pkl")
# Charger vos données d'entrée ici...
