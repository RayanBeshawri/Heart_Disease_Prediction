# Heart Disease Prediction Model

## Overview
This repository contains a comprehensive implementation of heart disease prediction using machine learning techniques. The project explores and compares custom-built Decision Tree and Random Forest classifiers with Scikit-learn models. Additionally, it utilizes AutoGluon for automated model exploration and optimization.

## Features
- **Custom Implementations**: Decision Tree and Random Forest classifiers are implemented from scratch to gain deeper insights into the underlying algorithms.
- **Scikit-learn Models**: Comparison of custom models with Scikit-learn's efficient implementations.
- **Automated Model Exploration**: Use of AutoGluon to evaluate multiple models and find the best performing one.
- **Feature Engineering**: Analysis of feature importance to enhance model performance.
- **Performance Metrics**: Evaluation using accuracy, F1-score, and confusion matrix visualizations.

## Requirements
To run this project, install the dependencies listed in `requirements.txt`:

## Usage

Load the dataset:
The dataset should be in CSV format and named dataset_heart.csv.
Train and Evaluate:
Run the script to train models and evaluate their performance.
AutoGluon will provide an automated leaderboard of various models.
Custom Model Implementation:
The repository includes custom implementations of Decision Tree and Random Forest classifiers, allowing detailed exploration.

## Results:
Visualize metrics such as accuracy, F1-score, and confusion matrices for better interpretation of results.

## Discussion and Conclusion

The custom models demonstrate similar performance to Scikit-learn's models but with slower training times due to:

Recursive architecture design
Lack of multi-threading
Simpler implementation without optimization techniques
Despite achieving reasonable accuracy, the confusion matrix highlights areas for improvement, especially in reducing false negatives. Feature engineering and alternative architectures could further enhance the model's performance.

Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue for suggestions.

License

This project is licensed under the MIT License.
