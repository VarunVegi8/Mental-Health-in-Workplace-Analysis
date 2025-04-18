# 🧠 Mental Health in the Workplace Analysis

## 📌 Project Overview  
This project investigates the factors influencing mental health treatment-seeking behavior in professional environments. Using the 2014 Mental Health in Tech Survey dataset, the study applies machine learning models to analyze how demographic and workplace-related factors affect whether employees seek help. The insights are intended to guide organizations in developing supportive mental health policies.

## 🎯 Objectives  
- Analyze how demographics and workplace factors influence treatment-seeking behavior.  
- Train ML models to classify individuals based on likelihood to seek treatment.  
- Identify key predictors like gender, family history, and work interference.  
- Provide recommendations to foster stigma-free, supportive workplaces.  

## 📂 Project Files  
- 📄 **Project Report**: AIT582 Final Project Paper.pdf  
- 🧠 **Models Used**: Naive Bayes, Logistic Regression, K-Nearest Neighbors, Random Forest  
- 📊 **Visualizations**: Treatment by age/gender, work interference vs. treatment, mental health consequences by gender  

## 📊 Dataset Information  
- **Name**: 2014 Workplace Mental Health Survey  
- **Source**: Kaggle  
- **Records**: 1,251 responses  
- **Key Columns**:
  - `Age`, `Gender`, `Family History`, `Treatment (Target)`, `Work Interference`, `Workplace Support`  

## 🛠️ Project Workflow  
### Data Preprocessing  
- Treated outliers in age  
- Standardized gender responses  
- Handled missing values using imputation/removal  
- Normalized continuous features  
- Engineered new features (age groups, company size categories)

### Machine Learning Models  
- **Naive Bayes**: Best performance (Accuracy ~82.5%)  
- **Random Forest**: High interpretability and performance (Accuracy ~81.2%)  
- **Logistic Regression**: Linear model with 79.4% accuracy  
- **K-Nearest Neighbors**: Intuitive but lower performance (75.4%)  

### Evaluation Metrics  
- Accuracy  
- Precision, Recall, F1-Score  
- AUC-ROC (for model comparison)  

## 📈 Results & Insights  
- **Top Predictors**: Gender, Family History, Work Interference  
- **Gender Differences**: Males less likely to seek help than Females/Others  
- **Age Patterns**: Majority of treatment seekers in the 20–40 range  
- **Best Model**: Naive Bayes outperformed other models in accuracy  

## 🏆 Conclusion  
- Machine learning can uncover hidden patterns in treatment-seeking behavior.  
- Random Forest and Naive Bayes are effective for predicting outcomes.  
- Findings support creation of proactive, inclusive, and stigma-free workplace policies.

## 🚀 Future Enhancements  
- Use recent and more diverse datasets  
- Explore deep learning and SHAP for interpretability  
- Collaborate with HR departments for real-world implementation  
- Design dashboards/tools for employee self-assessment  

## 📚 References  
- WHO Mental Health in the Workplace (2000, 2022)  
- Bryson et al., NIESR, 2017  
- Ganster & Rosen, Journal of Management, 2013  
- Mental Health America, 2023 Report  
- Additional studies on workplace wellness and stress   

## ⚙️ How to Run the Code (If Implemented Separately)  
1️⃣ **Prerequisites**:  
- Python 3.x  
- Required libraries:  
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

2️⃣ **Steps**:  
- Load the CSV dataset  
- Preprocess (clean, normalize, feature engineer)  
- Train/test using ML models  
- Evaluate performance and visualize insights  
