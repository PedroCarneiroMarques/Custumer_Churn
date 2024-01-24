# Telecom_Custumer_Churn

This dataset is perfect for practicing prescriptive analysis such as predictive prescription or predictive decision making. 
The reason is that the dataset has the attribute of customer value which allows for creating False Positive (FP) and False Negative(FN) costs in case of misclassification.
In standard classification tasks, it is assumed that FPs and FNs are the same, which is not the case for many cases. 
Furthermore, even if it is recognized that FPs and FNs are indeed different, their different balances per each data object are not understood or taken into consideration. 
This dataset gives you the opportunity to create a model that recognizes these complexities. For further information about the balance of FPs and FNs see the first mentioned publication. 
Also, you can find more information about each attribute on one of the publications.

Exploratory Data Analysis (EDA)

Data Loading and Basic Exploration

Loaded the dataset from a CSV file).

Checked basic information about the dataset using df.info().

Displayed summary statistics using df.describe().

Checked for missing values using df.isnull().sum().

Data Preprocessing

Handled missing values (if any).

Converted categorical columns to numerical format (if needed).

Standardized/Normalized numerical columns (if needed).

Visualizations

Explored relationships between variables using pairplots and correlation heatmaps.

Visualized the distribution of the target variable 'Churn'.

Explored correlations between numerical variables.

Utilized histograms, box plots, count plots, KDE plots, violin plots, and custom pairwise relationships using PairGrid.

Model Training and Evaluation

Random Forest Classifier

Split the data into training and testing sets using train_test_split.

Trained a Random Forest Classifier with hyperparameter tuning using GridSearchCV.

Evaluated the model using accuracy, confusion matrix, ROC curve, and feature importance.

Support Vector Machine (SVM)

Trained an SVM with hyperparameter tuning using GridSearchCV.

Evaluated the SVM model using accuracy and classification report.

Gradient Boosting Classifier

Trained a Gradient Boosting Classifier with hyperparameter tuning using GridSearchCV.

Evaluated the model using accuracy and classification report.

K-Nearest Neighbors (KNN)

Trained a K-Nearest Neighbors model with hyperparameter tuning using GridSearchCV.

Evaluated the model using accuracy and classification report.

Conclusion

Brief summary of the key insights obtained from the EDA and model evaluations. Discuss any notable patterns, correlations, or findings from the analysis.

Future Work

Mention any potential areas for further exploration or improvements, such as feature engineering, additional models, or different hyperparameters.
