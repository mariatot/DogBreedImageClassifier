# DogBreedImageClassifier
Développement d’un modèle de deep learning pour classer des images de chiens selon leur race. Ce projet utilise des CNN "maison" et des techniques de transfert d’apprentissage pour améliorer les performances de classification sur un dataset de 120 races.

## Description
Ce projet vise à développer un modèle capable de classer automatiquement des images de chiens selon leur race, en utilisant des techniques avancées de deep learning. Il a été conçu pour répondre aux besoins d'une association de protection des animaux afin d'automatiser la gestion de leur base de données d'images accumulées depuis plusieurs années.

## Contenu du projet
1. **Données utilisées** :  
   - **Stanford Dog Dataset** : 20 580 images représentant 120 races de chiens.  
   - Nettoyage et augmentation des données pour améliorer la qualité et la diversité des images d’entraînement.  

2. **Modélisation** :  
   - Développement d'un modèle CNN "maison" utilisant Keras.  
   - Application du transfert d’apprentissage avec des modèles pré-entraînés (ResNet50, VGG19, EfficientNetB3, Xception).  
   - Comparaison entre l’approche CNN "maison" et transfert d’apprentissage pour choisir le meilleur modèle final.  

3. **Résultats et modèle final** :  
   - Le modèle basé sur Xception avec fine-tuning partiel et data augmentation a obtenu les meilleures performances sur le dataset de validation.  

## Technologies utilisées
- **Python** : TensorFlow, Keras, OpenCV, NumPy, Matplotlib.  
- **Modèles pré-entraînés** : ResNet50, VGG19, EfficientNetB3, Xception.  

## Prochaines étapes
- Tester le modèle sur des images hors dataset pour évaluer la généralisation.  
- Explorer d'autres techniques de pré-processing (recadrage, résolution, etc.).  
- Améliorer la performance sur les races moins représentées.  
