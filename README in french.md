# La détection des faux billets

## 1. Contexte
Client : Organisation Nationale pour le Contrôle des Faux Billets (ONCFM).  
La détection des faux billets est un problème crucial pour les institutions financières. Ce projet propose une solution automatisée basée sur le machine learning pour identifier les billets authentiques et faux à partir de leurs caractéristiques numériques.

## 2. Approaches
- **Données :** Dimensions et caractéristiques des billets, incluant des échantillons de vrais et faux billets.
- Les variables incluent :  
  - **Variance** : Mesure de la dispersion.
  - **Skewness** : Asymétrie des données.
  - **Curtosis** : Caractéristique des distributions.
  - **Entropy** : Mesure spécifique des billets.

## 3. Méthodologies
- **Analyse exploratoire des données :**
  - Visualisation des distributions et relations entre variables (corrélations, graphiques).
- **Prétraitement des données :**
  - Nettoyage des données et gestion des valeurs manquantes (par régression linéaire).
- **Modèles utilisés :**
  - Régression logistique.
  - Clustering K-means.
- **Évaluation des performances :**
  - Utilisation d'une matrice de confusion, précision et rappel pour comparer les modèles.

## 4. Outils Utilisés

- Python (Pandas, Scikit-learn)
- Microsoft power bi pour les visualisations(Matplotlib/Seaborn).
- Outils de visualisation : Graphiques pour explorer les relations entre variables.(cercle de corrélation, matrice de confusion, méthode du coude).

## 5. Résultats
- La régression logistique a obtenu une précision de **95 %**.
- Le clustering K-means a montré une précision légèrement inférieure de **90 %**.

## 6. comment utiliser
1. Clonez ce dépôt :
   ```bash
   https://github.com/jinjin-gong/Fake-banknote-detection-en-Python
