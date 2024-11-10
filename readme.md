Prédiction de Maladies à partir de Documents Médicaux
Description
Ce projet utilise des techniques avancées de traitement du langage naturel (NLP) et de machine learning pour classifier automatiquement des résumés médicaux en fonction de la maladie décrite. En exploitant des modèles spécialisés en NLP biomédical, il vise à faciliter l'analyse de textes médicaux et à offrir un outil d'aide à la décision pour les professionnels de santé.

Objectifs
Classification de textes médicaux : Prédire la catégorie de maladie d'un résumé médical parmi cinq classes :
Maladies du système digestif
Maladies cardiovasculaires
Néoplasmes (cancers et tumeurs)
Maladies du système nerveux
Conditions pathologiques générales
Aide à la décision clinique : Fournir un modèle capable d'identifier rapidement les pathologies à partir de textes médicaux, contribuant ainsi à une prise de décision plus rapide et précise.
Dataset
Le dataset utilisé contient des résumés médicaux annotés, avec deux ensembles distincts :

Ensemble d'entraînement : 14 438 documents avec étiquettes de maladie.
Ensemble de test : 14 442 documents non étiquetés à classer.
Approche
Prétraitement des données : Les textes sont normalisés (suppression des caractères spéciaux, conversion en minuscules, suppression des mots courants).
Vectorisation : Transformation en vecteurs TF-IDF pour représenter les termes de manière numérique.
Modèles de classification :
Modèles de machine learning : Random Forest, KNN, et Arbre de décision.
Modèles avancés de NLP : BioBERT et BioDeBERTa, des modèles de transformateurs optimisés pour le domaine biomédical.
Résultats
Les modèles NLP spécialisés (BioBERT et BioDeBERTa) ont montré une précision supérieure, avec une performance de 67% pour BioDeBERTa, démontrant l'efficacité des modèles pré-entraînés biomédicaux pour cette tâche.