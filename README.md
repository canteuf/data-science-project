# Projet d'Analyse Prédictive du Churn Client - Dataset Telco Customer Churn

## 📊 Description du Projet

Ce projet constitue une analyse complète et approfondie du dataset **Telco Customer Churn**, un ensemble de données classique en science des données pour la prédiction de l'attrition client. L'objectif principal est de développer un modèle prédictif capable d'identifier les clients susceptibles de résilier leur abonnement auprès d'un opérateur télécom, permettant ainsi des actions préventives ciblées.

## 🎯 Objectifs

- **Analyser** les patterns et facteurs influençant le churn client
- **Développer** des modèles prédictifs performants utilisant des approches stochastiques
- **Comparer** différentes techniques de machine learning
- **Fournir** des insights actionnables pour la rétention client

## 📁 Structure du Projet

```bash
Projet-Data-Science/
│
├── notebook.ipynb                 # Notebook principal d'analyse
├── Datasets/
│   └── Telco-Customer-Churn.csv   # Dataset source
├── images/                        # Graphiques et visualisations générés
├── models/                        # Modèles sauvegardés
├── README.md                      # Documentation du projet
└── .gitignore                     # Fichiers à ignorer par Git
```

## 🛠️ Technologies Utilisées

- **Langage** : Python 3.x
- **Bibliothèques principales** :
  - `pandas`, `numpy` : Manipulation des données
  - `matplotlib`, `seaborn` : Visualisation
  - `scikit-learn` : Machine Learning
  - `xgboost`, `lightgbm` : Algorithmes avancés
  - `imbalanced-learn` : Gestion du déséquilibre
- **Outils** : Jupyter Notebook, Git

## 📋 Prérequis

- Python 3.8+
- Jupyter Notebook
- Git

## 🚀 Installation et Configuration

### 1. Cloner le repository

```bash
git clone <url-du-repository>
```

### 2. Créer un environnement virtuel

```bash
python -m venv env
source env/bin/activate  # Sur Windows : env\Scripts\activate
```

### 3. Installer les dépendances

```bash
pip install -r requirements.txt
```

### 4. Lancer Jupyter Notebook

```bash
jupyter notebook
```

## 📖 Utilisation

1. **Ouvrir** le notebook `notebook.ipynb`
2. **Exécuter** les cellules dans l'ordre pour reproduire l'analyse complète
3. **Explorer** les visualisations générées dans le dossier `images/`
4. **Utiliser** les modèles sauvegardés dans le dossier `models/`

## 📊 Méthodologie

### 1. Analyse Exploratoire des Données (EDA)

- Inspection des données et qualité
- Analyse univariée et bivariée
- Détection d'outliers et valeurs manquantes

### 2. Feature Engineering

- Encodage des variables catégorielles
- Normalisation des variables numériques
- Création de features dérivées
- Gestion du déséquilibre des classes

### 3. Modélisation Stochastique

- Évaluation de 11 algorithmes différents
- Optimisation des hyperparamètres avec RandomizedSearchCV
- Comparaison des performances (AUC, précision, rappel)

### 4. Évaluation et Sélection

- Métriques adaptées au problème de classification déséquilibré
- Sélection du modèle optimal
- Sauvegarde et documentation

## 📈 Résultats Clés

- **Modèle optimal** : AdaBoost
- **Performance** : AUC $\simeq$ 0.8261(estimation)
- **Facteurs de risque identifiés** :
  - Contrats à court terme
  - Absence de services additionnels
  - Clients récents

## 🤝 Contribution

Les contributions sont les bienvenues ! Pour contribuer :

1. Fork le projet
2. Créer une branche feature (`git checkout -b feature/AmazingFeature`)
3. Commit vos changements (`git commit -m 'Add some AmazingFeature'`)
4. Push vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrir une Pull Request

## 👥 Auteurs

-

## 🙏 Remerciements

- IBM pour le dataset Telco Customer Churn
- La communauté open source pour les bibliothèques utilisées
