# **Credit Risk Analysis**  

## **Overview**  
This repository contains a **credit risk analysis** pipeline using **machine learning models** to predict loan default likelihood. The dataset consists of borrower information, loan details, and credit history. The project includes **data preprocessing, exploratory data analysis (EDA), model training, evaluation, and visualization**.  

## **Project Features**  
### **1. Data Cleaning & Preprocessing**  
- Handles missing values and outliers  
- Encodes categorical features  
- Splits data into training and testing sets  

### **2. Exploratory Data Analysis (EDA)**  
- Summary statistics and outlier detection  
- Scatter matrix and box plots to identify trends  
- Parallel category diagrams to analyze categorical feature relationships  

### **3. Machine Learning Models**  
The project implements multiple classification models to predict loan default likelihood:  
- **K-Nearest Neighbors (KNN)**  
- **Logistic Regression (LG)**  
- **XGBoost Classifier**  

Each model is evaluated using metrics such as:  
- **Classification Report** (Precision, Recall, F1-score)  
- **ROC Curve & AUC Score**  
- **Reliability Plot & Brier Score**  
- **Feature Importance Analysis**  

## **Dataset**  
- The dataset used for this analysis is **credit_risk_dataset.csv**, sourced from **Kaggle**. A link to the dataset will be added later.  
- It includes borrower demographics, loan details, employment history, and previous credit behavior.  

## **Project Structure**  
```
📂 credit-risk-analysis
├── README.md              # Project documentation
├── credit_risk_dataset.csv # Dataset used in the analysis
├── docs/                  # Additional project documentation
├── images/                # Generated plots and analysis figures
│   ├── FeatureImportance.png
│   ├── ROC.png
│   └── RealiabilityPlot.png
└── notebook.ipynb         # Jupyter Notebook with full analysis
```

## **How to Use**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/credit-risk-analysis.git
   cd credit-risk-analysis
   ```
2. Open the Jupyter Notebook and run the cells to process data, train models, and analyze results.

## **Visualizations**  
The project includes various visualizations such as:  
- **Scatter Matrix**: Identifying trends and outliers.  
- **Box Plots**: Analyzing loan grades and default probability.  
- **Parallel Category Diagram**: Understanding relationships between categorical features.  
- **ROC Curve**: Model performance comparison.  
- **Feature Importance Plot**: Identifying key predictors of loan default.  

## **Documentation**  
For detailed documentation, refer to the **docs/** directory or the provided LaTeX/PDF documentation.  

## **Contributors**  
- [Your Name]  

## **License**  
This project is licensed under the [MIT License](LICENSE).

