# 🚢 Titanic Survival Prediction – Model Comparison

This project applies five different machine learning classification models on the classic **Titanic dataset** to predict passenger survival, and compares their performance.

## 📊 Dataset

The dataset used is the built-in Titanic dataset from Seaborn (`sns.load_dataset('titanic')`), which contains passenger information such as:

- `pclass` – Passenger class
- `sex`, `age`
- `sibsp`, `parch` – Family relations aboard
- `fare`, `embarked`
- `survived` – Target variable (0 = No, 1 = Yes)

## ⚙️ Workflow

1. Data loading and exploration
2. Data cleaning & preprocessing (handling missing values, encoding categorical features)
3. Feature scaling (for distance-based models)
4. Train-test split
5. Training and evaluating 5 classification models
6. Comparing accuracy, confusion matrix, and classification report for each

## 🤖 Models Used

| Model | Accuracy |
|---|---|
| Logistic Regression | 0.8034 |
| K-Nearest Neighbors (KNN) | 0.7753 |
| Naive Bayes | 0.7753 |
| Decision Tree | 0.7697 |
| **Support Vector Machine (SVM)** | **0.8258** ✅ |

**Best performing model:** SVM, with an accuracy of **82.58%**.

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (Logistic Regression, KNN, Naive Bayes, Decision Tree, SVM)

## 📁 Files

- `Titanic.ipynb` – Full notebook with data preprocessing, model training, and evaluation

## 🚀 How to Run

1. Clone this repository
2. Open `Titanic.ipynb` in Jupyter Notebook or Google Colab
3. Run all cells sequentially

## 📈 Evaluation Metrics

Each model was evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

## 📌 Conclusion

Among the five models tested, **SVM** achieved the highest accuracy, followed closely by **Logistic Regression**. Simpler models like Decision Tree and KNN performed relatively lower on this dataset.

---

*Created as a machine learning practice project on the Titanic dataset.*
