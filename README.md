# HealthCare Analytics Disease Prediction
<h1>Abstract</h1> 
Diabetes is a widespread chronic condition that requires early diagnosis for effective management. This study evaluates and compares the performance of three machine learning models—Logistic Regression, Random Forest, and XGBoost—for predicting diabetes using health-related features. The goal was to identify the most accurate and balanced model based on key evaluation metrics: accuracy, precision, recall, and F1-score. Results show that Logistic Regression outperforms the other models, achieving the highest accuracy (76%) and a strong balance between precision (67%) and recall (64%). These findings suggest that Logistic Regression is a reliable and interpretable model for diabetes prediction, offering potential benefits for early screening and improved healthcare decision-making. 

<h1>Objective</h1> 
Objective: The objective of this study is to evaluate and compare the effectiveness of various machine learning models in predicting diabetes based on available health data. Specifically, we aim to analyze the performance of Logistic Regression, and Random Forest, models to determine the best approach for accurate diabetes classification. The focus is on identifying the model with the highest accuracy, precision, recall, and F1-score while minimizing false positives and false negatives. 

<h1>Problem Statement</h1> Diabetes is a chronic health condition that affects millions of people worldwide. Early diagnosis is crucial for effective management and treatment. However, traditional diagnostic methods can be time-consuming and require extensive medical examinations. Machine learning offers an opportunity to automate and enhance the prediction process, improving efficiency and accuracy. The challenge is to develop a reliable predictive model that can correctly classify individuals as diabetic or non-diabetic, ensuring a balance between precision and recall minimizing misclassification errors. 

<h1>Introduction</h1> Machine learning has emerged as a powerful tool in the healthcare industry, particularly for disease prediction and classification. In this study, we explore the use of three machine learning models—Logistic Regression and Random Forest to classify individuals as diabetic or non-diabetic based on health-related features. 

Logistic Regression is a widely used statistical method for binary classification problems, providing interpretable results and a solid baseline for comparison. Random Forest, an ensemble learning method, enhances prediction accuracy by combining multiple decision trees.  

Our evaluation focuses on key performance metrics, including accuracy, precision, recall, and F1-score, to determine the best model for diabetes prediction. Based on the results, Logistic Regression outperforms the other models with an accuracy of 76%, the best balance of precision (67%) and recall (64%), and fewer false positives and false negatives. This analysis highlights the importance of model selection in medical diagnosis and the potential of machine learning in improving healthcare outcomes. 

<h1>Method</h1> In this study, Logistic Regression was employed as one of the primary machine learning models for predicting diabetes. The dataset used consisted of various health-related features such as glucose level, BMI, age, insulin levels, blood pressure, and the diabetes pedigree function, with each instance labeled as either diabetic (1) or non-diabetic (0). Logistic Regression was chosen for its simplicity, efficiency, and interpretability in binary classification problems. Before training the model, the data underwent preprocessing steps, including handling missing values, normalizing numerical features, and splitting the data into training and testing sets. The model was then trained on the processed dataset and evaluated using standard performance metrics such as accuracy, precision, recall, and F1-score. The results demonstrated that Logistic Regression achieved the highest overall performance, with an accuracy of 76%, precision of 67%, recall of 64%, and an F1-score of 65%, making it the most balanced and effective model among those tested for diabetes prediction. 

 

 <h1>Results</h1> 

| Table 1 Metric                            | Logistic Regression | Random Forest | XGBoost |
|----------------------------------|---------------------|----------------|---------|
| Accuracy                         | 76%                | 71%           | 70%     |
| Precision (Diabetic - Class 1)   | 67%                | 59%           | 57%     |
| Recall (Diabetic - Class 1)      | 64%                | 67%           | 67%     |
| F1-Score (Diabetic - Class 1)    | 65%                | 63%           | 62%     |



Table 1 discription: The results compare the performance of Logistic Regression and Random Forest models in predicting diabetes. Logistic Regression achieved higher overall accuracy (76%) compared to Random Forest (71%). It also performed better in terms of precision (67% vs. 59%), indicating it made fewer false positive predictions. However, Random Forest had a slightly better recall (67% vs. 64%), meaning it identified more actual diabetic cases. The F1-score, which balances precision and recall, was slightly higher for Logistic Regression (65% vs. 63%). The confusion matrix for Logistic Regression shows it correctly classified most non-diabetics (82), but missed 20 diabetics. Overall, Logistic Regression slightly outperformed Random Forest in this case.


| Logistic Regression Confusion Matrix Results| |
| --- |--- |
|82 Non-Diabetics correctly classified |
|17 Non-Diabetics misclassified as Diabetic  |
|20 Diabetics misclassified as Non-Diabetic (false negatives) |
|35 Diabetics correctly classified |



| Random Forest Confusion Matrix Results| |
| --- | --- |
|73 Non-Diabetics correctly classified |
|26 Non-Diabetics misclassified as Diabetic (false positives)  |
|18 Diabetics misclassified as Non-Diabetic |
|37 Diabetics correctly classified  |


| XGBoost Results Confusion Matrix Results| |
| --- | --- |
|71 Non-Diabetics correctly classified  |
|28 Non-Diabetics misclassified as Diabetic (false positives)   |
|18 Diabetics misclassified as Non-Diabetic |
|37 Diabetics correctly classified  |

  
 <h1>Discussion</h1>
 
The results of this study highlight the potential of machine learning, particularly Logistic Regression, in improving the accuracy and efficiency of diabetes prediction. Among the three models evaluated—Logistic Regression, Random Forest, and XGBoost—Logistic Regression emerged as the best performer, achieving the highest accuracy (76%) and the most balanced precision (67%) and recall (64%) scores. This indicates that Logistic Regression is not only effective in correctly identifying diabetic individuals but also in minimizing false positives and false negatives, which is crucial in a medical context where misclassification can lead to delayed treatment or unnecessary anxiety. 

While Random Forest and XGBoost showed slightly higher recall values (67%), their lower precision and accuracy suggest a greater tendency to misclassify non-diabetics as diabetic, which may lead to over-diagnosis. Logistic Regression, on the other hand, provided more consistent results, likely due to its straightforward modeling of the relationship between features and the binary outcome. Its interpretability also makes it valuable in healthcare settings, where understanding the contribution of individual risk factors is essential. 

These findings support the use of Logistic Regression as a reliable baseline model for diabetes prediction, especially when model simplicity and explainability are prioritized. However, further improvements could be explored by combining models (ensemble techniques), tuning hyperparameters, or incorporating more diverse health features. Additionally, validating the model on larger and more diverse datasets would enhance its generalizability and robustness in real-world applications. 

 
<h1>Conclusion</h1> 
 
This study demonstrates the effectiveness of machine learning in diabetes prediction, with Logistic Regression emerging as the most accurate and balanced model among those tested. Its simplicity, high performance, and interpretability make it particularly suitable for medical applications where accurate classification and understanding of contributing factors are critical. While Random Forest and XGBoost offered slightly higher recall, their lower precision and increased misclassification rates reduced their overall reliability. Logistic Regression not only achieved the highest accuracy but also minimized false positives and false negatives, making it a valuable tool for supporting early diagnosis and personalized healthcare strategies. Future work can explore model enhancements, feature expansion, and validation on diverse populations to further improve predictive performance. 

 <h1>References</h1> 
 - reference 1
 - reference 2
 
 <h1>Contrubutions</h1> 
 
 

 

