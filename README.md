# PROJECT-5_MACHINE_LEARNING
![foto](https://github.com/Lydia-Arocena/PROYECTO-5_MACHINE_LEARNING/blob/main/diamond.jpg)

# OBJETIVE:
With this project I am taking part in a Kaggle competition about predicting diamond prices.

This aims to predict diamond prices taking into account several features by using Machine Learning models.

# REPO STRUCTURE:
In order to develop this project, I have used the following files:
- **"Notebooks folder"**: This folder contains two different Jupyter Notebook files:
1. **"Feature_engineering_train"**: In this file I have extracted the main features from the provided raw data in order to improve the performance of machine learning models. Mainly, I have checked if there were highly correlated explanatory variables with each other and remove them and I have also transformed categorical data columns into numerical ones which are more esasily understable by Machine Learning models.


2. **"Train_&_Fit"**: In this one, I have trained several models with X_train,y_train(80% of my dataset called "Train") and made predictions with X_test (20% of the mentioned dataset) in order to chose the top 3 performance models. 

    Once selected, as my results will predictably improve if I use more data, I have trained them again with X,y (the whole mentioned dataset) and I have made predictions with it. 
    
    Then, I have made another final prediction with X_test(the other datasest called "Test") in order to make my first submission.

    In order to make my second submission, I have used GridSearchCV to select the best hyperparameters of the DecisionTreeRegressor model in order to retrain it with them and check if the RMSE has improved or not.

- **"Data foder"**:A directory that contains the original dataframes and the cleaned versions of them as well as my submissions.

- **Slice**: A summary of this project visually displayed.



# SOURCES:
- [Kaggle data set](https://www.kaggle.com/c/diamonds-datamad1021-rev/leaderboard)

- I have used the followingn libraries:
    - [Pandas](https://pandas.pydata.org/)
    - [Numpy](https://numpy.org/doc/)
    - [Sklearn](https://scikit-learn.org/)
    - [warnings](https://docs.python.org/3/library/warnings.html)
    

# CONCLUSIONS:
The best Machine Learning model to predict diamonds prices is the DecisionTreeRegressor.



