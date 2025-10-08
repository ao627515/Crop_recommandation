# machine-learning

## Description

Ce projet propose un modèle de classification pour recommander le type de culture agricole optimal en fonction des caractéristiques du sol et des conditions climatiques. Il utilise un jeu de données (`Crop_recommendation.csv`) contenant des mesures telles que la teneur en azote (N), phosphore (P), potassium (K), la température, l'humidité, le pH et les précipitations, ainsi que le label de la culture recommandée.

Le projet inclut des notebooks Jupyter pour l'exploration des données et le développement du modèle de machine learning, ainsi qu'un script Python principal.

## Structure du projet

- `Crop_recommendation.csv` : Jeu de données principal.
- `projet_ML.ipynb` et `project.ipynb` : Notebooks Jupyter pour l'analyse exploratoire et la modélisation.
- `main.py` : Script Python principal (exemple de démarrage).
- `pyproject.toml` : Fichier de configuration du projet et des dépendances.
- `.gitignore`, `.python-version`, `README.md`, `uv.lock` : Fichiers de gestion de projet.

## Installation

### Prérequis

- Python 3.13 ou supérieur ([.python-version](c:/Projects/Crop_recommandation/.python-version))
- pip

### Installation des dépendances

Dans le dossier du projet, exécute :

```sh
pip install -r requirements.txt
```

Ou, si tu utilises `pyproject.toml` avec `pip` :

```sh
pip install .
```

Les principales dépendances sont :

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- ipykernel

### Lancement du projet

#### 1. Exploration et modélisation

Ouvre le notebook [projet_ML.ipynb](c:/Projects/Crop_recommandation/projet_ML.ipynb) dans Jupyter ou VS Code pour explorer les données et exécuter le modèle.

#### 2. Script principal

Pour exécuter le script principal :

```sh
python main.py
```

## Utilisation

Le projet charge le jeu de données, effectue une analyse exploratoire, traite les valeurs manquantes et dupliquées, puis entraîne un modèle de classification pour prédire la culture recommandée selon les paramètres du sol et du climat.

## Exemple de données

Chaque ligne du fichier [Crop_recommendation.csv](c:/Projects/Crop_recommandation/Crop_recommendation.csv) contient :

```
N,P,K,temperature,humidity,ph,rainfall,label
90,42,43,20.88,82.00,6.50,202.93,rice
...
```

## Auteur

Projet réalisé dans le cadre d'une initiation au machine learning appliqué à l'agriculture.

---

N'hésite pas à adapter ce README selon tes besoins spécifiques ou à ajouter des instructions pour l'entraînement et l'évaluation du modèle
