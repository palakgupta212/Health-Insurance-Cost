# 🏥 Health Insurance Cost Prediction Model

## 📌 Overview
This project predicts **health insurance costs** based on demographic and lifestyle factors using **Machine Learning**.  
The dataset includes age, BMI, smoking status, and other variables that influence insurance charges.  

---

## 📊 Dataset
- **Source**: [Kaggle – Medical Cost Personal Dataset](https://www.kaggle.com/mirichoi0218/insurance)  
- **Features**:
  - `age` – Age of the individual  
  - `sex` – Gender  
  - `bmi` – Body Mass Index  
  - `children` – Number of dependents  
  - `smoker` – Smoking status (yes/no)  
  - `region` – Residential area (northeast, northwest, southeast, southwest)  
  - `charges` – Medical insurance cost (target variable)  

---

## ⚙️ Workflow
1. **Data Preprocessing**
   - Encode categorical features
   - Handle missing values and outliers
   - Feature scaling if required

2. **Exploratory Data Analysis (EDA)**
   - Distribution of charges
   - Correlation heatmaps
   - Impact of smoking, BMI, and age

3. **Model Building**
   - Algorithms used:
     - Linear Regression
     - Random Forest Regressor
     - Gradient Boosting (XGBoost)
   - Evaluation Metrics:
     - R² Score
     - Mean Absolute Error (MAE)
     - Root Mean Squared Error (RMSE)

4. **(Optional) Deployment**
   - A simple Flask/Streamlit app for predictions

---

## 📈 Results
- Linear Regression provided a baseline.  
- Random Forest and XGBoost improved prediction accuracy.  
- **Key Factors:** Smoking status, BMI, and age strongly influenced insurance costs.  

---

## 🛠️ Tech Stack
- **Language**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost  
- (Optional) Streamlit/Flask for deployment  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/health-insurance-cost-model.git
   cd health-insurance-cost-model
