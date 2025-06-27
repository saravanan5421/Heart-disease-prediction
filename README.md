# Heart-disease-prediction
Project Report
Introduction
Heart disease is one of the leading causes of death globally, and early prediction can help save lives. In this project, I worked on a dataset related to heart health with the goal of building a model that can predict whether a person is at risk of heart disease based on their health indicators. The project also involved detailed data analysis and recommendations for healthcare providers.

Objective
This project focused on three main tasks:
Perform a complete data analysis on the provided dataset.
Build machine learning models to predict the presence of heart disease.
Offer useful suggestions for hospitals to help prevent heart-related issues.

Data Analysis (Task 1)
I began with data cleaning and preprocessing. I checked for missing values, handled outliers, and explored the shape of each feature's distribution. I noticed that some columns were right-skewed while others were left-skewed, which could affect model performance.

For categorical data, I used Label Encoding to convert it into numerical form so it could be used in machine learning models.

Exploratory Data Analysis (EDA) helped me understand the relationships between features, like age, blood pressure, cholesterol levels, and heart disease outcomes. Visualizations like histograms, box plots, and heatmaps made it easier to spot patterns.

Model Building and Implementation (Task 2)
I implemented several machine learning models to compare their performance:
Logistic Regression – A simple model, good for binary classification.
Linear Regression – Tried for comparison, but not suitable for classification.
Decision Tree Classifier – Captured non-linear relationships in the data.
Random Forest Classifier – Improved accuracy using an ensemble of trees.
Gradient Boosting Classifier – Performed well in terms of precision and recall.
XGBoost – Gave one of the best results in this project.
SVC (Support Vector Classifier) – Useful for creating decision boundaries.
I also applied SMOTE (Synthetic Minority Oversampling Technique) to balance the classes in the dataset, which helped in improving model performance.
To improve accuracy further, I used GridSearchCV to perform hyperparameter tuning across models like Random Forest and SVC.

Model Evaluation
Each model was evaluated using:
Accuracy
Precision
Recall
F1 Score
Confusion Matrix
Among all models, XGBoost, Random Forest, and Gradient Boosting gave the most reliable results.

Suggestions for Hospitals (Task 3)
Based on my findings, here are some key suggestions for hospitals and healthcare professionals:
Encourage routine heart checkups for early detection.
Focus on important health indicators like blood pressure, cholesterol, and chest pain.
Educate patients about risk factors and promote preventive care programs.
Use data-driven insights to identify high-risk individuals and offer them priority care.

Tools & Technologies Used
Python
Pandas, NumPy, Matplotlib, Seaborn
Scikit-learn
XGBoost
Jupyter Notebook

Conclusion
This project helped me understand the complete process of working with real-world data—from data cleaning to building and tuning machine learning models. It also showed how data science can play a crucial role in healthcare by providing meaningful predictions that can help save lives.
