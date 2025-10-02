# Student Retention Analytics
This project analyzes and predicts **student dropout risk** in a university context using machine learning and exploratory data analysis.  

## Overview
Universities often face the challenge of identifying students at risk of dropping out.  
This project builds a predictive model to anticipate student attrition and extract insights about the main factors driving dropout.  

## Dataset
- Source: [https://www.kaggle.com/datasets/thedevastator/higher-education-predictors-of-student-retention]
- Size: 4424 records, 37 features.
- Features grouped into: demographic, academic performance, attendance, and socio-economic variables.

## Methodology
1. **Data Cleaning & Preprocessing**  
   - Handled missing values, normalized variables.  
2. **Exploratory Data Analysis (EDA)**  
   - Visualized dropout patterns across demographics and academic features.  
   - Built correlation heatmaps and distribution plots.  
3. **Feature Engineering**  
   - Created categorical encodings and derived GPA/attendance metrics.  
4. **Modeling**  
   - Compared Gaussian Naive Bayes, Logistic Regression, Decision Tree, Random Forest, XGBoost and SVM.  
   - **Logistic Regression performed best**, achieving **91% accuracy and 0.95 AUC**.
5. **Insights**
   - Students with more **approved courses in 1st and 2nd semester** were far less likely to drop out.  
   - **On-time tuition payments** correlated with higher retention, suggesting financial stability is key.  
   - **International students** showed higher retention rates, possibly reflecting stronger academic commitment.  
   - Higher **GPA in 2nd semester** reduced dropout risk, emphasizing consistent performance.  
   - **Scholarship holders** were less likely to drop out, highlighting the importance of financial aid.  


## Results
- Logistic Regression achieved **91% accuracy** and **0.95 AUC**, outperforming other models tested.  
- Identified that students with **few approved courses, low GPA, or delayed tuition payments** were at highest risk of dropout.   

## Tools Used
- Python, Pandas, NumPy  
- scikit-learn (Logistic Regression, Random Forest, SVM, Decision Tree, Naive Bayes), XGBoost  
- Matplotlib, Seaborn, Jupyter Notebook  

## Next Steps
- Build interactive dashboard using **Streamlit** to visualize student risk profiles.  
- Deploy predictive model via API.  

## Author
**Alberto Montero Molina**  
- [LinkedIn](https://www.linkedin.com/in/alberto-montero-molina-412b3a249/)  
- [GitHub](https://github.com/albertomonterom)  
