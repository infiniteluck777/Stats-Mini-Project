(https://github.com/user-attachments/files/32497662/README.md )#Stats-Mini-Project
'Heart-Disease-Prediction'
Heart Disease Prediction using Machine Learning

## Student Details
- **Name:** Atharva Ajit Pathak
- **Roll No:** 50
- **Class/Division:** TYBSC "IT"

## Project Overview
This project predicts whether a patient has heart disease based on clinical and diagnostic attributes such as age, cholesterol level, blood pressure, chest pain type, and more. It is a **binary classification** problem solved using supervised machine learning techniques.

## Dataset
- **Source:** UCI Machine Learning Repository — [Heart Disease Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease)
- **Records:** 303 patients
- **Features:** 13 clinical attributes
- **Target:** Presence (1) or absence (0) of heart disease

| Column | Description |
|---|---|
| age | Age in years |
| sex | 1 = male, 0 = female |
| cp | Chest pain type (0–3) |
| trestbps | Resting blood pressure (mm Hg) |
| chol | Serum cholesterol (mg/dl) |
| fbs | Fasting blood sugar > 120 mg/dl (1 = true) |
| restecg | Resting ECG results (0–2) |
| thalach | Maximum heart rate achieved |
| exang | Exercise-induced angina (1 = yes) |
| oldpeak | ST depression induced by exercise |
| slope | Slope of the peak exercise ST segment |
| ca | Number of major vessels colored by fluoroscopy (0–3) |
| thal | 3 = normal, 6 = fixed defect, 7 = reversible defect |
| target | 0 = no heart disease, 1 = heart disease present |

## Tech Stack
- **Language:** Python
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, ucimlrepo

## Project Workflow
1. **Data Loading** – Fetch the dataset using the official `ucimlrepo` package.
2. **Data Cleaning** – Handle missing values, remove duplicates, and convert the target into binary form.
3. **Exploratory Data Analysis (EDA)** – Visualize target distribution, correlations, and age-wise trends.
4. **Preprocessing** – Train-test split and feature scaling using `StandardScaler`.
5. **Model Training** – Train and compare three models:
   - Logistic Regression
   - Random Forest Classifier
   - K-Nearest Neighbors (KNN)
6. **Evaluation** – Compare models using accuracy, classification report, and confusion matrix.
7. **Feature Importance** – Identify the most influential features using the Random Forest model.

## Results
The notebook compares model accuracy and highlights the best-performing model along with a confusion matrix and feature importance chart. (Update this section with your actual output values after running the notebook.)

## How to Run
1. Open `Heart_Disease_Prediction.ipynb` in Jupyter Notebook or Google Colab.
2. Install the required package if needed:
   ```
   pip install ucimlrepo
   ```
3. Run all cells sequentially from top to bottom.

## Future Improvements
- Hyperparameter tuning using GridSearchCV
- Trying additional models such as SVM or XGBoost
- Applying k-fold cross-validation for more robust evaluation
- Handling class imbalance if present

## Author
**Atharva Ajit Pathak**
Roll No: 50 | TYBSC "IT"
