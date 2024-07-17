# Heart Disease Prediction Project

## Overview

This machine learning project aims to predict the presence of heart disease in patients using a subset of 14 attributes from a comprehensive database originally containing 76 attributes. The dataset, with sensitive information like names and social security numbers replaced by dummy values, has been widely utilized by ML researchers, particularly the Cleveland database. The target "goal" field in the dataset is an integer ranging from 0 (indicating no presence of heart disease) to 4 (indicating varying degrees of presence). The primary objective of this project is to develop a predictive model capable of distinguishing between the presence (values 1, 2, 3, 4) and absence (value 0) of heart disease.

## Project Objectives

1. **Preprocess the Data**: Clean and prepare the data for analysis.
2. **Feature Exploration**: Analyze and understand the importance of each attribute.
3. **Feature Selection**: Select the most relevant attributes for model building.
4. **Model Implementation**: Develop and evaluate machine learning models to predict heart disease.
5. **Performance Evaluation**: Assess the accuracy and reliability of the models.

## Dataset

The dataset contains information about patients with the following 14 attributes:

1. Age
2. Sex
3. Chest pain type (4 values)
4. Resting blood pressure
5. Serum cholesterol in mg/dl
6. Fasting blood sugar > 120 mg/dl
7. Resting electrocardiographic results (values 0, 1, 2)
8. Maximum heart rate achieved
9. Exercise-induced angina
10. Oldpeak = ST depression induced by exercise relative to rest
11. The slope of the peak exercise ST segment
12. Number of major vessels (0-3) colored by fluoroscopy
13. Thal (3 = normal; 6 = fixed defect; 7 = reversible defect)
14. Goal (the predicted attribute)

The "goal" field is the target variable, with values ranging from 0 to 4. For this project, we will simplify the target variable to a binary classification task where:
- 0 indicates no presence of heart disease.
- 1, 2, 3, 4 indicate the presence of heart disease.

## Project Workflow

1. **Data Preprocessing**
   - Handle missing values.
   - Encode categorical variables.
   - Normalize/standardize numerical variables.
   
2. **Exploratory Data Analysis (EDA)**
   - Visualize data distributions.
   - Analyze correlations between features and the target variable.
   - Identify important features through statistical methods.

3. **Feature Selection**
   - Use techniques like correlation analysis, feature importance from models, and recursive feature elimination to select the most relevant features.
   
4. **Model Building**
   - Split the dataset into training and testing sets.
   - Implement various machine learning algorithms such as Logistic Regression, Decision Trees, Random Forest, and Support Vector Machines.
   - Use cross-validation to tune hyperparameters and avoid overfitting.
   
5. **Model Evaluation**
   - Evaluate models using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.
   - Compare model performance and select the best model for prediction.

## Getting Started

### Prerequisites

- Python 3.7+
- Required libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

## Contributing

Contributions are welcome! Please read the [contributing guide](CONTRIBUTING.md) to get started.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- The dataset used in this project is a publicly available resource provided by the UCI Machine Learning Repository.
- Special thanks to the researchers and contributors of the Cleveland database for making this data accessible.

## Contact

If you have any questions or suggestions, please feel free to reach out:

- Email: = saivenkatmadamanchi@gmail.com
- GitHub: [https://github.com/saivenkatmadamanchi](https://github.com/yourusername)

We hope this project contributes to the advancement of diagnostic tools for cardiovascular health assessment. Happy coding!

---

Note: Customize the above details (such as GitHub links, email, and other personal information) to fit your specific project context.
