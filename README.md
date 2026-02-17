# task4-logistic-regression
The objective of this task is to build a binary classification model using Logistic Regression and evaluate its performance using different metrics.
Dataset Used : I used the Breast Cancer Wisconsin Dataset.
This dataset contains medical features of tumors and the target variable indicates whether the tumor is:
* 0 → Benign
* 1 → Malignant
 Tools & Libraries Used
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
## Steps Performed
1. Imported required libraries
2. Loaded the dataset using pandas
3. Removed unnecessary columns
4. Converted target column into binary values
5. Split data into training and testing sets
6. Standardized features using StandardScaler
7. Trained Logistic Regression model
8. Made predictions on test data
9. Evaluated model using:
   * Accuracy
   * Confusion Matrix
   * Precision & Recall
   * ROC Curve
   * AUC Score
10. Plotted ROC curve for both Train and Test datasets
##  Model Performance
* The model achieved high accuracy (around 95–98%).
* The ROC-AUC score was close to 1, which indicates strong classification performance.
* The ROC curve shows that the model performs much better than a random classifier.
##  Key Concepts Learned
* Binary Classification
* Logistic Regression
* Sigmoid Function
* Confusion Matrix
* Precision and Recall
* ROC Curve & AUC
* Threshold tuning
##  Conclusion
This task helped me understand how logistic regression works for classification problems. I learned how to evaluate a model using different metrics instead of relying only on accuracy. The ROC-AUC score confirmed that the model performs effectively on unseen data.


