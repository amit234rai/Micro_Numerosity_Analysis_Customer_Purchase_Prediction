### **Customer Purchase Prediction & Micro-Numerosity Analysis Project Overview**:
#### **Author: AMIT RAI**

This project is conducted as part of my internship at **YBI Foundation**. The goal is to predict customer purchase behavior based on demographic and review-related features, with a specific focus on Micro-Numerosity analysis to understand the impact of small-scale numerical features on purchase predictions.

#### **Objective**:
The primary objective of this project is to leverage machine learning techniques to predict customer purchase behavior. By analyzing a dataset containing demographic information and customer reviews, the goal is to develop a robust predictive model. This model aims to discern patterns and relationships within the data to forecast whether a customer is likely to make a purchase. Furthermore, the project places a specific emphasis on Micro-Numerosity analysis, delving into the impact of small-scale numerical features on the accuracy and reliability of purchase predictions. The insights gained from this analysis will not only contribute to the refinement of the predictive model but also enhance our understanding of the nuanced factors influencing customer purchase decisions.


#### **Steps**:

1. **Data Import and Exploration:**
   - Imported necessary libraries and loaded customer data.
   - Explored the dataset to understand its structure and features.

2. **Data Preprocessing:**
   - Defined target variable (`y`) and feature variables (`X`).
   - Encoded categorical variables for modeling.

3. **Train-Test Split:**
   - Split the dataset into training (80%) and testing (20%) sets.

4. **Model Selection and Training:**
   - Chose a Random Forest Classifier for purchase prediction.
   - Trained the model using the training set.

5. **Model Evaluation:**
   -  Used the trained model to make predictions on the test set.
   -  Evaluated the model accuracy using confusion matrix, accuracy score, and
      classification report.

6. **Feature Importance Visualization:**
   - Visualized the importance of each feature using a bar chart.
   - Identified key factors influencing purchase predictions.

7. **Confusion Matrix Heatmap:**
   - Plotted a heatmap to illustrate model performance via a confusion matrix.
   - Analyzed true positives, true negatives, false positives, and false negatives.

8. **ROC Curve and AUC:**
   - Calculated and visualized the ROC curve and AUC to assess model discrimination.
   - Evaluated the trade-off between true positive rate and false positive rate.

9. **Distribution of Predicted Probabilities:**
   - Examined the distribution of predicted probabilities for positive class predictions ('Yes').
   - Explored the model's confidence levels in predicting customer purchases.

#### **Key Takeaways**:
- Achieved an accuracy of 60% on the test set.
- Feature importance analysis provided insights into influential factors.
- Confusion matrix heatmap detailed model performance across different prediction categories.
- ROC curve and AUC quantified the model's discriminative power.
- Distribution of predicted probabilities shed light on model confidence.

#### **Next Steps**:
- Consider model refinement through hyperparameter tuning.
- Explore additional features or engineering for enhanced predictive power.
- Iterate on the analysis to improve overall model performance.
