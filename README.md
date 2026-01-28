# Classification de plantes médicinales (Machine Learning)

Projet de **classification multiclasses** en **supervised learning** visant à prédire des **catégories de symptômes médicinaux** de plantes à partir d’attributs numériques et catégoriels (ex. medicinal rating, edibility rating, weed potential, climatic tolerance).

## Objectif
- Transformer un dataset réel en un problème de classification exploitable
- Comparer deux modèles : **Régression logistique** (baseline) vs **KNN**
- Mettre en place un pipeline de préparation des données et une évaluation rigoureuse

## Données
Le dataset contient des caractéristiques structurées de plantes (numériques et catégorielles).  
Les labels de symptômes étant très granulaires, ils ont été **regroupés en classes plus larges** pour rendre l’apprentissage plus robuste.

## Méthodologie
- Exploration et nettoyage des données
- Gestion des valeurs manquantes
- Encodage des variables catégorielles
- Normalisation / mise à l’échelle des features
- Analyse du déséquilibre des classes
- Entraînement et comparaison des modèles : **Logistic Regression** et **KNN**
- Évaluation avec séparation **train/test** et **validation croisée** pour le choix des hyperparamètres

## Résultats (synthèse)
KNN obtient de meilleures performances que la régression logistique, ce qui suggère une structure **non linéaire** des données et l’importance de la similarité locale pour la classification des symptômes.

## Technologies
- Python
- pandas, NumPy
- scikit-learn

## Contenu du dépôt
  - notebook du projet
  - rapport PDF

## Lancer le notebook
1. Installer les dépendances
   ```bash
   pip install pandas numpy scikit-learn matplotlib
