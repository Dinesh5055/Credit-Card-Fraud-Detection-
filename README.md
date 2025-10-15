# 💳 Credit Card Fraud Detection using Machine Learning

📘 Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning. The dataset is highly imbalanced, so advanced resampling techniques like SMOTE were used to balance the classes. The model was trained using a Random Forest Classifier, achieving high accuracy and recall on fraud detection.

⚙️ Tech Stack

- Languages: Python

- Libraries: NumPy, Pandas, Scikit-learn, imbalanced-learn, Seaborn, Matplotlib

- Techniques: EDA, Data Balancing (SMOTE), Random Forest Classification, Model Evaluation


🧠 Project Workflow

1.Data Loading & Exploration

  - Loaded the dataset (creditcard-dataset.csv) and analyzed feature distributions.

  - Visualized class imbalance between fraudulent and non-fraudulent transactions using Seaborn plots.

2.Data Preprocessing

  - Checked and handled missing values.

  - Separated features (X) and target (y).

  - Split data into training (80%) and testing (20%) sets.

3.Handling Class Imbalance

  - Applied SMOTE (Synthetic Minority Oversampling Technique) to oversample minority class and reduce model bias.

4.Model Training

  - Trained a Random Forest Classifier on the balanced dataset.

  - Tuned hyperparameters for improved generalization.

5.Model Evaluation

  - Evaluated model performance using Accuracy, F1-Score, and Confusion Matrix.

  - Achieved 98% accuracy and significant recall improvement for the fraud class.


📊 Results

|       Metric      | Before SMOTE | After SMOTE |
| :---------------: | :----------: | :---------: |
|      Accuracy     |      96%     |   **98%**   |
|   Recall (Fraud)  |     0.24     |   **0.96**  |
| Precision (Fraud) |     0.91     |   **0.95**  |

The model achieved strong recall after balancing the dataset, minimizing false negatives in fraud detection.



📈 Visualization Samples

 - Fraud vs Non-Fraud Transaction Distribution

 - Confusion Matrix of Model Predictions

 - Feature Importance Plot (Random Forest)


🧾 Key Learnings

 - Importance of handling class imbalance in real-world data.

 - Usage of SMOTE for improving minority class prediction.

 - Model interpretability through feature importance and evaluation metrics.
