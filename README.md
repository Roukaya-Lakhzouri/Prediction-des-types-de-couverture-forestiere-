# 🌲 Prédiction des types de couverture forestière 

Ce projet a pour objectif de prédire les types de couverture forestière à partir de données environnementales (sol, climat, topographie) à l’aide de techniques de classification multiclasse. Il est réalisé dans le cadre du module Big Data.

---

## 📁 Contenu du projet

Le projet est divisé en trois parties exécutables dans Google Colab :

### 1. [`Random_Forest_Decision_Tree_Gradient_Boosting.ipynb`](lien_vers_fichier_1)

- 📌 **Prétraitement des données**
- 📈 Modélisation avec :
  - SVM
  - Decision Tree
  - Random Forest
  - Gradient Boosting
- 🧪 **Évaluation multiclasse** : matrice de confusion, précision, rappel, F1-score

### 2. [`Random_Forest_Decision_Tree_PySpark.ipynb`](lien_vers_fichier_2)

- 🧠 **Implémentation Big Data** des mêmes modèles (Decision Tree & Random Forest)
- ⚙️ Utilisation de **PySpark MLlib** pour le traitement et la classification
- 💻 Objectif : travailler sur des environnements de données distribuées

### 3. [`Random_Forest_Déploiement.ipynb`](lien_vers_fichier_3)

- 🚀 **Déploiement du modèle final** via une interface simple avec **Gradio**
- 🧑‍💻 Permet à l’utilisateur de saisir des variables environnementales et d’obtenir la prédiction du type de forêt en temps réel

---

## 🔧 Technologies utilisées

- **Python**
- **Scikit-learn**
- **PySpark**
- **Gradio**
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**

---

## 🎯 Objectifs pédagogiques

- Comparer des modèles de classification supervisée sur un problème multiclasse
- Appliquer le traitement Big Data avec Spark pour des flux de données volumineux
- Déployer un modèle de machine learning dans une interface interactive accessible

---

## 🧠 Ce que vous apprendrez

- Prétraitement de données environnementales
- Comparaison des performances de modèles classiques et Big Data
- Évaluation de modèles multiclasse
- Déploiement d’une application ML avec Gradio


