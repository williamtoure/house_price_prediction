# 🏡 House Price Prediction

## 📌 Description
Ce projet vise à prédire le prix des maisons en utilisant des techniques de **machine learning** avec **Python** et **Jupyter Notebook**.  
L’objectif est de construire un modèle performant en exploitant un jeu de données immobilières et en appliquant un pipeline complet : exploration, préparation des données, modélisation et évaluation.

## 🎯 Objectifs
- Nettoyer et explorer les données.  
- Réaliser une **analyse exploratoire** (EDA).  
- Prétraiter les données (valeurs manquantes, encodage, normalisation).  
- Entraîner et comparer différents modèles (régression linéaire, Random Forest, XGBoost, etc.).  
- Évaluer la performance à l’aide de métriques comme **RMSE**, **MAE** et **R²**.  
- Sélectionner un modèle final et interpréter les résultats.  

## 📂 Structure du projet
```
├── data/                 
│   ├── raw/              # Données brutes (CSV Kaggle)
│   ├── processed/        # Données nettoyées
├── notebooks/            
│   ├── 01_EDA.ipynb      # Analyse exploratoire
│   ├── 02_Preprocessing.ipynb
│   ├── 03_Modeling.ipynb
│   ├── 04_Evaluation.ipynb
├── src/                  
│   ├── data_preprocessing.py
│   ├── model_training.py
│   ├── utils.py
├── requirements.txt      
├── README.md             
```

## 🛠️ Prérequis
- **Python 3.9+**
- **Jupyter Notebook / JupyterLab**

### 📦 Bibliothèques principales
Installer avec :
```bash
pip install -r requirements.txt
```

- `numpy`, `pandas` → manipulation des données  
- `matplotlib`, `seaborn` → visualisation  
- `scikit-learn` → machine learning  
- `xgboost` ou `lightgbm` → modèles avancés  

## 🚀 Utilisation
1. Cloner le dépôt :
   ```bash
   git clone https://github.com/username/house-price-prediction.git
   cd house-price-prediction
   ```
2. Créer un environnement virtuel et installer les dépendances :
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows
   pip install -r requirements.txt
   ```
3. Lancer Jupyter Notebook :
   ```bash
   jupyter notebook
   ```
4. Explorer les notebooks dans le dossier `notebooks/`.

## 📊 Jeu de données
Le dataset utilisé est : [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).  
📥 Téléchargez-le et placez-le dans `data/raw/`.

## 📈 Résultats attendus
- Mise en évidence des variables influentes.  
- Comparaison des performances de plusieurs modèles.  
- Définition d’un modèle final performant.  

## 📝 Améliorations possibles
- Création d’un pipeline automatisé avec `scikit-learn`.  
- Optimisation des hyperparamètres (`GridSearchCV`, `Optuna`).  
- Déploiement (API Flask/FastAPI ou Streamlit).  
