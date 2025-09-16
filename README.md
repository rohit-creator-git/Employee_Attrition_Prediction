# 👨‍💼 Employee Attrition Prediction Notebook  

## 📌 Overview  
This project demonstrates how to use **Machine Learning & Data Visualization** techniques to predict **Employee Attrition (Yes/No)**.  
Employee attrition prediction helps organizations in:  
- Identifying employees likely to leave the company  
- Reducing recruitment & training costs  
- Taking proactive retention strategies based on data-driven insights  

The notebook walks through **data preprocessing, exploratory analysis, model building, and evaluation**.  

---  

## ⚙️ Tech Stack  
- **Languages & Tools**: Python, Jupyter Notebook  
- **Libraries**:  
  - Data Processing: Pandas, NumPy  
  - Visualization: Matplotlib, Seaborn  
  - Machine Learning: Scikit-learn (Logistic Regression, Random Forest)  
  - Model Saving: Joblib  

---  

## 📊 Workflow  
1. **Data Understanding & Cleaning**  
   - Handle missing values  
   - Encode categorical variables (OneHotEncoder)  
   - Feature scaling for numeric variables  

2. **Exploratory Data Analysis (EDA)**  
   - Attrition distribution  
   - Attrition by department, job role, overtime, income, etc.  
   - Correlation analysis  

3. **Model Training**  
   - Logistic Regression  
   - Random Forest Classifier  

4. **Model Evaluation**  
   - Compare models using Accuracy, Precision, Recall, F1-score, ROC-AUC  
   - Select best-performing model  

5. **Prediction Pipeline**  
   - Save best model (`attrition_model.pkl`)  
   - Single employee attrition prediction example  

---  

## 🚀 How to Run  
1. Clone the repo:  
   ```bash
   git clone <your-repo-link>
   cd Employee_Attrition_Prediction
   ```  

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  

3. Open Jupyter Notebook:  
   ```bash
   jupyter notebook Employee_Attrition_Prediction_NoXGB_Fixed.ipynb
   ```  

4. Load the dataset `HR_Employee_Attrition.csv` and run all cells.  

---  

## 📊 Results  
- Random Forest achieved the best performance with **~80% accuracy**.  
- Key attrition drivers identified:  
  - Overtime  
  - Job Satisfaction  
  - Distance From Home  

---  

## 🔮 Future Improvements  
- Add **Streamlit app** for interactive predictions.  
- Hyperparameter tuning for better accuracy.  
- Deploy as API / web app for HR managers.  
