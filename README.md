# Logistic-Regression

**Overview**

The script is designed to build a Logistic Regression model for classifying individuals based on disease diagnosis. It includes data loading, preprocessing, model training, and evaluation using various metrics. Additionally, visualizations such as ROC curves and confusion matrices are generated for both training and test sets.

**Dataset**

The dataset used is Final_Preprocessed_data.csv, containing features pertinent to disease diagnosis. The dataset is divided into training and test sets to validate the model's efficacy.

**Features**

The dataset consists of various features significant to disease diagnosis. The target variable is encoded for model compatibility.

**Model**

Logistic Regression, a linear model for classification, is employed from scikit-learn. The model is known for its simplicity and efficiency in binary classification tasks.

**Performance Metrics**
The model's performance is assessed using metrics such as:

Accuracy
Precision
Recall
ROC-AUC Score

**Visualization**
Two primary visualizations are included:

ROC Curve: Illustrates the model's diagnostic ability at various threshold settings for both training and test sets.

Confusion Matrix: Displays the true positives, true negatives, false positives, and false negatives, providing insight into the model's classification accuracy.

**Requirements**

Necessary libraries for this script include pandas, scikit-learn, and matplotlib, which facilitate data handling, model building, and visualization.

