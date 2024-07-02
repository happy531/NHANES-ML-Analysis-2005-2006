# Machine Learning Analysis on NHANES Dataset

Semester ML Project from Gdańsk University of Technology, Faculty of Electronics, Telecommunications and Informatics.

This project focuses on conducting a comprehensive machine learning analysis on the National Health and Nutrition Examination Survey (NHANES) dataset from the years 2005 to 2006. The goal is to apply various machine learning techniques to understand patterns, make predictions, and derive insights from the dataset.

## Overview

The NHANES dataset for the years 2005-2006 is utilized as the primary data source for this analysis. This dataset is known for its rich information on the health and nutritional status of the US population, making it an excellent candidate for in-depth machine learning analysis.

## Features

The project leverages several Python libraries to preprocess, analyze, and model the NHANES data:

- **Pandas**: For data manipulation and analysis.
- **Scikit-learn**: Offers various tools for machine learning, including preprocessing, model selection, and evaluation metrics.
- **Imbalanced-learn (imblearn)**: Provides methods for dealing with imbalanced datasets, such as SMOTE for oversampling.
- **SciPy**: Used for scientific computing and technical computing.
- **Matplotlib & Seaborn**: For data visualization.

## Machine Learning Workflow

The project encompasses a series of steps to ensure a thorough analysis of the NHANES dataset:

1. **Data Preprocessing**: Standardization, normalization, and encoding categorical variables to prepare the data for machine learning models.
2. **Model Selection**: Utilizes a variety of machine learning models, including Decision Tree Classifier, Random Forest Classifier, Gradient Boosting Classifier, Logistic Regression, and Support Vector Classifier (SVC).
3. **Evaluation**: Employs metrics such as recall, precision, F1 score, and accuracy to evaluate model performance.
4. **Cross-Validation**: Implements Stratified K-Fold cross-validation to ensure the model's generalizability across different subsets of the dataset.
5. **Visualization**: Generates plots to visualize the data distribution, model performance, and other key insights.

## Getting Started

To run this project, ensure you have Python installed on your system along with the necessary libraries mentioned above. The dataset can be accessed directly from the provided source URL.

```bash
pip install pandas scikit-learn matplotlib seaborn imbalanced-learn scipy
```

## Usage

The analysis is encapsulated in a Jupyter Notebook, making it easy to follow along and execute the code cells sequentially to reproduce the results.

## Conclusion

This project aims to provide a comprehensive analysis of the NHANES 2005-2006 dataset using various machine learning techniques. By exploring different models and evaluation strategies, it seeks to uncover valuable insights into the health and nutritional status of the population.