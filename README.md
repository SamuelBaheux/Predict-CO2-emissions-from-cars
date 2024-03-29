# Estimate CO2 from Cars

Ce challenge kaggle vise à prédire les émissions de dioxyde de carbone (CO2) des véhicules en utilisant un ensemble de données comprenant des informations détaillées sur divers aspects des véhicules.

Les données utilisées dans le cadre de ce challenge sont disponibles à cette adresse: 
[Estimate CO2 from cars](https://www.kaggle.com/competitions/estimate-co2-emissions-from-cars)
## Installation

Pour garantir un environnement de développement isolé, nous vous recommandons d'utiliser un environnement virtuel (venv). Suivez ces étapes pour créer votre environnement virtuel et installer les dépendances du projet :

1. Cloner le dépôt github
```bash
git clone https://github.com/AxelFritz2/Challenge_Kaggle_Mosef.git
cd Challenge_Kaggle_Mosef
```
2. Créer l'environnement virtuel
```bash
python -m venv venv
```

3. Activer l'environnement virtuel

- Sur Windows : 
    ```bash
  .\venv\Scripts\Activate
    ```
- Sur Linux/Mac
    ```bash
  source venv/bin/activate
    ```

4. installer les dépendances

```bash
pip install -r requirements.txt
```

## Structure du Projet

- **src**: Les sources du projet, ce dossier comprend le script de prétraitement des données.
- **notebooks** : Ce dossier comprend les Jupyter notebooks utilisés pour l'analyse exploratoire des données et l'ensemble des modèles utilisés dans ce projet.
- **artefacts** : Ce dossier comprend l'ensemble des artefacts (modèles et hyperparamètres) sauvegardés de façon a pouvoir être réutilisé sans réentrainer les différents modèles.
- **requirements**: La liste des dépendances du projet.

## Auteurs

- [Samuel Baheux](https://github.com/SamuelBaheux)
- [Samuel Launay Pariente](https://github.com/samuel-LP)
- [Axel Fritz](https://github.com/AxelFritz1)
