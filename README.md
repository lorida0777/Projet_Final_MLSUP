## 🌦️ Prédiction de la Pluie en Australie avec des Algorithmes de Classification

### 📌 Objectif du projet

Ce projet a pour but de **prédire s’il pleuvra demain** (`RainTomorrow`) à partir de données météorologiques historiques fournies par le **Bureau of Meteorology d'Australie**. Il met en œuvre plusieurs **algorithmes de classification** appris dans le cadre du cours de Machine Learning supervisé.

---

### 🧠 Algorithmes utilisés

* Régression linéaire
* K-Nearest Neighbors (KNN)
* Arbres de décision
* Régression logistique
* Support Vector Machine (SVM)

---

### 📊 Métriques d'évaluation

Pour évaluer les performances des modèles, plusieurs métriques sont utilisées :

* Accuracy
* Indice de Jaccard
* F1-Score
* Log Loss
* Erreur Absolue Moyenne (MAE)
* Erreur Quadratique Moyenne (MSE)
* Coefficient de détermination (R²)

---

### 🗂️ Données utilisées

Les données proviennent de sources publiques :

* Bureau of Meteorology : [http://www.bom.gov.au/climate/dwo/](http://www.bom.gov.au/climate/dwo/)
* Jeu de données enrichi via Rattle : [weatherAUS.RData](https://bitbucket.org/kayontoga/rattle/src/master/data/weatherAUS.RData)

Variables notables :

* `RainToday` : s’il a plu aujourd’hui
* `RainTomorrow` : variable cible

---

### 🔍 Étapes principales

1. **Importation et exploration des données**
2. **Nettoyage et prétraitement**
3. **Transformation des variables catégorielles**
4. **Séparation des données en jeu d'entraînement/test**
5. **Entraînement des modèles**
6. **Évaluation et comparaison des performances**

---

### 📁 Organisation du projet

```
📦 Projet_Final_MLSUP
 ┣ 📄 Projet_Final_MLSUP_1.ipynb
 ┣ 📄 README.md
 ┗ 📂 data
     ┗ 📄 Weather_Data.csv 
 ┗ 📂 Rapport
     ┗ 📄 Rapport_ML_Sup.pdf
     ┗ 📄 Rapport_ML_Sup.tex
```

---

### 🚀 Comment exécuter le projet

1. Cloner le dépôt :

```bash
git clone https://github.com/lorida0777/Projet_Final_MLSUP.git
cd Projet_Final_MLSUP
```

2. Ouvrir le notebook avec Jupyter :

```bash
jupyter notebook Projet_Final_MLSUP_1.ipynb
```

---

### 👨‍💻 Auteur

Projet réalisé dans le cadre du cours de Machine Learning Supervisé (MLSUP).



