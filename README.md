Student Performance Prediction (Pass/Fail)

This project implements an end-to-end machine learning pipeline to predict whether a student passes or fails based on their final exam marks.


---

📌 Project Overview

This repository contains:

Data preprocessing and cleaning

Handling mixed-type and inconsistent values

Encoding categorical features

Feature scaling and selection

Model training using Random Forest

Evaluation with accuracy, confusion matrix, and cross-validation



---

📁 Dataset

Assumes a dataset marks_final.csv with features like student scores and a target column Pass/Fail indicating whether the student passed.


---

⚙️ Technologies Used

Python

pandas, numpy

scikit-learn

seaborn, matplotlib



---

🚀 How to Run

# Install dependencies
pip install -r requirements.txt

# Run the pipeline
python main.py


---

🧠 Model Pipeline

1. Load and inspect data


2. Drop irrelevant columns (e.g., Student_ID)


3. Handle missing and inconsistent values


4. Identify and transform mixed-type columns


5. Encode categorical columns (OneHotEncoder)


6. Scale numerical features (StandardScaler)


7. Train/test split with stratification


8. Train Random Forest classifier


9. Evaluate using accuracy, confusion matrix, and classification report




---

📊 Evaluation Metrics

Accuracy Score

Confusion Matrix

Cross-validation (k=5)



---

📈 Example Output

Accuracy: 0.91
Confusion Matrix:
[[45 5]
 [ 3 47]]


---

✅ Future Improvements

Hyperparameter tuning with GridSearchCV

SHAP or ELI5 for model explainability

Export model with joblib or pickle for deployment



---

🤝 Contributing

Feel free to fork and open pull requests!


---

📄 License

MIT License
