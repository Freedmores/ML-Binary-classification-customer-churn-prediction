# Customer Churn Prediction
<h3>From Data Preprocessing to Model Training</h3>

This repository contains a Churn Prediction Data Preprocessing exercise and a tutorial on training and evaluating multiple machine learning models for customer churn prediction. The notebook includes steps for data preprocessing, as well as training and evaluating Logistic Regression, XGBoost, and Random Forest models.


<h4>Overview</h4>
This project demonstrates how to preprocess data for customer churn prediction and train various machine learning models to predict churn. <br/>The notebook covers:
<ul>
<li>Data preprocessing, including handling missing values, encoding categorical variables, and scaling numerical features.</li>
<li>Training multiple machine learning models:
  <ol>
    <li>Logistic Regression</li>
    <li>XGBoost</li>
    <li>Random Forest</li>
  </ol>
  </li>
<li>Evaluating the performance of the trained models using accuracy, precision, recall, and F1-score.</li>
</ul>
<h4>Dataset</h4>
The dataset used for this project contains customer data with various features that help predict whether a customer is likely to churn. The target column indicates whether a customer churned or not.

Ensure you have the dataset available before running the notebook. You can either upload your own dataset or use a publicly available churn dataset.

<h4>Preprocessing Steps</h4>
The notebook covers:
<ol>
  <li><b>Handling Missing Data:</b> Different strategies such as filling with median/mode and dropping missing rows.</li>
  <li><b>Encoding Categorical Variables:</b> Converting categorical columns to numerical values using label encoding and one-hot encoding.</li>
  <li><b>Feature Scaling:</b> Standardizing numerical features so they contribute equally to the model.</li>
  <li><b>Splitting the Data:</b> Dividing the dataset into training and testing sets for model evaluation.</li>
</ol>
<h4>Models Trained</h4>
Three machine learning models are trained and evaluated for customer churn prediction:
<ul>
  <li><b>Logistic Regression:</b> A simple, interpretable linear model for classification.</li>
  <li><b>XGBoost:</b> A high-performance gradient boosting model widely used for structured data.</li>
  <li><b>Random Forest:</b> An ensemble learning method that creates multiple decision trees for better accuracy.</li>
</ul>
After training, the models are evaluated using metrics such as accuracy, precision, recall, and F1-score to assess their performance.

<h4>Technologies Used</h4>
 <li>Python</li>
 <li>Jupyter Notebook</li>
 <li>Pandas for data manipulation</li>
 <li>NumPy for numerical operations</li>
 <li>Scikit-learn for machine learning and data preprocessing</li>
 <li>XGBoost for gradient boosting models</li>
<h4>Usage</h4>
<li>Clone the repository:<br/>
&ensp; &ensp; git clone https://github.com/yourusername/churn-prediction-preprocessing.git</li>
<li>Navigate to the project directory and open the notebook in Jupyter.</li>
<li>Run the notebook cells sequentially to perform the data preprocessing, model training, and evaluation steps.</li>
