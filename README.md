# 🚢 Prédiction de Survie des Passagers du Titanic

**Réalisé par :** Hanin Hedhli, Hadir Dridi, Ella Soussi, Jihen Souissi  
**Superviseur :** Olfa Chebbi  
**Outils :** Python, Jupyter Notebook, Scikit-learn, Pandas, Matplotlib, Seaborn  

---

## 🔍 À propos du projet

Ce projet applique des algorithmes de **machine learning** pour prédire la survie des passagers du Titanic en fonction de caractéristiques telles que : âge, sexe, classe, famille à bord, tarif, et port d’embarquement.  

**Objectifs :**  
- Comparer plusieurs modèles de classification (Arbre de Décision, SVM, KNN)  
- Évaluer leurs performances sur le dataset Titanic  
- Extraire des insights pour améliorer les prédictions  

---

## 📊 Modèles & Résultats

| Modèle                   | Précision Globale |
|---------------------------|-----------------|
| Arbre de Décision         | 78 %            |
| SVM                       | ~78 %           |
| KNN                       | 72.63 %         |

**Insights principaux :**  
- Arbre de Décision et SVM offrent de meilleures performances que KNN  
- Prétraitement des données (gestion des valeurs manquantes, encodage) essentiel pour la qualité des prédictions  
- Visualisation via matrices de confusion permet d’identifier les erreurs de classification  

---

## 📸 Captures d’écran

Aperçu des analyses et des matrices de confusion :  

<img width="545" height="643" alt="image" src="https://github.com/user-attachments/assets/313959dc-b71b-45ef-adb8-b2a4dcc4d7ee" />

<img width="503" height="656" alt="image" src="https://github.com/user-attachments/assets/67f00207-bbce-49a5-9dda-47fdbc0d5abb" />

<img width="503" height="656" alt="image" src="https://github.com/user-attachments/assets/9e224cdf-79ac-4a3b-83c9-7a11948b176f" />



---

## 🚀 Étapes clés

1. Prétraitement des données : traitement des valeurs manquantes et encodage des variables catégoriques  
2. Division du dataset : 80 % entraînement, 20 % test  
3. Entraînement des modèles : Arbre de Décision, SVM, KNN  
4. Évaluation : précision, rappel, matrices de confusion  
5. Comparaison des performances et recommandations pour améliorer les prédictions  

---

## 📖 Références

- [Dataset Titanic - Kaggle](https://www.kaggle.com/c/titanic)  
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)  
- [Pandas Documentation](https://pandas.pydata.org/)  

---

