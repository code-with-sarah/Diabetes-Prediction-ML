# Diabetes Prediction using Machine Learning

A professional data science project that predicts the likelihood of diabetes in patients based on clinical diagnostic measurements. This model is built using Python and the Scikit-Learn library.

## 📊 Dataset Overview
The dataset originates from the National Institute of Diabetes and Digestive and Kidney Diseases. It contains data from female patients of Pima Indian heritage.
* **Target Label:** `Outcome` (0 = Non-Diabetic, 1 = Diabetic)
* **Features:** Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age.

## 🛠️ Data Preprocessing & Refactoring
* **Invalid Zero Handling:** Columns like Glucose, BloodPressure, SkinThickness, Insulin, and BMI contained invalid `0` values, which were treated as missing data and replaced with `NaN`.
* **Missing Data Imputation:** Missing values were successfully imputed using the **Median** of each respective column to maintain data integrity.
* **Code Cleanliness:** Variable names and documentation follow strict professional industry standards (Refactored from Roman Urdu to English).

## 🤖 Model & Performance
* **Algorithm Used:** Random Forest Classifier
* **Data Split:** 80% Training, 20% Testing
* **Evaluation Metric:** Accuracy Score
* **Test Accuracy:** **74.68%**

## 📂 Project Structure
* `Diabetes_Prediction_ML_Project.ipynb` - Core Google Colab Notebook containing full pipeline.
* `diabetes.csv` - Sourced dataset file.
---

## 💻 How to Run the Project
1. Open the `.ipynb` notebook directly via Google Colab.
2. Upload the `diabetes.csv` dataset to the runtime environment.
3. Execute the cells sequentially from top to bottom.
