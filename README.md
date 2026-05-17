#  Diabetes Prediction Using Machine Learning

An end-to-end Machine Learning project developed to predict the likelihood of diabetes in patients based on diagnostic clinical measurements. This project showcases data cleaning, preprocessing, feature handling, and model training workflows.

---

## Project Overview & Goals
The main objective of this project is to build a predictive model that can assist healthcare professionals in identifying diabetes risks early. The pipeline handles real-world data inconsistencies (like invalid zero values) and delivers clean, structural data to a classification model.

## 🛠️ Tech Stack & Libraries
- **Language:** Python 3.12
- **Environment:** Google Colab
- **Libraries:** - `Pandas` & `NumPy` (Data Manipulation & Cleaning)
  - `Scikit-Learn` (Model Training & Evaluation)

## 🔄 Machine Learning Pipeline

### 1. Data Cleaning & Handling Inconsistencies
Real-world datasets often contain missing entries masked as zeros. In this dataset, variables like **Glucose, Blood Pressure, Skin Thickness, Insulin, and BMI** cannot biologically be zero. 
- Replaced invalid `0` values with `NaN`.
- Imputed missing values using the **Median** of each respective column to maintain data integrity without losing valuable rows.

### 2. Data Splitting
The processed dataset was split into an **80% Training set** and a **20% Testing set** using `train_test_split` to ensure robust validation and prevent overfitting.

### 3. Model Training & Performance
- **Algorithm Used:** Random Forest Classifier
- **Overall Model Accuracy:** **74.68%**

---

## 💻 How to Run the Project
1. Open the `.ipynb` notebook directly via Google Colab.
2. Upload the `diabetes.csv` dataset to the runtime environment.
3. Execute the cells sequentially from top to bottom.
