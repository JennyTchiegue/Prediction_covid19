# 📊 Projet de Classification avec Scikit-Learn

## 📝 Description
Ce projet consiste en une analyse et une classification de données en utilisant plusieurs modèles d'apprentissage automatique. L'objectif est d'explorer les données, d'appliquer différentes techniques de prétraitement, et d'évaluer plusieurs modèles de classification afin d'optimiser la performance.

## 🚀 Fonctionnalités
- Exploration des données pour définir un objectif mesurable.
- Prétraitement des données : séparation Train/Test, encodage des variables.
- Implémentation et comparaison de plusieurs modèles de classification :
  - Random Forest
  - AdaBoost
  - SVM
  - KNN
- Utilisation de pipelines (`scikit-learn.pipeline`) pour automatiser le prétraitement et l'entraînement.
- Normalisation des données pour améliorer la performance de SVM et KNN.
- Évaluation des performances avec la courbe précision-rappel.
- Visualisation et interprétation des résultats pour optimiser le choix du modèle.

## 🛠️ Installation
### 📌 Prérequis
Avant de commencer, assure-toi d'avoir les éléments suivants installés :
- Python 3.x
- Jupyter Notebook 
- Bibliothèques nécessaires (voir ci-dessous)

### 📥 Clonage du projet
```sh
git clone https://github.com/JennyTchiegue/Prédiction_covid19.git
cd   Prédiction_covid19.git
```

### 📦 Installation des dépendances
Installe les bibliothèques requises avec :
```sh
pip install -r 
```
numpy
pandas
matplotlib
seaborn
scikit-learn
```

## 📊 Utilisation
Lance le projet avec :
```sh
python main.py
```
Ou ouvre le Notebook Jupyter :
```sh
jupyter notebook
```

## 📈 Modèles et Performance
1. **Prétraitement :**
   - Séparation des données en Train/Test.
   - Encodage des variables catégoriques.
   - Normalisation appliquée à SVM et KNN.

2. **Modèles évalués :**
   - Random Forest
   - AdaBoost
   - SVM
   - KNN

3. **Évaluation :**
   - Comparaison des modèles avec la courbe précision-rappel.
   - Optimisation du choix du modèle en fonction des métriques.

## 🏗️ Architecture du projet
```
├── data/              # Dossier contenant les datasets
├── notebooks/         # Jupyter Notebooks pour l'expérimentation
├── src/              # Code source du projet
│   ├── preprocess.py  # Prétraitement des données
│   ├── train.py       # Entraînement des modèles
│   ├── evaluate.py    # Évaluation des modèles
├── README.md          # Documentation principale
├── requirements.txt   # Liste des dépendances
```

## ✅ Tests
Exécuter les tests unitaires :
```sh
pytest tests/
```

## 🤝 Contribution
1. Forker le projet
2. Créer une branche (`git checkout -b feature-nouvelle-fonctionnalité`)
3. Committer (`git commit -m "Ajout d'une nouvelle fonctionnalité"`)
4. Pousser (`git push origin feature-nouvelle-fonctionnalité`)
5. Ouvrir une Pull Request

 

## 📩 Contact
Si tu as des questions, n'hésite pas à me contacter sur [linkedin](https://linkedin.com/in/jenny-tchiegue-907803257) ou à ouvrir une issue sur GitHub ! 🚀
