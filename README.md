# Brain Tumor Classification Model

A deep learning model to classify brain MRI images as having or not having a tumor.

## Installation

```bash
pip install -r requirements.txt
```

## Structure du projet

main.ipynb - Le notebook avec tout le code. C'est là qu'on charge les données, entraîne le modèle et fait les prédictions.

Data/brain_tumor_dataset/ - Les images IRM séparées en deux dossiers :
  - yes/ : images avec tumeur
  - no/ : images sans tumeur

model/brain_tumor_model.pth - Le modèle déjà entraîné. Tu peux l'utiliser directement pour faire des prédictions sans réentraîner.

requirements.txt - Liste des bibliothèques à installer.


## Utilisation

Ouvrez `main.ipynb` et exécutez les cellules pour :
- Charger les données
- Entraîner le modèle
- Faire des prédictions

## Dépendances

Voir `requirements.txt`
