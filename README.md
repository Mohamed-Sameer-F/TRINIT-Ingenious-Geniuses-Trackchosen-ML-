# TRINIT-Ingenious-Geniuses-Trackchosen-ML-
This is the ML based PS solution done during our TRINIT hackathon

#**Introduction**
Sexual harassment is a pervasive issue affecting individuals across various demographics and settings. It encompasses unwelcome sexual advances, requests for sexual favors, and other verbal or physical conduct of a sexual nature that creates a hostile or offensive environment.

This project focuses on utilizing machine learning techniques, specifically a Multi-Output Classifier with Logistic Regression, to predict types of harassment based on victim stories. Harassment can take various forms, including Commenting, Ogling/Facial Expressions/Staring, and Touching/Groping. By analyzing victim narratives, we aim to automatically classify the type of harassment experienced, which can aid in understanding patterns, allocating resources, and formulating appropriate responses.

#**Model architectur**
The Multi-Output Classifier Logistic Regression model is employed for this task. This model extends logistic regression to handle multiple labels simultaneously. It essentially trains a logistic regression model for each label independently, allowing the prediction of multiple labels for each instance.

#**Key Features**
Text Processing: Utilize natural language processing techniques to preprocess victim narratives and extract meaningful features.

Multi-Output Classification: Employ a multi-output classifier to predict multiple harassment types simultaneously.

Logistic Regression: Utilize logistic regression as the base classifier due to its simplicity and efficiency.

Evaluation Metrics: Assess model performance using appropriate evaluation metrics for multi-label classification tasks, such as precision, recall, and F1-score.

#**Usage**
Data Preprocessing: Preprocess victim stories to extract features suitable for model training.
Model Training: Train the Multi-Output Classifier Logistic Regression model using the preprocessed data.
Model Evaluation: Evaluate the trained model using appropriate evaluation metrics.
Prediction: Utilize the trained model to predict harassment types for new victim stories.


#**Conclusion**
As a beginner Iam unable touse XAI Shap over the given time constraint.This model predicts the type
