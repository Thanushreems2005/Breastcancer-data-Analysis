# Breastcancer-data-Analysis
This project implements a binary classifier to predict whether a breast cancer tumor is malignant or benign using logistic regression. The model is built using the Breast Cancer Wisconsin Dataset and achieves high accuracy and recall, making it useful for medical diagnostic assistance.

📂 Dataset
Source: Breast Cancer Wisconsin Dataset
Samples: 569
Features: 30
Labels:
0 = Malignant
1 = Benign

⚙️ Process
1.Data Loading
Loaded the dataset and split it into training (80%) and testing (20%) sets.
2.Preprocessing
Standardized all feature values for better model performance.
3.Model Training
Applied logistic regression to train the binary classification model.
4.Evaluation Metrics
Evaluated the model using:
>Confusion Matrix
>Precision
>Recall
>ROC-AUC Curve
5.Threshold Tuning
Experimented with classification thresholds from 0.3 to 0.7. The default threshold of 0.5 gave balanced performance.
6.Sigmoid Function Analysis
Visualized the sigmoid function to understand how raw outputs are converted into probabilities.

📊 Results
Precision: ~92%
Recall: ~99%
ROC-AUC Score: ~99%
The model demonstrated excellent performance in identifying benign tumors with very high recall, minimizing false negatives—a critical factor in medical diagnosis.

📁 Files
Breast-Cancer-Analysis.ipynb — Full implementation of model training, evaluation, and visualization.
README.md — Project overview and usage instructions.

🚀 Running the Project
To run the model:
bash
python Breast-Cancer-Analysis.ipynb
Ensure required libraries like scikit-learn, matplotlib, and numpy are installed.

🧠 Key Concepts
>Logistic Regression: A statistical model used for binary classification problems.
>Sigmoid Function: Maps real-valued input into [0,1] for probabilistic interpretation.
>Threshold Tuning: Helps adjust the trade-off between precision and recall.
>Evaluation Metrics: Essential for interpreting model effectiveness beyond raw accuracy.

📌 Conclusion
This project shows how logistic regression, when paired with proper preprocessing and evaluation, can be a powerful tool for medical data classification tasks. The approach balances simplicity, interpretability, and performance.
