# **Bank Customer Churn Model**

This project aims to predict customer churn in the banking sector using machine learning techniques. By analyzing customer data, the model identifies individuals likely to leave the bank, enabling better retention strategies.

---

## **Table of Contents**
- [Introduction](#introduction)  
- [Features](#features)  
- [Technologies Used](#technologies-used)  
- [Dataset](#dataset)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Learnings](#learnings)  

---

## **Introduction**
Customer churn is a critical issue for banks, directly impacting profitability and growth. The objective of this project is to build a machine learning model that predicts churn based on customer behavior and demographics, helping banks to proactively address churn risks.

---

## **Features**
1. **Data Preprocessing**:  
   - Categorical encoding for non-numerical data.  
   - Missing data handling and outlier detection.  
   - Feature scaling for uniformity in model inputs.  

2. **Imbalanced Dataset Handling**:  
   - Techniques like **SMOTE** were used to balance the dataset.  

3. **Model Development**:  
   - **Support Vector Machine (SVM)** classifier for predictions.  
   - Hyperparameter tuning using **Grid Search**.  

4. **Evaluation Metrics**:  
   - **Accuracy**, **Precision**, **Recall**, **F1-Score**, and **ROC-AUC**.  

---

## **Technologies Used**
- **Programming Language**: Python  
- **Tools**: Jupyter Notebook  
- **Libraries**:  
  - `Pandas` and `NumPy` for data preprocessing  
  - `Scikit-learn` for machine learning models  
  - `Matplotlib` and `Seaborn` for data visualization  

---

## **Dataset**
The dataset used in this project contains customer data such as:  
- Customer demographics (e.g., age, gender).  
- Account information (e.g., balance, tenure).  
- Transactional details and other behavioral patterns.  

(Note: Add dataset link or mention if it’s proprietary or synthetic.)  

---

## **Installation**
1. Clone the repository:  
   ```bash
   git clone https://github.com/bu21cseno500181/bank-customer-churn-model.git
   cd bank-customer-churn
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

3. Run the project using Jupyter Notebook or any Python IDE.  

---

## **Usage**
1. Open the notebook file:  
   ```bash
   jupyter notebook Bank_Customer_Churn.ipynb
   ```
2. Follow the cells to preprocess the data, train the model, and evaluate results.  
3. Adjust parameters for experimentation, if needed.  

---

## **Learnings**
- Practical understanding of machine learning workflows.  
- Data preprocessing techniques, especially handling imbalanced datasets.  
- Application of **SVM** and hyperparameter tuning using Grid Search.  
- The significance of precision and recall in churn analysis.  

---

## **Contributing**
Contributions are welcome! Feel free to fork the repository and submit pull requests.  

---

## **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details. 
