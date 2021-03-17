# Robust-Yield-Prediction-on-various-Farm-Processing-Units
This Repository consists files of the ML Project - Robust Yield Prediction on Farm Units for a new food chain company , It is my Final academic project for the PG Program in Data Science &amp; Analytics @ Insofe.

Robust Yield Prediction Development Plan.

1) Introduction: Agriculture is considered to be the primary culture practiced all around the globe. The science or practice of farming, including cultivation of the soil for the growing of crops and the rearing of animals to provide food, wool, and other products.
• Predicting the yield of the crop is a vital agricultural problem. Crop yield is primarily dependent on weather conditions, field management and the planning of harvest operation. Accurate information about the history of crop yield is a vital criterion for making decisions related to agricultural risk management. Selection of crop and prediction of the yield- To aggrandize the yield of a crop, the identification, and selection of the ideal crop play an important role. It is also dependent on other factors like temperature, humidity, luminescence, and external pressure that surround that crop.
• Agriculture, Supply Chain Management (SCM) implies managing the relationships between the businesses responsible for the efficient production and supply of products from the farm level to the consumers to meet consumers requirements reliably in terms of quantity, quality and price. In Agriculture, Machine Learning techniques are used in crop management processes, following with farming conditions (Weather). In farming, they are used to predict yield and quality of crops as well as livestock production.
The proposed method uses RandomForestRegression and Gradient Boosting techniques to predict the yield of various ingredients. These techniques have plenty of applications. Some of them are discussed below:



2) Problem Statement: A new fast-food chain is seeing rapid expansion over the past couple of years. They are now trying to optimize their supply chain to ensure that there are no shortages of ingredients. For this, they’ve tasked the data science team to come up with a model that could predict the output of each food processing farm over the next few years. These predictions could further increase the efficiency of their current supply chain management systems.
 
 Objectives: 
a) Explore the data and engineer new features.
b) Predict the yield for each farm during the given timestamps.
c) Given the forecasted demand for the next few months for a particular ingredient, device a strategy to source it, creating a strategy to source ‘ing_w’ ingredient type.


3) Methodology: Includes the process for carrying out the research and procedure for     doing things, which Includes
• Approach
• Algorithm Engineering
• Tools Used


Approach:
(I) The First stage is understanding the data. There are 5 curated datasets provided in this competition. The datasets consist of Crop Information mainly around different types of ingredients, Farm Data and Field Management Information and also consists information of the weather data provided by timestamp for each location where the farms are present. 
• In this stage, research questions are identified, Exploratory Data Analysis was performed, and eventually all the Insights and Observations are validated to see if the approach is feasible. In addition to this, the initial search also included grouping the variables, plotting relations in the weather data, measures of various weather fields were also defined. 

(II) The Second stage was the Data Preparation. When preparing the data, the data was initially cleaned and merged which means that their information regarding farming companies, type of ingredients, timestamp, weather data and more information regarding the problem were stored. After all the necessary data was extracted correctly, the data was synthesized in order to provide it to an ML model. 

(III) In the Final stage, Ensemble techniques Random Forest Regression and also Boosting Algorithms were used to make the yield predictions.


RANDOM FOREST REGRESSION:
• A Random Forest is a meta estimator that fits a number of classifying decision trees on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting. 
• Because we are attempting to predict a value, we will look at Regression methods. Because of   the medium size of our data, we will begin RandomForestRegressors, and then move towards ensemble methods like boosted trees such as GradientBoostingRegressor. Initially worked on a baseline our first submission will simply use all the data and no hyperparameter tuning.
• Hyperparameter tuned the model by using Random search where random combinations of the hyperparameters are used to find the best solution for the built model to yield better results comparatively. 



Tools and Technology Stack:
•	Jupyter notebooks
•	Python 



4)Results and Discussions:
• For the trained Random Forest Regressor, the training set accuracy and test set accuracy were 95.62% and 87.23% respectively. 
• The evaluation metric used for this project is the Root Mean Squared Error (RMSE) - Square root of the average of squared residuals (prediction errors).
•Test Data RMSE_score:  344.1695875856751

Predictions CSV Files: https://drive.google.com/drive/folders/1V4ybQyVEEdbQQhEXv2-MxT7iBKTY7gB4?usp=sharing



5) Conclusion: 
•The project has successfully demonstrated the use of Random Forest Regression Networks and Boosting techniques in the development of Robust Yield Prediction model on a dataset consisting of various parameters related to the obtaining of expected yield. The results were very realistic in nature.
• Artificial Intelligent techniques and methodologies are currently being used extensively in the agricultural sector as a single purpose to aggregate the accuracy and to identify solutions to the problems. As practical usage of Artificial Intelligent (AI) based on various application in a plethora of fields, shows that machine learning scheme is open to change and can be implemented on an agricultural field.



