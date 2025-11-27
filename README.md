# Project Summary – Decision Tree Mini-Models (Titanic Dataset)

This project explores how different preprocessing strategies impact the performance of a Decision Tree classifier on the Titanic – Machine Learning from Disaster dataset. Using Python, Pandas, Scikit-Learn, and SMOTE, we tested multiple approaches for handling missing data, engineering features, and tuning model parameters.

**The workflow includes:**

- Exploratory Data Analysis (EDA): visualizing distributions, correlations, and categorical frequencies.

- Preprocessing: one-hot encoding, removal of irrelevant columns, missing-value handling (mean, median, mode), balancing classes with SMOTE, and creating age bins.

**Feature Engineering:**

- converting Cabin into boolean or removing it entirely,

- merging SibSp and Parch into a single Family variable,

- generating IsAlone, FamilyGroup, and testing their predictive value.

**Model Comparison:** training models with and without age bins and engineered features, analyzing accuracy across multiple configurations.

**Final Model:** built using age bins, removal of Cabin, a combined Family feature and balanced training data.

This setup achieved an improved validation accuracy of approximately 0.78.

**Hyperparameter Tuning:** testing different max_depth and min_samples_leaf values to reduce overfitting and identify the best configuration.

Overall, this notebook demonstrates a complete end-to-end workflow for improving a decision tree model through thoughtful data preparation and structured experimentation.
