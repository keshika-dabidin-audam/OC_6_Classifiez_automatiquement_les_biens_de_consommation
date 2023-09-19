# Projet 6 Openclassrooms : Classifiez automatiquement des biens de consommation
#### Librairies Data Science, Analyse Exploratoire des données, Clustering, NLP, CNN Transfer Learning
## Outils et compétences

- Représenter graphiquement des données à grandes dimensions (T-SNE, ACP)
- Utiliser des techniques d’augmentation des données
- Prétraiter des données texte pour obtenir un jeu de données exploitable (TF-IDF, Word2vec, BERT, USE)
- Prétraiter des données image pour obtenir un jeu de données exploitable (Data generator, SIFT, VGG-16)
- Mettre en œuvre des techniques de réduction de dimension (ACP)
- Définir la stratégie de collecte de données en recensant les API disponibles
- Définir la stratégie d’élaboration d’un modèle d'apprentissage profond
- Évaluer la performance des modèles d’apprentissage profond selon différents critères

## Description générale du projet 

### (a) Présentation du contexte d'étude
Vous êtes Data Scientist au sein de l’entreprise "Place de marché”, qui souhaite lancer une marketplace e-commerce.
Pour rendre l’expérience utilisateur des vendeurs (faciliter la mise en ligne de nouveaux articles) et des acheteurs (faciliter la recherche de produits) la plus fluide possible, et dans l'optique d'un passage à l'échelle, il devient nécessaire d'automatiser cette tâche.

On vous demande donc d'étudier la faisabilité d'un moteur de classification des articles en différentes catégories, avec un niveau de précision suffisant. Dans le cas de la faisabilité de la classification, il est demandé de réaliser une classification supervisée à partir des images en mettant en place une data augmentation afin d’optimiser le modèle.

De plus, l'entreprise souhaite élargir la gamme de produits, en particulier dans l’épicerie fine. Il est demandé de fournir une extraction des 10 premiers produits dans un fichier “.csv”

### (b) Présentation des données
- Le jeu de données des articles est téléchargeable sur le lien suivant : https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/Parcours_data_scientist/Projet+-+Textimage+DAS+V2/Dataset+projet+pre%CC%81traitement+textes+images.zip
- L'API des données concernant l'épicerie est disponible sur le lien suivant : https://rapidapi.com/edamam/api/edamam-food-and-grocery-database

## Livrables
- Des notebooks contenant les fonctions permettant le prétraitement et la feature extraction des données textes et images ainsi que les résultats de l’étude de faisabilité (graphiques, mesure de similarité) :
  - Dabidin_Keshika_1_notebook_pretraitement_feature_extraction_faisabilite_texte_072023.ipynb
  - Dabidin_Keshika_2_notebook_pretraitement_feature_extraction_faisabilite_images_072023.ipynb
  - Dabidin_Keshika_4_notebook_obtention_du_dossier_classifie_train_test_data_pour_dataset_tensorflow_072023.ipynb
 - Un notebook de classification supervisée des images : Dabidin_Keshika_3_notebook_CNN_Transfer_Learning_Stage_classification_supervisee_072023.ipynb
- Un script Python de test de l’API et le fichier au format “csv” contenant les produits extraits :
  - Dabidin_Keshika_5_notebook_API_Food_Query_072023.ipynb
  - Dabidin_Keshika_6_fichier_api_champagne_072023.csv
- Un support de présentation : Dabidin_Keshika_7_presentation.pptx.pdf
