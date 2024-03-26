# Lung Cancer Prediction Model
## Project Overview
This project aims to leverage AI-driven predictive models to forecast the risk of lung cancer using risk factors and symptoms. It addresses the crucial need for early diagnosis of lung cancer, which significantly enhances treatment options and prognosis.

## Data Source
The dataset, obtained from Kaggle, includes data from 309 participants, featuring 16 variables related to risk factors, symptoms, and lung cancer status. Variables include age, gender, smoking habits, yellow fingers, anxiety, chronic diseases, fatigue, and more. The data underwent thorough preparation, including duplication removal and normalization, to ensure quality input for model training.

## Exploratory Data Analysis (EDA)
Our EDA focused on uncovering correlations between various factors and lung cancer incidence, employing statistical tests such as t-tests and chi-square tests. The analysis highlighted significant relationships, for instance, between smoking, yellow fingers, chronic diseases, allergies, and lung cancer.

## Model Training and Testing
We split the data into training (80%) and testing (20%) sets. A logistic regression model was applied, achieving a train accuracy score of 0.92 and a test accuracy score of 0.91, with impressive precision and recall metrics. The model's ability to predict lung cancer risk based on provided factors was promising, as indicated by the confusion matrix results.

## Challenges
The project faced challenges related to the relatively small sample size and the lack of detailed data on cancer stages, family history, second-hand smoke exposure, and occupational exposures.

## Next Steps
Future work will explore additional models such as Random Forest Classification, Naive Bayes, and Gradient Boosting Classifier to compare their performance with the logistic regression model. This iterative approach aims to refine the predictive capabilities of our models further.

## Conclusion
The "Lung Cancer Prediction Model" project demonstrates the potential of machine learning algorithms in enhancing lung cancer diagnosis processes. By providing a cost-effective tool for early risk assessment, we hope to contribute to better patient outcomes and the ongoing fight against cancer.
