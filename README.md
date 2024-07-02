# Financial-Fraud-Detection
### Financial Fraud Detection Project

#### Objective:
The primary goal of this project was to develop a robust model capable of accurately detecting fraudulent transactions within a financial dataset. Given the critical nature of identifying fraud, special attention was given to maximizing the detection rate of fraudulent activities.

#### Methodology:
1. **Exploratory Data Analysis (EDA):**
   - Performed detailed EDA to understand the distribution and relationships of key features.
   - Visualized data using histograms, box plots, and correlation matrices to identify patterns and potential outliers.
   - Assessed class imbalance and the distribution of fraudulent versus non-fraudulent transactions.

2. **Data Preprocessing:**
   - Cleaned the dataset by handling missing values and outliers.
   - Standardized and normalized numerical features to ensure consistent scaling.
   - Used techniques such as SMOTE to balance the classes, addressing the imbalance between fraudulent and non-fraudulent transactions.

3. **Model Development:**
   - Implemented various classification models including Decision Tree, Random Forest, XGBoost, and Balanced Random Forest.
   - Tuned hyperparameters using GridSearchCV to optimize model performance.
   - Evaluated models based on precision, recall, F1-score, and accuracy, with a particular focus on maximizing the recall for fraudulent transactions.

4. **Model Evaluation and Selection:**
   - The XGBoost classifier emerged as the best-performing model, achieving a precision and recall of 97% for fraudulent transactions.
   - Visualized model performance using confusion matrices, ROC curves, and precision-recall curves.
   - Assessed feature importance to understand which features contributed most to the predictions.

5. **Key Visualizations:**
   - **Confusion Matrix:** Illustrated the number of true positives, true negatives, false positives, and false negatives, highlighting the model's ability to correctly identify fraudulent transactions.
   - **ROC Curve:** Demonstrated the trade-off between true positive rate and false positive rate, with an area under the curve (AUC) indicating excellent discrimination ability.
   - **Precision-Recall Curve:** Showed the balance between precision and recall, particularly important for imbalanced datasets.
   - **Feature Importance Plot:** Identified the most significant features contributing to the model's decisions, aiding in interpretability and further refinement.

#### Conclusion:
The XGBoost classifier, with its superior performance, was selected as the final model for detecting fraudulent transactions. It successfully identified fraudulent activities with a recall rate of 97%, ensuring that most fraudulent transactions were correctly flagged. This high level of accuracy in identifying fraud makes the model a valuable tool for financial institutions to mitigate risks and prevent financial losses due to fraud.

This project demonstrates the effectiveness of combining advanced machine learning techniques with thorough data analysis and preprocessing to tackle the challenging problem of financial fraud detection.
