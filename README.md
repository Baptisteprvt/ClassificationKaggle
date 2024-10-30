# Classification d'Images de Bateaux

Ce projet utilise l'apprentissage profond pour classifier des images de bateaux en différentes catégories. L'approche repose sur un modèle de réseau de neurones convolutifs (CNN) entraîné à partir de données d'image pour reconnaître et classifier des types de bateaux.

## Installation

Pour exécuter ce projet, vous devez installer les bibliothèques suivantes :

```bash
pip install tensorflow keras numpy pandas matplotlib seaborn
```

## Utilisation

1. **Préparation des données** : Assurez-vous que les données d'images sont correctement formatées et chargées. Le notebook utilise des ensembles d'images d'entraînement et de test dans des formats compatibles avec TensorFlow.
2. **Entraînement du modèle** : Le modèle CNN est entraîné pour classifier les images de bateaux. Les résultats d'entraînement incluent les courbes de précision et de perte.
3. **Évaluation du modèle** : Une évaluation des performances est fournie via un rapport de classification et une matrice de confusion.
4. **Prédictions** : Pour faire des prédictions sur un jeu de données de test, le modèle prédit les catégories des images et génère un fichier CSV avec les résultats.

### Exécution

L'entraînement et l'évaluation du modèle peuvent être réalisés en exécutant les cellules du notebook dans l'ordre. Une fois l'entraînement terminé, les résultats sont sauvegardés dans un fichier CSV pour soumission ou analyse.

## Structure du Notebook

- **Chargement et préparation des données** : Chargement des images et prétraitement pour l'entraînement.
- **Construction et entraînement du modèle** : Configuration d'un modèle CNN, compilation, et entraînement.
- **Évaluation des performances** : Calcul des scores de précision, rappel, F1-score et génération d'une matrice de confusion pour évaluer la performance.
- **Prédiction** : Prédiction des classes sur le jeu de test et génération d'un fichier CSV des résultats.

## Résultats

Le modèle a atteint une précision de test d'environ 90% avec des résultats détaillés dans le rapport de classification pour chaque classe.
