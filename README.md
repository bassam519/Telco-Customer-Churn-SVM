# Telco Customer Churn Prediction using SVM

This project predicts **customer churn** (whether a customer leaves or stays) using the **Telco Customer Churn dataset**.  
We applied **Support Vector Machine (SVM)** along with preprocessing, visualization, and hyperparameter tuning.

---

## 📊 Project Workflow
1. **Data Exploration**  
   - Checked missing values, duplicates, and data types.  
   - Summarized numerical and categorical features.  

2. **Data Visualization**  
   - Countplot of churn (class balance).  
   - Histograms for `tenure`, `MonthlyCharges`, and `TotalCharges`.  
   - Boxplots of numerical features vs churn.  
   - Barplots for churn by contract type and payment method.  

3. **Data Preprocessing**  
   - Encoded categorical variables.  
   - Scaled numerical features (`tenure`, `MonthlyCharges`, `TotalCharges`).  
   - Split dataset into training and testing sets.  

4. **Modeling with SVM**  
   - Tuned hyperparameters (`C`, `gamma`, `kernel`) using `GridSearchCV`.  
   - Trained the best model on training data.  
   - Evaluated on test data.  

---

## 📈 Results
- **Accuracy:** 78.99%  
- **ROC AUC Score:** 0.7875  

These results show the SVM model is reasonably good at predicting churn but can be improved with advanced feature engineering or model ensembles.  

---

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 🚀 How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/Telco-Customer-Churn-SVM.git
   cd Telco-Customer-Churn-SVM
