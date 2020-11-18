# mussle_classification

Problem statement and the approach 


In this analysis, I will be using binary class classification algorithms to predict the existence of mussels based on some given conditions. The input features are location (northing and easting), secchi observation, water column depth, pressure, pH, specific conductivity, temperature, turbidity, and the substrate type (hard/soft). The classification algorithms predict the existence of a colonization of mussels as ‘YES’ where number of mussels per m2 is greater than 20 and ‘NO’ for places where the number of mussels per m2 is less than 20. The algorithms used in this problem are K- Nearest Neighbour (KNN), Decision Tree, Support Vector Machine (SVM), and Logistic Regression. The accuracy of each model will be calculated using Jaccard index, F1-score, and LogLoss. The best prediction method can then be evaluated using the best accuracy. The rank order parameters extracted from SVM (with a linear solver) gives an idea to understand the feature importance on the existence of mussels. 
