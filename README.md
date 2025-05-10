# AI_ML-BREAST_cancer_SVM_TASK7

Breast Cancer SVM Classification:

This project uses Support Vector Machine (SVM) models to classify breast cancer as benign or malignant based on a dataset.

📂 Project Files

task7_Breast_cancer_SVM.ipynb → Jupyter Notebook with code for data loading, preprocessing, SVM training, and evaluation.

📊 Dataset:

Breast cancer dataset (breast-cancer.csv) with features like radius, texture, smoothness, etc.

Target column: diagnosis (B = Benign, M = Malignant → mapped to 0/1).

🛠️ Steps Performed:

Load data using pandas.

Clean non-numeric data and map target labels.

Drop unnecessary columns (like id).

Split data into features (X) and target (y).

Train/test split (80/20) using train_test_split.

Scale features using StandardScaler.

Train SVM models:

Linear kernel

RBF kernel

Evaluate accuracy and print classification reports.

📦 Libraries Used:

pandas

numpy

matplotlib

scikit-learn (SVC, train_test_split, StandardScaler, accuracy_score, classification_report)

🚀 How to Run

Make sure you have:

Python installed

Jupyter Notebook or JupyterLab installed

Install required libraries:

bash
Copy
Edit
pip install pandas numpy matplotlib scikit-learn
Run the notebook:

bash
Copy
Edit
jupyter notebook task7_Breast_cancer_SVM.ipynb

📈 Outputs:

Accuracy scores for linear and RBF SVM models.

Classification reports (precision, recall, f1-score).

Plots (if implemented).

📌 Notes:

You need the breast-cancer.csv file in the same directory.

Hyperparameters (C, gamma) can be tuned for better performance.
