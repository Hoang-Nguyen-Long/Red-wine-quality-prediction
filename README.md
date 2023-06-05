# Red-wine-quality-prediction
#We are playing the role of a wine manufacturer searching for the greatest-tasting red wine. We want to apply machine learning models in the production process to ensure that every wine bottle has the highest quality. 
#Therefore, this analysis aims to predict wine quality given some essential attributes of wine. 
We have to deal with the Red Wine Quality Dataset, which consists of 1599 observations and 12 attributes (11 prediction attributes and 1 label of wine quality). Most importantly, the analysis aims to seek the answers to three main questions:
What are the attributes that potentially have strong effects on the wine quality? 
What is the flavor profile for “good” wine quality in terms of acids, flavors, and preservatives? 
With the predefined chemical elements of red wine products, what will be the corresponding quality levels? 

Methods and findings summary 
Exploratory Data Analysis was carried out to answer the first 2 questions. Regarding the answer to the first question, the main method was correlation analysis to anticipate the influences of 11 chemical components on wine quality based on Pearson’s correlation coefficients. Generally, the top 3 chemical components that influence red wine quality most significantly in descending order are Alcohol, Volatile Acid, and Sulphates. 
About the answer to the second question, we applied descriptive statistics findings to rule out the profile of high-quality wine. Practically, the wine manufacturer should not go overflow with chemicals that are positively correlated with good wine quality. Thus, the appropriate range for each chemical is provided. For instance, a good red wine should not have excessive volatile acids, residual sugar, and chlorides. Sulfates and other preservative attributes should be added within the health safe regulation. 
To answer the third question, we applied four different prediction models (1) Random Forest, (2) Logistics Regression, (3) Support Vector Machine, and (4) KNN. By comparing their accuracies, the best model was found as Random Forest Classifier with 90% accuracy. Thus, this could be applied in the actual manufacturing process in the hope to increase quality and reduce cost.

