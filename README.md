Description:
Developed a machine learning model to predict the likelihood of diabetes onset in females based on Age, Glucose levels, Insulin levels, Pregnancies, and other health features.

Key Steps:

Data Preprocessing:
Utilized the StandardScaler from the sklearn.preprocessing module to standardize feature values, ensuring uniformity and improved model performance.
Employed the train_test_split function from sklearn.model_selection to split the dataset into training and testing subsets for model evaluation.

Model Training:
Implemented a Support Vector Machine (SVM) classifier using the svm module from scikit-learn.
Trained the SVM model on the training dataset to learn patterns and relationships between input features and diabetes outcomes.

Model Evaluation:
Calculated the accuracy of the model predictions using the accuracy_score function from sklearn.metrics.
Assessed model performance on the test dataset to validate its effectiveness in predicting diabetes onset.

Results:
Achieved 77.27% accuracy score on the test dataset, demonstrating the model's efficacy in diabetes prediction.
Created Scatter plot and Regression plot between glucose levels and insulin levels 

**Next Steps:**

Continuously refine and optimize the model through iterative testing and validation processes.
Explore additional features and data sources to enhance prediction accuracy and expand the model's scope to encompass diverse patient populations.
