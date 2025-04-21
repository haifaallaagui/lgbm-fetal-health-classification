# 🤖 Classification de la Santé Fœtale

Ce projet de machine learning vise à classifier l'état de santé fœtale en utilisant des données issues de monitoring cardiotocographique. Plusieurs modèles supervisés sont testés et optimisés pour une meilleure précision, notamment **Random Forest** et **SVM**, avec une évaluation basée sur le **F1-score**.

---

## 📊 Objectif

Développer un système de classification automatique pour évaluer l’état de santé du fœtus en trois classes :
- 🟢 **Normal**
- 🟡 **Suspect**
- 🔴 **Pathologique**

---

## 🛠️ Technologies utilisées

- Langage : **Python 3**
- Librairies : `pandas`, `scikit-learn`, `matplotlib`, `seaborn`
- Modèles : `RandomForestClassifier`, `SVC`
- Évaluation : `F1-score`, `matrice de confusion`, `classification_report`

---

## 📁 Dataset

Le dataset utilisé provient d’un fichier de monitoring fœtal contenant plusieurs attributs biomédicaux :
- **BPM** (battement cardiaque)
- **Accélérations / Décélérations**
- **Variabilité à court et long terme**
- **Nombre de contractions, mouvements fœtaux, etc.**

La variable cible (`target`) correspond à l'état de santé classé en 3 catégories.

---

## 📌 Étapes du projet

1. **Prétraitement des données**
   - Nettoyage des valeurs manquantes
   - Standardisation / Normalisation
2. **Exploration & visualisation**
   - Analyse de la distribution des classes
   - Corrélation entre les attributs
3. **Modélisation**
   - Entraînement de plusieurs modèles (Random Forest, SVM)
   - **Tuning des hyperparamètres** avec `GridSearchCV`
4. **Évaluation**
   - F1-score (macro, micro, weighted)
   - Matrice de confusion
   - Courbes ROC (si applicable)



