# Heart Disease Classification
### Overview
This Jupyter notebook tackles the task of heart disease classification using popular machine learning models. We'll walk through data prep, model building, and evaluating key classifiers – RandomForest, KNN, and Logistic Regression. To enhance performance, we'll fine-tune these models with RandomizedSearchCV and GridSearchCV. Plus, we'll uncover crucial features in our dataset.

### Steps:
1) Problem Definition:
Predict the likelihood of heart disease using machine learning models based on essential health indicators

2) Data:
Collect the data from various sources as this is a personal project we could use a open source dataset for heart disease. (https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset).

3) Evaluation:
Achieving an accuracy rate exceeding 95% is a crucial milestone, warranting further refinement and enhancement of the model.

4) Features:
The following features serve as the basis for discerning the presence or absence of heart disease in our patients.
* age
* sex
* chest pain type (4 values)
* resting blood pressure
* serum cholestoral in mg/dl
* fasting blood sugar > 120 mg/dl
* resting electrocardiographic results (values 0,1,2)
* maximum heart rate achieved
* exercise induced angina
* oldpeak = ST depression induced by exercise relative to rest
* the slope of the peak exercise ST segment
* number of major vessels (0-3) colored by flourosopy
* thal: 0 = normal; 1 = fixed defect; 2 = reversable defect

5) Feature Importance:
* Identify and analyze important features in the dataset.
* Visualize the importance of features using appropriate plots.
