# Fraud Detection and Sales Analysis using Random Forest

## Overview  
This project focuses on building machine learning models using Random Forest and other ensemble methods for two key tasks:  
1. **Fraud Detection**: Classify individuals as "Risky" or "Good" based on taxable income.  
2. **Sales Analysis**: Analyze the attributes that contribute to high sales for a cloth manufacturing company.  

Random Forest is utilized as the primary algorithm, along with Logistic Regression, Decision Trees, and SVM for comparison.

---

## Table of Contents  
- [About the Data](#about-the-data)  
- [Project Features](#project-features)  
- [Modeling Techniques](#modeling-techniques)  
- [Results](#results)  
- [How to Run](#how-to-run)  
- [Technologies Used](#technologies-used)  
- [Contributing](#contributing)  
- [License](#license)  

---

## About the Data  

### Fraud Detection Dataset:  
- **Taxable Income**: Used to classify individuals into "Risky" (≤ 30000) or "Good".  
- Additional attributes include: age, work class, education, occupation, and more.  

### Sales Dataset:  
- **Target Variable**: `Sales` (categorized as High/Low based on threshold values).  
- **Features**: Includes Competitor Price, Income, Advertising, Population, Price, Shelf Location, Age, Education, Urban, and US.  

---

## Project Features  
- **Fraud Detection**:  
  - Classification using Random Forest.  
  - Ensemble methods including Bagging and Voting Classifiers.  
  - Evaluation using cross-validation.

- **Sales Analysis**:  
  - Random Forest model to identify key factors contributing to sales.  
  - Exploratory Data Analysis to derive insights.

---

## Modeling Techniques  
1. **Fraud Detection**:  
   - Random Forest Classifier to label individuals as "Risky" or "Good".  
   - Ensemble Voting Classifier with Logistic Regression, Decision Trees, and SVM.  
   - Cross-validation to evaluate performance.  

2. **Sales Analysis**:  
   - Random Forest to analyze features impacting high sales.  
   - Categorized `Sales` into High and Low.  

---

## Results  
### Fraud Detection:  
- Cross-validation results:  
  ```
  array([1.        , 0.98333333, 0.96666667, 0.93333333, 1.        ,
         1.        , 0.98333333, 0.98333333, 1.        , 1.        ])
  ```
- Mean accuracy: **98.5%**

### Sales Analysis:  
- Cross-validation results:  
  ```
  array([0.125, 0.1  , 0.125, 0.225, 0.2  , 0.175, 0.225, 0.075, 0.125, 0.15 ])
  ```
- Mean accuracy: **15.25%**  

---

## How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/R-Mahesh45/Fraud-Detection-and-Sales-Analysis-using-Random-Forest.git
   cd Fraud-Detection-and-Sales-Analysis-using-Random-Forest
   ```

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook or script:  
   ```bash
   python fraud_detection.py
   python sales_analysis.py
   ```

---

## Technologies Used  
- **Languages**: Python  
- **Libraries**:  
  - pandas, numpy  
  - scikit-learn  
  - matplotlib, seaborn  

---

## Contributing  
Contributions are welcome! Please fork the repository and submit a pull request.  

---

## Contact  
For any queries, please reach out to:  
**Mahesh Anil Rathod**  
**Email**: maheshrathod2236@gmail.com  
