# Site-Energy-Intensity-Prediction

![image](https://user-images.githubusercontent.com/68380016/222897205-bd498c5f-6fbd-45cb-a29c-aa21eda673c3.png)



**Description:** According to a <a href="https://www.iea.org/reports/tracking-buildings-2021" target="_blank">report</a> issued by the International Energy Agency (IEA), the lifecycle of buildings from construction to demolition was responsible for 37% of global energy-related and process-related CO2 emissions in 2020. Yet it is possible to drastically reduce the energy consumption of buildings by a combination of easy-to-implement fixes and state-of-the-art strategies. 

The dataset consists of building characteristics, weather data for the location of the building, as well as the energy usage for the building, and the given year, measured as Site Energy Usage Intensity (Site EUI). Each row in the data corresponds to a single building observed in a given year.

source of dataset & data dictionary -  <a href="https://www.kaggle.com/c/widsdatathon2022/data" target="_blank">Click Here</a>    

**Problem Statement:** You are provided with two datasets: (1) the train\_dataset where the observed values of the Site EUI for each row are provided and (2) the x\_test dataset the observed values of the Site EUI for each row are removed and provided separately in y\_test. Your task is to predict the Site EUI for each row (using the complete training dataset), given the characteristics of the building and the weather data for the location of the building. Use the test sets for validation and testing. 

The target variable is **site\_eui** and the evaluation metric is **RMSE** score.

**Steps Involved:** The project involves several steps such as data cleaning, exploratory data analysis, feature engineering, and model building. In the data cleaning step, missing values are imputed and irrelevant columns are dropped. In the exploratory data analysis step, the distribution of the target variable and the relationship between the features and the target variable are explored using visualizations. In the feature engineering step, new features are created from the existing features to improve the performance of the models.

**Modelling and Tuning:** Several machine learning models such as Catboost, Random forest classifier, and XGBoost classifier are trained on the dataset using techniques such as knn imutation. Hyperparameter tuning using 5 fold cross validation CatBoost is performed.
