# Project Name

> Fraudulent Claim Detection

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Evaluation](#evaluation)
- [Conclusion](#conclusion)
- [Recommendations](#recommendations)
- [Contact](#contact)

## General Information

- **Background of the Project**: Fraudulent activities are a significant challenge in the insurance industry. Detecting fraud efficiently is crucial for minimizing financial losses. The objective of this project is to build a machine learning model to detect fraudulent insurance claims. We use Logistic Regression and Random Forest models to predict the likelihood of fraud based on various features such as incident severity, injury claims, policy tenure, and more.
  
- **Business Problem**: The business needs an automated system that can quickly flag potentially fraudulent claims to minimize financial loss. By leveraging machine learning models, fraud detection can be improved, reducing the manual effort involved and increasing the speed of claims processing.
  
- **Dataset**: The dataset contains features from insurance claims, including incident severity, injury types, claim severity, customer age, policy tenure, and more. The target variable is binary: whether the claim is fraudulent (`1`) or legitimate (`0`).

## Evaluation

The models were evaluated using several metrics:

- **Logistic Regression**:
  - Validation Accuracy: 83.5%
  - Sensitivity (Recall): 61.22%
  - Precision: 68.18%
  - F1 Score: 64.52%
  - Specificity: 90.73%

- **Random Forest (Tuned)**:
  - Validation Accuracy: 82.5%
  - Sensitivity (Recall): 75.51%
  - Precision: 61.67%
  - F1 Score: 67.89%
  - Specificity: 84.77%

### Conclusion

- **Conclusion 1**: The **Random Forest model** has better recall (75.51%) compared to **Logistic Regression** (61.22%), which makes it more effective at detecting fraudulent claims. However, **Logistic Regression** is more interpretable and can provide insights into the importance of different features.

- **Conclusion 2**: The most significant features contributing to fraud detection include **incident severity**, **injury claims**, **policy tenure**, and **customer age**. These features had a significant impact on the model's prediction accuracy.

- **Conclusion 3**: The **Random Forest model** provides better performance in detecting fraudulent claims, but **Logistic Regression** offers a trade-off between performance and interpretability, which can be valuable in business settings.

### Recommendations

- **Deploy Random Forest** for fraud detection, as it has better recall and is better suited for identifying fraudulent claims.
  
- **Monitor Precision-Recall Trade-offs** to maintain accuracy in fraud detection, ensuring a balance between false positives and false negatives.

- **Implement a Dashboard** to track model performance and real-time fraud detection metrics for continuous monitoring and improvement.

- **Train a Hybrid Model** that combines both Random Forest and Logistic Regression to leverage the strengths of each for both detection power and interpretability.

## Technologies Used

- **pandas** - version 2.2.2
- **numpy** - version 1.26.4
- **matplotlib** - version 3.9.2
- **seaborn** - version 0.13.2
- **sklearn** - version 1.5.1
- **IPython** - version 7.34.0
- **statsmodels** - version 0.14.2

## Contact

Created by [@vaishalimakwana] - feel free to contact me!

Created by [Praveenkumar Periyaswamy]
