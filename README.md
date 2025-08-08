🧠 Alzheimer’s Disease Detection
This project aims to detect Alzheimer’s disease using machine learning techniques.
It processes patient data, applies preprocessing pipelines, and trains predictive models to classify Alzheimer’s presence based on medical and demographic features.

📂 Project Structure
alzeihmer_detectionipynb.ipynb – Jupyter Notebook containing all code for data loading, preprocessing, model training, and evaluation.

alzheimers_disease_data.csv – Dataset containing patient information and Alzheimer’s diagnosis labels (not included here for privacy).

🚀 Features
Data cleaning and preprocessing:

Removal of irrelevant columns (PatientID, DoctorInCharge).

Identification of numerical and categorical features.

Scaling and encoding using MinMaxScaler / StandardScaler.

Model Training:

Logistic Regression

Random Forest Classifier

Model Evaluation:

Accuracy score

Classification Report

Confusion Matrix Visualization

🛠 Technologies Used
Python 3

Pandas, NumPy – Data handling

Matplotlib, Seaborn – Visualization

Scikit-learn – Machine Learning models & preprocessing

📊 Workflow
Import Libraries – Load all required dependencies.

Load Dataset – Read Alzheimer’s disease dataset from CSV.

Preprocess Data – Handle categorical and numerical columns.

Split Data – Train-test split for model evaluation.

Train Models – Logistic Regression & Random Forest.

Evaluate Models – Compare performance using accuracy and confusion matrices.

📈 Results
The models are evaluated to determine the best-performing classifier for Alzheimer’s prediction.

Metrics like accuracy and classification report help in model comparison.
