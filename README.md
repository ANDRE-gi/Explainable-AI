# Projet Explainable AI

L'explicabilité est un enjeu clé en IA, notamment pour les applications critiques comme la finance, la santé et la vision par ordinateur.
Ce projet présente un ensemble d'expérimentations visant à explorer et expliquer le fonctionnement de différents modèles de Machine Learning à l'aide de techniques d'Explainable AI. L'objectif principal est d'apporter de la transparence aux prédictions faitess par les modèles et d'identifier les contributions des caractéristiques.


- **Shapley Values pour la prédiction immobilière**  
  Nous utilisons les valeurs de Shapley pour quantifier l'impact de chaque caractéristique (comme le nombre de pièces, le taux de criminalité, etc.) sur la prédiction du prix de l'immobilier à partir du dataset Boston Housing. Cette approche permet de décomposer et d'interpréter la contribution de chaque variable à la prédiction finale.

- **DICE pour le dataset UCI Credit Card Default**  
  Nous avons implémenté la méthode de DiCE(Diverse Counterfactual Explanations) appliquée au dataset UCI Credit Card Default. L'objectif est de déterminer comment les clients pourraient modifier certaines de leurs caractéristiques (âge, genre, niveau d'éducation, situation matrimoniale, relevés de factures, historique de paiement, limite de crédit, etc.) pour éviter un défaut de paiement sur leur carte de crédit.

- **Grad-CAM pour l'interprétation de modèles de classification d'images**  
  Ici, nous générons une visualisation Grad-CAM sur une image représentant un oiseau perché sur une branche. Cette technique met en lumière les zones de l'image qui influencent le plus la décision du modèle de classification, facilitant ainsi l'interprétation visuelle des prédictions.

- **Attribution des décisions dans les modèles BERT**  
  Ce module se concentre sur l'analyse des attributions dans un modèle BERT appliqué à la question-réponse. En étudiant les gradients des prédictions par rapport aux tokens d'entrée, nous identifions les éléments textuels les plus influents dans le processus de décision du modèle. Cette démarche offre une meilleure compréhension du fonctionnement interne de BERT pour des tâches complexes de compréhension du langage.
