# The Challenge
The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, we have to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

Folder Structure:

Data dictionary.png: This image gives a overview about features we are dealing with, it is included in EDA_DataTransformation.ipynb notebook.

1. Dataset Information
1.1 Titanic Train.csv: This dataset is used for model training and evaluation.
1.2 Titanic Test.csv: This is a validation dataset, used for final predictions.
1.3 training_dataafterEDA.csv: This dataset is constructed after initial exploaratory data analysis and includes minor modifications.
1.4 test_data_afterEDA.csv: This dataset is constructed after initial exploaratory data analysis on validation dataset and includes minor modifications.

1.5 training_data_algorithm.csv: This is the final training dataset which is constructed after performing Data Cleaning, outlier detection, handling missing values and Data transformation. This is then used for algorithm training.
1.6 test_data_algorithm.csv: This is the final validation dataset which is constructed after performing Data Cleaning, outlier detection, handling missing values and Data transformation. Final predictions are made on this dataset.

1.7 ValidationPredictions.csv: Final pedictions are stored as csv.

2. Notebook Information
2.1 EDA_DataTransformation.ipynb: This notebook comprises of Exploratory Data Analsis, Outlier Detection and Outlier elminiation strategey, Handling missing values, and Data transformation.
2.2 Algorithm_Implementation.ipynb: This notebook comprises of algorithm implementation namely Logistic Regression, Random Forest, and KNN. Also, models have been compared to check how they are performing on unknown data using evaluation metrics.

3. Model Information:
3.1 logistic_model.sav: Logistic Regression model. 
3.2 randomforest_model.sav: Random Forest model. 
3.1 knn_model.sav: KNN model. 
