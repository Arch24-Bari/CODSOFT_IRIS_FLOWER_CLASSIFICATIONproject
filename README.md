# CODSOFT_IRIS_FLOWER_CLASSIFICATIONproject
This project performs a multi-class classification on the Iris dataset.

**Data Loading and Exploration**: The project starts by loading the Iris dataset and performing initial data exploration using df.sample(), df.info(), df.describe(), and df['species'].value_counts().

Data Preprocessing: The 'species' column, which is of object type, is converted to an integer type using LabelEncoder.

Data Visualization: Univariate analysis is performed using histograms to visualize the distribution of 'sepal_width', 'sepal_length', 'petal_length', and 'petal_width'. Multivariate analysis is done using pairplot to visualize the relationships between features and the 'species' column, and a heatmap is used to confirm the correlations.

Model Training: The data is split into training and testing sets. **Three classification models** are trained:
**Logistic Regression
Decision Tree Classifier
KNeighbors Classifier**

Model Evaluation: The accuracy, confusion matrix, and classification report are calculated for each model.

Model Comparison: A bar plot is generated to compare the accuracy of the three models. All models achieved 100% accuracy on the test set.

Prediction: A sample prediction is made using the trained Logistic Regression model.
