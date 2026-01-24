# DeepLearning Internship

Ce projet a été réalisé dans le cadre de mon stage de 2ᵉ année de licence informatique, au LICIIS (Laboratoire d'Informatique en Calcul Intensif et Image pour la Simulation) à Reims.  
L'objectif principal était de concevoir, entraîner et optimiser un modèle de réseau de neurones convolutif (CNN) capable de reconnaître les différentes plantes et, si présentes, leurs maladies à partir d’images issues du dataset PlantVillage.

## Stack technique :
- Language : Python 3.13
- Framework : PyTorch
- Bibliothèques : Torchvision, NumPy, Matplotlib
- Dataset : Kaggle

## Tâches réalisés :
- Prétraiter et explorer les données du dataset PlantVillage.
- Concevoir plusieurs architectures CNN plus ou moins profondes.
- Implémenter des techniques de data augmentation pour améliorer la robustesse du modèle.
- Atteindre une précision supérieure à 99% sur les données de validation/test.
- Étudier les performances de chaque version (simple CNN, deep CNN, avec ou sans batch normalization…).

## Ressources :

- Auto-formation avec des ressources (cours en ligne, articles, documentations PyTorch).
- Rendez-vous régulier par mon tuteur de stage pour valider mes choix techniques.
- Nombreux essais/erreurs sur l’architecture, le prétraitement et le sur-apprentissage.
- Utilisation de Google Colab et PyCharm pour l'entraînement des modèles et la visualisation des résultats

## Quelques liens vers mes travaux : 

- Notebooks d'expérimentation et d'entraînement :  
   [Notebooks](https://drive.google.com/drive/folders/1va3uwjT-qCHGCeu_LIWKai9FHW19VCx7)

- Modèles entraînés (.pth) :  
  [Télécharger les modèles](https://drive.google.com/drive/folders/1qdRDtb93IjDKse_SsNtGvHmpAEywdt0C?usp=sharing)  
  (Ces fichiers sont également présents dans ce dépôt, via git LFS)

## Résultats

- Précision finale sur validation : >99%
- Plusieurs variantes testées (nombres de couches, batch norm, régularisation, etc.)
- Visualisation des performances avec courbes d’apprentissage et matrices de confusion
