PCOS Diagnosis Prediction using Machine Learning
This project involves predicting Polycystic Ovary Syndrome (PCOS) using machine learning algorithms. PCOS is a common hormonal disorder in women that can affect their fertility and overall health. Early detection is crucial, and machine learning models can assist in making accurate predictions based on a set of features.

Dataset
The dataset used contains information about women with PCOS, including features like Age, BMI, Testosterone Level, and Antral Follicle Count, which are commonly associated with the condition. The target variable is PCOS Diagnosis (0 = No, 1 = Yes).

Features:
Age: The age of the patient (18-45 years).

BMI: The Body Mass Index (18-35).

Menstrual Irregularity: Binary indicator for irregular menstrual cycles (0 = No, 1 = Yes).

Testosterone Level: Testosterone level in ng/dL (20-100).

Antral Follicle Count: Number of antral follicles detected in ultrasound (5-30).

PCOS Diagnosis (Target): 0 = No PCOS, 1 = PCOS.

Project Workflow
Data Preprocessing:

SMOTE (Synthetic Minority Over-sampling Technique) was used to address class imbalance and ensure a balanced dataset for training.

Split the data into training and test sets.

Modeling:

Tested various models to predict PCOS:

Logistic Regression

Random Forest

XGBoost

Decision Tree

Cross-validation was applied to tune hyperparameters and assess model performance.

Evaluation:

Models were evaluated using metrics such as accuracy, precision, recall, and confusion matrices.

The best models were identified based on the evaluation results.

Results:

The models performed well, with XGBoost and Random Forest providing the best results in predicting PCOS diagnosis.

Libraries Used
pandas: Data manipulation and analysis

numpy: Numerical operations

scikit-learn: Machine learning algorithms and utilities (e.g., cross-validation, SMOTE, models)

xgboost: XGBoost algorithm for boosting

matplotlib / seaborn: Data visualization

imbalanced-learn: SMOTE implementation

Future Work
Test more algorithms like Support Vector Machines (SVM) and K-Nearest Neighbors (KNN).

Integrate the model into a web application for real-time PCOS diagnosis prediction.

Improve model performance by experimenting with additional feature engineering.

Conclusion
This project highlights the application of machine learning in healthcare, demonstrating how data science can aid in early detection and improve patient outcomes.
