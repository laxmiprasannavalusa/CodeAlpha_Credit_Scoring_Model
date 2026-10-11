# CodeAlpha_Credit_Scoring_Model
Credit Scoring Model using Machine Learning
# Credit Scoring Model Using Machine Learning

## Project Overview

This project uses machine learning classification algorithms to predict credit risk by classifying applicants into good-credit-risk and bad-credit-risk categories.

## Objective

To develop and compare machine learning models for credit risk classification using applicant data.

## Dataset

The project uses the German Credit Risk dataset, containing 1,000 records and 20 input features.

## Technologies Used

* Python
* Google Colab
* Pandas and NumPy
* Matplotlib and Seaborn
* Scikit-learn

## Machine Learning Algorithms

* Logistic Regression
* Random Forest Classifier
* Gradient Boosting Classifier

## Methodology

1. Load and explore the dataset.
2. Preprocess numerical and categorical features.
3. Split the dataset into training and testing sets.
4. Train the classification models.
5. Evaluate and compare model performance.
6. Generate a sample prediction.

## Model Evaluation Results

| Algorithm           | Accuracy | Recall | ROC-AUC |
| ------------------- | -------: | -----: | ------: |
| Logistic Regression |      75% |    80% |  80.58% |
| Random Forest       |      76% | 38.33% |  79.49% |
| Gradient Boosting   |      79% | 56.67% |  79.19% |

Gradient Boosting achieved the highest accuracy among the three tested models, while Logistic Regression achieved the highest recall and ROC-AUC.

## Conclusion

This project demonstrates how machine learning algorithms can be used to classify credit risk and compare model performance. The models are intended for educational purposes and should not be used alone to make real-world lending decisions.
