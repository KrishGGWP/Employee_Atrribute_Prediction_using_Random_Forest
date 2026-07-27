# Employee Attrition Prediction using Decision Tree and Random Forest Classification

## Student Details

- **Name:** Krish Sachan
- **Registration Number:** 23BET10033
- **Application Number:** IN26010941
- **University:** VIT Bhopal University
- **Course:** B.Tech Computer Science and Engineering (Edu Technology)
- **Batch:** 2B
- **Graduation Year:** 2027
- **Email:** krish.23bet10033@vitbhopal.ac.in

## Objective

The objective of this project is to predict employee attrition using Decision Tree and Random Forest classification models. The performance of both models is evaluated and compared using standard classification metrics to identify the most effective approach for employee attrition prediction.

## Dataset

**IBM HR Analytics Employee Attrition & Performance Dataset**

Kaggle: https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Methodology

1. Loaded the IBM HR Analytics Employee Attrition dataset.
2. Performed data exploration and identified numerical and categorical features.
3. Checked for missing values and removed unnecessary columns.
4. Encoded categorical variables using Label Encoding.
5. Split the dataset into 80% training and 20% testing sets.
6. Trained a Decision Tree Classifier.
7. Trained a Random Forest Classifier with 100 estimators.
8. Evaluated both models using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.
9. Compared the performance of both models and visualized feature importance for the Random Forest model.

## Results

The Random Forest Classifier achieved better overall performance than the Decision Tree Classifier by providing higher Accuracy, Precision, Recall, and F1-Score. It also produced more stable predictions due to ensemble learning.

## Model Comparison

| Model | Description |
|--------|-------------|
| Decision Tree | Easy to interpret but susceptible to overfitting. |
| Random Forest | More accurate, robust, and less prone to overfitting by combining multiple decision trees. |

## Conclusion

Both Decision Tree and Random Forest classifiers were successfully implemented to predict employee attrition. The Random Forest model outperformed the Decision Tree across most evaluation metrics because it reduces overfitting by aggregating predictions from multiple trees. Although Decision Trees are simple and highly interpretable, they can become unstable with slight changes in the training data. Random Forest provides better generalization and prediction accuracy but requires greater computational resources and is less interpretable. Overall, Random Forest is the preferred model for this employee attrition prediction task.

## Repository Structure

```
Assignment-5.ipynb
README.md
```
