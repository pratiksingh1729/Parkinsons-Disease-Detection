🧠 Parkinson’s Disease Detection Using Machine Learning

📌 Project Overview

This project focuses on the early detection of Parkinson’s Disease using machine learning techniques applied to biomedical voice measurements. Parkinson’s Disease is a progressive neurological disorder that affects movement, speech, and motor control. Early diagnosis can significantly improve treatment outcomes and patient quality of life.

The project uses a publicly available Parkinson’s dataset containing voice frequency, jitter, shimmer, and other vocal biomarkers to build a predictive classification model capable of distinguishing between healthy individuals and Parkinson’s patients. The dataset contains 195 observations and 24 attributes, including a target variable (status) indicating the presence or absence of Parkinson’s Disease.

🎯 Objectives

Analyze voice-based biomedical measurements. Perform exploratory data analysis and preprocessing. Identify significant features associated with Parkinson’s Disease. Train and evaluate machine learning classification models. Predict whether a patient is likely to have Parkinson’s Disease based on voice characteristics. Compare model performance using standard evaluation metrics.

📊 Dataset Information

The dataset consists of biomedical voice measurements recorded from individuals with and without Parkinson’s Disease.

Features Include Fundamental Frequency (Fo) Highest Vocal Frequency (Fhi) Lowest Vocal Frequency (Flo) Jitter Measures Shimmer Measures Noise-to-Harmonics Ratio (NHR) Harmonics-to-Noise Ratio (HNR) RPDE DFA D2 PPE Target Variable status = 1 → Parkinson’s Disease Present status = 0 → Healthy Individual

Dataset Summary:

Total Records: 195 Total Features: 24 No Missing Values Detected 🛠 Technologies Used Programming Language Python Libraries numpy pandas matplotlib seaborn scikit-learn xgboost joblib Machine Learning Concepts Data Preprocessing Feature Engineering Classification Algorithms Model Evaluation Hyperparameter Tuning Feature Importance Analysis

🔍 Project Workflow

Data Collection Loaded Parkinson’s voice dataset. Inspected dataset dimensions and feature types.
Data Cleaning Checked for null values. Verified data consistency. Removed unnecessary attributes if required.
Exploratory Data Analysis (EDA) Statistical summaries Distribution analysis Correlation analysis Feature relationship visualization
Feature Selection
Selected the most informative voice biomarkers that contribute to Parkinson’s prediction.

Model Development
Implemented and compared multiple classification models:

Logistic Regression Random Forest Classifier Support Vector Machine (SVM) XGBoost Classifier 6. Model Evaluation

Performance evaluated using:

Accuracy Precision Recall F1 Score ROC-AUC Score Confusion Matrix

📈 Key Findings

Voice-based biomarkers provide strong indicators of Parkinson’s Disease. Features related to jitter, shimmer, and frequency variations contribute significantly to classification performance. Ensemble models such as Random Forest and XGBoost generally outperform traditional linear models. Machine learning can effectively assist clinicians in early Parkinson’s screening and diagnosis.

📊 Performance Metrics

Metric Description Accuracy Overall prediction correctness Precision Correct positive predictions Recall Ability to identify Parkinson’s cases F1 Score Balance of precision and recall ROC-AUC Overall classification capability

Replace this section with your actual model results after training.

📁 Project Structure

Parkinsons-Disease-Detection/ │ ├── data/ │ └── parkinsons.csv │ ├── notebooks/ │ └── Parkinsons_Detection.ipynb │ ├── models/ │ └── trained_model.pkl │ ├── images/ │ ├── correlation_heatmap.png │ ├── feature_importance.png │ ├── confusion_matrix.png │ └── roc_curve.png │ ├── requirements.txt │ └── README.md

💡 Future Improvements

Deep Learning-based Disease Detection Explainable AI (SHAP/LIME) Real-Time Voice Input Prediction Web Application Deployment using Streamlit Integration with Healthcare Monitoring Systems

👨‍💻 Author

Pratik Singh
