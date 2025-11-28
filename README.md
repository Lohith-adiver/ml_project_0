Solubility ML Project (Beginner Level)

Author: Lohith Adiver

Overview

This project focuses on predicting the solubility of molecules using machine learning techniques. Solubility is a critical property in chemistry and pharmaceutical research, and estimating it using computational models can save significant time and resources. The primary objective of this project is to understand how molecular descriptors can be used as input features to predict aqueous solubility.

Objective

To build a predictive model for molecular solubility

To compare the performance of two different regression algorithms

To understand the effect of model complexity on prediction accuracy

Machine Learning Models Used

Linear Regression
A basic regression algorithm used as a baseline model. It identifies a linear relationship between input descriptors and solubility values.

Random Forest Regressor
An ensemble-based model that uses multiple decision trees. It is capable of capturing non-linear patterns in the dataset and generally performs better for complex data.

Key Findings

Random Forest produced more accurate predictions compared to Linear Regression.

Solubility data contains non-linear relationships that a simple linear model cannot capture effectively.

Ensemble methods such as Random Forest are suitable for this type of chemical property prediction.

Dataset

The project uses the Delaney solubility dataset, which contains:

Molecular descriptors as numerical input features

Experimentally measured solubility values as the target output

These descriptors serve as input variables to train the machine learning models.

Tools and Technologies

Python

Google Colab

pandas, numpy

scikit-learn

matplotlib

These libraries were used for data preprocessing, model development, and result visualization.

Methodology

Load and explore the dataset

Prepare input features and target values

Split the dataset into training and testing sets

Train both Linear Regression and Random Forest models

Evaluate and compare the performance of both models

Visualize the results using prediction graphs

Conclusion

The Random Forest model outperformed Linear Regression in predicting molecular solubility. The experiment demonstrates that non-linear models are better suited for this dataset due to the complexity of chemical descriptors and their relationships with solubility.

This project served as an introduction to practical machine learning model implementation and evaluation. It establishes a foundation for exploring more advanced models and datasets in future work.
