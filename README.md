# 🧠 Alzheimer’s Disease Detection

This project predicts Alzheimer’s disease using machine learning models trained on patient demographic, lifestyle, and medical data. It uses a structured dataset with **2,149 patient records** and **35 features** to classify whether a patient is likely to have Alzheimer’s.

---

## 📂 Project Files

*   **`alzheimer_detection.ipynb`** – Google Colab notebook for data preprocessing, model training, and evaluation.
*   **`alzheimers_disease_data.csv`** – The dataset containing patient details, lifestyle factors, cognitive scores, and diagnosis labels. *(Note: This file is not public for privacy reasons.)*

---

## 📊 Dataset Overview

*   **Rows:** 2,149
*   **Columns:** 35
*   **Target Variable:** `Diagnosis` (0 = No Alzheimer’s, 1 = Alzheimer’s detected)

### Example Features:
*   **Demographics:** `Age`, `Gender`, `Ethnicity`, `EducationLevel`
*   **Lifestyle:** `BMI`, `Smoking`, `AlcoholConsumption`, `PhysicalActivity`, `DietQuality`, `SleepQuality`
*   **Medical History:** `FamilyHistoryAlzheimers`, `CardiovascularDisease`, `Diabetes`, `Hypertension`
*   **Cognitive Tests:** `MMSE`, `FunctionalAssessment`
*   **Symptoms:** `MemoryComplaints`, `Confusion`, `Forgetfulness`, `Disorientation`

### Dropped Columns:
*   `PatientID`, `DoctorInCharge` (irrelevant for prediction)

---

## 🚀 Features of the Project

### Preprocessing
*   Dropping irrelevant columns.
*   Identifying and separating categorical & numerical features.
*   Scaling features using **`MinMaxScaler`** and **`StandardScaler`**.

### Models Implemented
*   **Logistic Regression**
*   **Random Forest Classifier**

### Evaluation Metrics
*   **Accuracy Score**
*   **Classification Report** (Precision, Recall, F1-Score)
*   **Confusion Matrix** Visualization

---

## 🛠 Tech Stack

*   **Python 3**
*   **Google Colab** – Cloud-based notebook environment
*   **Pandas & NumPy** – Data processing and manipulation
*   **Matplotlib & Seaborn** – Data visualization
*   **Scikit-learn** – Machine learning models and preprocessing tools

---

## 📈 Workflow

1.  **Import Dependencies** in the Google Colab notebook.
2.  **Upload the Dataset** (`alzheimers_disease_data.csv`) to the Colab environment.
3.  **Preprocess Data**:
    *   Drop unused columns.
    *   Encode categorical features.
    *   Scale numerical features.
4.  **Split Data** into training and testing sets.
5.  **Train Models**: Train the Logistic Regression and Random Forest models.
6.  **Evaluate Models**: Compare performance using accuracy, the classification report, and confusion matrix visualizations.

---

## ▶ How to Run in Google Colab

1.  Open the **`alzheimer_detection.ipynb`** notebook in Google Colab.
2.  Upload the `alzheimers_disease_data.csv` file when prompted by the notebook's upload cell.
3.  Go to **Runtime > Run all** to execute all cells from top to bottom.

---

## 📌 Future Enhancements

*   Apply **hyperparameter tuning** (e.g., GridSearchCV) for improved model performance.
*   Explore additional machine learning algorithms (e.g., Gradient Boosting, SVM).
*   Experiment with **deep learning models** (e.g., neural networks) for potentially higher accuracy.
*   Deploy the best-performing model as a web-based prediction tool using a framework like Flask or FastAPI.
