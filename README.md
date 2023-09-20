# machine_learning_project-supervised-learning

## Project Goals
-   The goals of this project was to use supervised learning techniques to build a machine learning model that can predict whether a patient has diabetes or not, based on certain diagnostic measurements.The project involves three main parts: exploratory data analysis, preprocessing and feature engineering, training multiple machine learning models, and then comparing the models to choose the best one based on our objective, which is to minimize BOTH the false positives and false negatives.
### Process
-   First, the dataset was imported and data cleaning and EDA was performed on the dataset, which included checking for null and missing values, checking for outliers, visual charts/graphs to gain initial insight into the data, etc.

-   Then, preprocessing and feature engineering was performed on the resulting cleaned data to get it ready for the machine learning models. This included handling the missisng values and outlier values, splitting the dataset up into training and testing sets, scaling the predictor values, etc.

-   Lastly, the processed data was then used to train three different classification models (logitistic regresion, decision tree, and random forest), these models were then evaluated on the testing dataset with their evaluation metrics. Since the objective is to minimize BOTH the false positives and false negatives, the F1-Score was focused on and used to evaluate the models.

### Results

-	From the resulting performance metrics for each model, the best model to use for our objective, which is to minimize BOTH the false positives and false negatives, would be the Decision Tree model, since it has the best F1-Score out of the three models (which means that this model would be the best one for our objective). This means that the Decision Tree model would be the best one to use to minimize both the false positives and false negatives in the predictions. And with a F1-Score of ~0.7, the model is considered to be pretty accurate model.

- Some more findings from the project include:
    - The average age of the people in the data set was ~33 years old
    - The average glucose level for people with diabetes is ~141, the average BMI for people with diabeties is ~35
    - The average glucose level for people without diabetes is ~110, the average BMI for people without diabeties is ~30 (we can see that the glucose and BMI level is on average noticibily higher in people with diabetes than people without)
    - The only notible correlations between the predictors are the correlations between pregnancies and age, skin thickness and BMI, and skin thickness and insulin
    - From the ML model metrics, it was found that the best classification model for this dataset (out of the 3 used) is the Decision Tree Model, as it has the best F1-Score out of the 3 models with a score of ~0.7.
