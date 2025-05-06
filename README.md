# Graduate Admission Prediction using Machine Learning 🎓

This project classifies students' graduate admission chances using logistic regression, data preprocessing, and clustering analysis on the popular Graduate Admissions dataset.

## 📄 Data Set Used
The data set used in this project is admission.csv file

## 📋 Project Structure
Data Analysis (EDA): Examining and visualizing the overall structure of the data set.

## Data Preprocessing
* Checking for missing data
* Finding outliers
* Converted "Chance of Admit"  to binary class using threshold,
* Feature scaling via StandardScaler

## Modeling
* Logistic Regression
* Gradient Descent Classification
 Model evaluated with:
* Accuracy
* Confusion Matrix

## Clustering
Applied KMeans clustering on `GRE Score`, `CGPA`, and `TOEFL Score`
* 3 clusters created to observe academic profile segmentation
* Scatter plot visualization

## 🔍 Key Results
* Best accuracy : 0.97
* Threshold Used: 0.78 for classification

## 🔧 Technologies Used
* Python
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Scikit-learn
* Scipy
  
