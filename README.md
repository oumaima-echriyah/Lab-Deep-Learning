
# MNIST Classification with CNN,and Vision Transformer

## Contexte
Ce projet a pour objectif d'explorer différentes architectures de réseaux de neurones pour des tâches de vision par ordinateur. Nous avons travaillé sur la classification d'images du dataset **MNIST** en utilisant plusieurs approches : **CNN**, modèles pré-entraînés (**VGG16**, **AlexNet**), et **Vision Transformer (ViT)** implémenté à partir de zéro.  

L'objectif final est de comparer les performances de ces modèles en termes de précision, F1 score, perte, et temps d'entraînement.

---

## Dataset
Le projet utilise le dataset [MNIST](https://www.kaggle.com/datasets/hojjatk/mnist-dataset), un ensemble de données d'images représentant des chiffres manuscrits. Chaque image est en niveaux de gris, de taille 28x28 pixels, et associée à une étiquette indiquant le chiffre correspondant (de 0 à 9).

---

## Conclusion
Comparé aux modèles **CNN** et **VGG16**, le **Vision Transformer (ViT)** implémenté à partir de zéro affiche la **précision la plus faible**. Cela s'explique par la complexité du modèle ViT, qui nécessite plus de données et d'entraînement pour atteindre des performances optimales, tandis que les modèles CNN et VGG16, souvent pré-entraînés sur des jeux de données plus vastes, bénéficient d'une meilleure généralisation sur des tâches comme celle de la classification d'images.

---

