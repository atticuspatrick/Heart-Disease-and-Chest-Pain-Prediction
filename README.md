# Heart-Disease-and-Chest-Pain-Prediction

This is the final project for STAT 223 carried out by Owen Patrick, Cam Lunn, and myself. In this project, my group had a goal of predicting both chest pain type and heart disease within patients. We performed the following:
*Exploratory data analysis (EDA) on the data set to prune necessary features with the strongest prediction power
*Linear Discriminant Analysis (LDA) to predict both chest pain type and heart disease
*Quadratic Discriminant Analysis (QDA) to predict chest pain type and heart disease
*K-Nearest Neighbors to predict chest pain type and heart disease.
*Decision Trees to predict chest pain type and heart disease

Feel free to check out the full code in the RMD or the full report in the attached PDF! Here is a brief summary of our findings as the PDF and RMD are pretty lengthy documents:



Our goal was to use patient health data to predict whether someone has heart disease as well as what kind of chest pain they are likely to have. With cardiovascular illness related deaths so prevalent in the United States, it is vital that work is done to catch heart disease and chest pain in patients before it is too late. This project provides useful insight into what the most significant indicators of heart disease and chest pain are and simultaneously allows us to see what preventative measures can be taken to reduce risk of heart disease. We had success in meeting our research objectives, most notably in predicting heart disease status. Our best model was the decision tree which had an accuracy of about 88.45% in predicting heart disease status. This means that given data of a new patient in the same format as used in the model, we have around an 88.45% chance of correctly predicting whether or not they have heart disease. We did not have much success with predicting heart pain type and only achieved an accuracy of around 62% with our best model. KNN was marginally better than our decision tree with an accuracy of 62.31% versus 61.44%. Because this difference is so small and decision trees are more easily interpretable, we concluded that the decision tree is the best method for predicting chest pain type. Overall, the decision tree method proved to be the most accurate and interpretable out of all three methods we attempted using.

Data source: https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset
