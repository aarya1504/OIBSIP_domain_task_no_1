# OIBSIP_domain_task_no_1
##Problem Statement :
The Iris flower dataset is a classic and simple multivariate dataset often used for classification problems in machine learning. The challenge is to build a predictive model that can accurately classify an Iris flower into one of the three species — Setosa, Versicolor, or Virginica — based solely on its physical dimensions: sepal length, sepal width, petal length, and petal width.

##Objective :
The primary goal of this project is to build a machine learning model that can classify Iris flowers into three species Iris Setosa, Iris Versicolor, and Iris Virginica based on four key features: sepal length, sepal width, petal length, and petal width. This is a fundamental classification problem in supervised learning and serves as an ideal introduction to machine learning.

##Steps Performed :
1. Data Loading
Loaded the Iris dataset using sklearn.datasets and converted it into a DataFrame for easier manipulation.

2. Exploratory Data Analysis (EDA)
Analyzed the structure and distribution of data using descriptive statistics and visualizations such as:

Histograms
Pairplots
Correlation heatmaps
Box plots
3. Data Preprocessing
Checked for missing values
Encoded the target labels using LabelEncoder
Split the data into training and testing sets
4. Model Training
Trained multiple classification models:

Logistic Regression
Decision Tree Classifier
Support Vector Machine (SVM)
Random Forest Classifier
GuassianNB
Xgboost
5. Model Evaluation
Evaluated each model using:

Accuracy Score
Confusion Matrix
Classification Report
6. Visualization
Visualized classification results, confusion matrix, and decision boundaries (if applicable).

Tools and Libraries Used :
Programming Language: Python
Jupyter Notebook
Libraries:
pandas, numpy – data manipulation
matplotlib, seaborn – data visualization
sklearn – machine learning (model training, evaluation, preprocessing)

##Dataset Description :
Source: Kaggle

Features:
Sepal Length (cm)
Sepal Width (cm)
Petal Length (cm)
Petal Width (cm)
Target Classes:
Iris Setosa
Iris Versicolor
Iris Virginica Total Samples: 150
##Outcomes :
Successfully built a machine learning model to classify Iris flowers with over 95% accuracy.
Random Forest Classifier showed the best performance with balanced precision and recall.
Gained hands-on experience in the complete machine learning workflow: data preprocessing, training, tuning, and evaluating.
The project also enhanced skills in Python, data visualization, and model interpretability.
##Conclusion :
This project solidified understanding of classification problems using machine learning. The Iris dataset proved to be an excellent starting point, offering clean and well-structured data. By comparing multiple models, we learned the importance of evaluation metrics and model selection based on business needs or performance criteria.
