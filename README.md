# Decision Tree vs Random Forest – Classification Analysis

This project performs a **comparative analysis of Decision Tree and Random Forest classifiers**
on a merged match dataset to predict match outcomes.

The notebook covers **data loading, preprocessing, model training, evaluation, and performance comparison**
using multiple classification metrics.

---

## 📌 Project Overview

- Merge match-level data with match results
- Perform exploratory data inspection
- Train and evaluate:
  - Decision Tree Classifier
  - Random Forest Classifier
- Compare model performance using standard metrics

---

## 📂 Dataset Description

Two CSV files are used:

- `Match_dataset.csv` – contains match-related features  
- `match_results.csv` – contains match results (Winner)

These datasets are merged using **Match_ID** to create the final modeling dataset.

---

## ⚙️ Workflow

1. **Data Loading**
   - Load CSV files using pandas
   - Merge datasets on `Match_ID`

2. **Data Exploration**
   - Shape, columns, and data types
   - Null value inspection

3. **Preprocessing**
   - Feature selection
   - Handling categorical variables
   - Train-test split

4. **Model Training**
   - Decision Tree Classifier
   - Random Forest Classifier

5. **Model Evaluation**
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion Matrix
   - ROC Curve

6. **Model Comparison**
   - Performance comparison between DT and RF

---

## 📊 Evaluation Metrics Used

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC Curve

These metrics help in understanding both overall performance and class-wise behavior.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📁 Project Structure

DecisionTree-vs-RandomForest/
│
├── DT_RF.ipynb
├── Match_dataset.csv
├── match_results.csv
├── requirements.txt
└── README.md

---

## 🚀 How to Run

1. Clone the repository
```bash
git clone https://github.com/your-username/DecisionTree-vs-RandomForest.git
```
Install dependencies

pip install -r requirements.txt


Open the notebook

jupyter notebook DT_RF.ipynb

📌 Conclusion

Random Forest generally performs better than a single Decision Tree by reducing overfitting
and improving generalization through ensemble learning.

This project demonstrates the practical advantage of ensemble models in classification tasks.

👤 Author

Devendra Kushwah
B.Tech | Machine Learning & Data Science Enthusiast

