# Heart-disease-ml
Machine learning test on heart disease dataset.
This project applies several machine learning algorithms to predict the presence of heart disease using a structured medical dataset. The objective is to compare different models and select the one that best identifies patients with potential heart disease.

## Project Overview
Heart disease is one of the leading causes of death worldwide. Early detection is essential for prevention and treatment. In this project, several machine learning models were trained and evaluated to classify whether a patient has heart disease based on clinical features.

The workflow includes:

- Introduction
- Dataset
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Models training
- Results
- Conclusion

Dataset

The dataset contains several clinical attributes related to heart health, such as:

- Age
- Sex
- Chest pain type
- Resting blood pressure
- Cholesterol
- Maximum heart rate
- Exercise-induced angina
- ST depression
- Other cardiovascular indicators

Machine Learning Models Used

The following models were implemented and compared:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Decision Tree
- Random Forest
- Gradient Boosting
- Support Vector Machine (SVM)

Feature scaling was applied to models that require it (such as KNN, Logistic Regression, and SVM).

## Results
The best performing models were Random Forest and Gradient Boosting, both achieving an accuracy of 0.864.
However, Random Forest was selected as the preferred model because it produced fewer false negatives in the confusion matrix. Value very important in clinical prediction models.
In a medical context, false negatives are particularly critical because they represent patients who actually have heart disease but are incorrectly classified as healthy.
Therefore, reducing false negatives is important to avoid missing potentially sick patients.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
