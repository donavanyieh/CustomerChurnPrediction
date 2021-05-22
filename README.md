# Predict customer churn with unbalanced target class dataset
#### View the full notebook with outputs here:<br>https://www.kaggle.com/yiehyuheng/customer-churn-prediction-on-unbalanced-dataset
<b>Tech Stack</b><br>
Python (Pandas, NumPy, Matplotlib, Seaborn), sklearn (preprocessing, PCA, pipeline), SMOTE, PyCaret (LightGBM)
<br><br>
<b>Dateset</b><br>
https://www.kaggle.com/mnassrib/telecom-churn-datasets
<br><br>
<b>Brief overview of approach</b>
<ol>
  <li>EDA/ data cleaning to understand distribution of numeric and categorical data, and to identify and remove attributes with high multicollinearity</li>
  <li>Standardize numeric data and performed label/ one-hot encoding to relevant categorical fields</li>
  <li>Reduce dimensionality with PCA (95% explained variance)</li>
  <li>SMOTE to mitigate class imbalance</li>
  <li>PyCaret to compare and select best model (LightGBM)</li>
  <li>PyCaret for model tuning and evaluation on unseen data</li>
</ol>
