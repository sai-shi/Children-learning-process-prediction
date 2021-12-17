# Machine Learning Course Project #
## Description ##
In this project, I implemented machine learning models for a Kaggle competition. The objective is to evaluate and predict children’s behaviors on the game app, PBS KIDS Measure Up! given history game dataset. The results could be helpful for better-designed games and improved learning outcomes. The solutions may aid in discovering important relationships between engagement with high-quality educational media and learning processes.

Specifically, I used the gameplay data to forecast how many attempts a child will take to pass a given assessment (an incorrect answer will be counted as an attempt). In the training dataset, the full history game data is provided, including numerical, categorical and text data. Given a specific installation id, which represents an individual, our model should be able to predict how many attempts is needed to pass the game.

## My Work ##
Exploratory Data Analysis, Data Preprocessing, Feature Extraction, and Model Implementation

## Result ##

KNN, MLP and RBF SVM shows the best accuracy and other classifiers did not work well. The reason might be the dataset is highly non-linear. Since the number of features is only five, KNN works pretty well in this problem.

![accuracy](https://github.com/sai-shi/Children-learning-process-prediction/blob/main/accuracy.png)
