# ANN_Porter_project
 ANN_Porter_project
 
Purpose: To help Porter in estimating the delivery time more precisely based on the various features (factors) using Artificial Neural Networks 

Experimentation and analysis:
•	It was assumed that ANN can capture complex non-linear interactions between multiple variables… With sufficient hyperparameter tuning, ANN can outperform linear and tree-based models.
•	But with various experiments done using ANN, it was observed that ANN was not very effective in capturing all possible non linear interactions. Despite of rigorous hyperparameter tuning and all, the highest R-squared achieved was 0.28
•	So polynomial features of degree 2 were introduced (squared features and interaction features)… Even the basic ANN model gave R-squared of 0.3. One of the Basic model (model # 19) achieved R-squared of 0.31
•	Despite of rigorous hyperparameter tuning the maximum R-squared remained at 0.31
•	We could see with hands on experience that ANNs cannot always ensure  that best results are achieved. “Feature Engineering” is still important.
•	It appears like, it is not possible to achieve better R-squared from this given dataset. With all the experiments, I conclude that the available features in the dataset do not have enough predictive power to achieve better “prediction model”.
•	Refer the summary table in the excel (01_ANN_Experiments_00). All the experiments (ipynb notebooks) are made available.

