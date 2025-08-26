# Micro-Project 3  
**Heart Disease Dataset – Machine Learning Models**

### Extended Description
In Week 3, I focused on **predictive modeling** using five machine learning algorithms: Logistic Regression, Support Vector Machine (SVM), Decision Tree, Random Forest, and K-Nearest Neighbors (KNN).  

**Key Results:**  
- **Logistic Regression:** Accuracy = 0.89, AUC = 0.94. Strong discriminative ability with balanced precision/recall. Coefficients showed Sex, FastingBS, and ExerciseAngina increased risk, while ST_Slope_Up and certain chest pain types decreased it.  
- **SVM (Linear/RBF):** Accuracy = 0.89, AUC = 0.94. Results were nearly identical to Logistic Regression, suggesting the dataset is largely linearly separable.  
- **Decision Tree:** Accuracy = 0.77, AUC = 0.76. Higher misclassification rates (more false positives/negatives) and signs of overfitting.  
- **Random Forest:** Accuracy = 0.88, AUC = 0.94. Strong and stable predictions. Feature importance ranked ST_Slope, Oldpeak, MaxHR, and ExerciseAngina as the most critical predictors.  
- **KNN (best k=10):** Accuracy = 0.87, AUC = 0.93. Performance was solid but slightly weaker than Logistic Regression and Random Forest.  

**Visualizations included:**  
- Confusion matrices for each model  
- ROC curves to compare discriminative performance  
- Logistic Regression coefficient plot  
- Random Forest feature importance chart  
- A summary table ranking models by accuracy  

**Interpretation:**  
Logistic Regression provided interpretability and confirmed known medical risk factors (ST slope, exercise-induced angina, blood sugar, cholesterol). Random Forest reinforced these findings with strong predictive stability. The fact that both models highlighted similar predictors strengthens the reliability of the results.  

**Conclusion:**  
Logistic Regression is a strong baseline with clinical interpretability, while Random Forest offers robust predictive performance. Together, they provide consistent and clinically meaningful insights into heart disease risk factors.  
