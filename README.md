##
Ce projet implémente un modèle de neurone artificiel pour la classification binaire en utilisant un ensemble de données synthétiques.

## 1. Dataset
Le jeu de données est généré à l'aide de la fonction make_blobs de scikit-learn. Il contient 100 échantillons avec 2 caractéristiques, répartis en 2 centres.

## 2. Fonctions du modèle
### Initialisation
La fonction initialisation initialise les paramètres du modèle (poids et biais) avec des valeurs aléatoires.

### Modèle
La fonction model calcule la sortie du modèle en appliquant la fonction sigmoïde à la combinaison linéaire des caractéristiques et des poids.

### Fonction de perte
La fonction log_loss calcule la perte logistique du modèle.

### Calcul des gradients
La fonction gradients calcule les gradients de la fonction de perte par rapport aux paramètres du modèle.

### Mise à jour des paramètres
La fonction update met à jour les paramètres du modèle en utilisant la descente de gradient.

### Prédiction
La fonction predict prédit les étiquettes en fonction des probabilités de sortie du modèle.

### Entraînement du modèle
La fonction artificial_neuron entraîne le modèle en utilisant l'algorithme de descente de gradient.

## 3. Frontière de décision
Une visualisation de la frontière de décision est tracée en utilisant les poids et le biais appris par le modèle.

## 4. Visualisations 3D
Des visualisations 3D sont créées à l'aide de la bibliothèque Plotly pour montrer la distribution des données et la surface de décision du modèle.

### Exécution du code
Exécutez le script 'model_neurone_artificiel.ipynb' pour lancer le modèle.
