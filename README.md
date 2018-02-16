# Schizo_predict
L'objectif de ce notebook est de présenter une approche tentant de prédire la schizophrénie à partir de relevés d' EEG issus de patients schizophrènes et non schizophrènes.

Le notebook cherche à entraîner plusieurs modèles (régression logisitique, arbre de décision, réseaux de neuronnes linéaires ...)  sur les variables brutes (couplées avec une sélection de variables type ANOVA, et ACP) et de nouvelles variables créées à partir de l'expertise médicale.

Ce notebook reprend le contexte général de l'étude médicale et contient l'implémentation en python des différents modèles ainsi que leur évaluation.
