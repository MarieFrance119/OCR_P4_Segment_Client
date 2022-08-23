# OCR_P4_Segment_Client
L'objectif du projet est de comprendre les différents types d’utilisateurs (clients de Olist) grâce à leur comportement et à leurs données personnelles.

3 notebooks ont été réalisés :
- un notebook d'analyse exploratoire 
- un notebook avec des essais des différentes approches de modélisation 
- un notebook de simulation pour déterminer la fréquence nécessaire de mise à jour du modèle de segmentation, afin que celui-ci reste pertinent 

L'approche a cherché à éviter le modèle classique de RFM (recency, frequency, monetary). 

4 clusters ont été trouvés avec un K-Means, la « Elbow method » a été utilisée pour aider au choix du nombre de clusters. 
3 modèles de KMeans ont été comparés :
- un avec 5 variables
- un avec 5 variables et PCA
- un avec 3 variables.
