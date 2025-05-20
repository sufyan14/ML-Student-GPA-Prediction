# 📊 Student Performance Prediction using K-Nearest Neighbors (KNN)

This project uses the **K-Nearest Neighbors (KNN)** algorithm to predict student academic performance based on behavioral and demographic data. The model is built using **Python** and **scikit-learn**, and includes data preprocessing, training, evaluation, and visualization.

## 📁 Dataset Features

The dataset includes the following columns:

- `StudentID` (excluded from training)
- `Age`
- `Gender`
- `Ethnicity`
- `ParentalEducation`
- `StudyTimeWeekly`
- `Absences`
- `Tutoring`
- `ParentalSupport`
- `Extracurricular`
- `Sports`
- `Music`
- `Volunteering`
- `GPA`
- `GradeClass`

Depending on the use case, either **GPA (regression)** or **GradeClass (classification)** is used as the target variable.

---

## 🧠 Objective
 
- ✅ **Regression:** Predict students' **GPA** as a continuous score.

---

## 🛠️ Tech Stack

- Python 3.x  
- pandas, numpy  
- scikit-learn  
- matplotlib, seaborn  

---

## ⚙️ How It Works

1. **Data Preprocessing**  
   - Drop irrelevant fields (e.g., `StudentID`)  
   - Encode categorical variables (e.g., `Gender`, `ParentalEducation`, etc.)  
   - Split data into training and test sets  
   - Scale features using `StandardScaler`  

2. **Model Training**  
   - Apply K-Nearest Neighbors with `n_neighbors=24`  
   - Train on scaled features using `KNeighborsClassifier` or `KNeighborsRegressor`  

3. **Evaluation**  
   - For regression: Mean Squared Error (MSE), R² score, and actual vs predicted plot  

---

## 📈 Output

### Actual vs Predicted GPA (Regression)

![{24C90279-5F9A-47BE-B489-F7128F607EB7}](https://github.com/user-attachments/assets/407de609-01b0-4ee8-a670-e5302de8c6bb)
