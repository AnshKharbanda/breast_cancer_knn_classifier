# Breast Cancer Classification using KNN

This project explores how machine learning can be used to help classify breast tumors as malignant or benign.
The goal is to build a simple but complete machine learning pipeline that takes medical features from tumor cell images and predicts whether the tumor is cancerous.
The project uses the Breast Cancer Wisconsin diagnostic dataset, which contains measurements of cell nuclei extracted from digitized images of breast masses.

Project workflow:

The model was built step by step following a typical machine learning pipeline:
1. Data loading and initial inspection
2. Outlier detection using the IQR method
3. Removing highly correlated features
4. Feature scaling to normalize the data
5. Splitting the dataset into training and testing sets
6. Training a K-Nearest Neighbors classifier
7. Hyperparameter tuning to find the best value of k
8. Evaluating the model using accuracy, recall, confusion matrix and ROC curve

Model used:
K-Nearest Neighbors (KNN) classifier.
KNN was chosen because it is a simple and intuitive algorithm that works well for structured datasets when features are properly scaled.

Results:
Best k value found during tuning: 7

Model performance:
Accuracy: around 95%
Recall: 95.34%
ROC AUC score: 0.988
These results indicate strong performance, especially for detecting malignant cases, which is important in medical diagnosis tasks.

Visualization:
The ROC curve shows the classifier's ability to distinguish between malignant and benign tumors.

Technologies used:
Python
NumPy
Pandas
Scikit-learn
Matplotlib
Seaborn
