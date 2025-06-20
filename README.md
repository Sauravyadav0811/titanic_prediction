# 🚢 Titanic Survival Prediction with Machine Learning

This project uses machine learning to predict whether a passenger survived the Titanic shipwreck, based on features like age, sex, class, family size, and fare paid. It includes full EDA, feature engineering, model training and evaluation, and a GUI using Gradio.

---

## 📌 Project Highlights

- ✅ Exploratory Data Analysis (EDA)
- ✅ Feature Engineering (Title, Family Size, IsAlone, etc.)
- ✅ Handling Missing Values
- ✅ Model Training (Random Forest, Logistic Regression, Decision Tree, KNN)
- ✅ Model Comparison & Evaluation
- ✅ Confusion Matrix, Accuracy, Precision, Recall, F1 Score
- ✅ Gradio GUI to predict survival from user input
- ✅ Submission ready for Kaggle Titanic competition

---

## 📂 Project Structure

```

📁 titanic-survival-prediction/
├── train.csv                     # Original training dataset
├── test.csv                      # Original test dataset
├── titanic\_random\_forest\_model.pkl  # Trained model
├── submission.csv               # Submission file for Kaggle
├── titanic\_gui.py               # Gradio GUI app
├── README.md                    # Project documentation
└── requirements.txt             # Libraries to install

````

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/titanic-survival-prediction.git
cd titanic-survival-prediction
````

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch the Gradio GUI

```bash
python titanic_gui.py
```

The GUI will open in your browser. Fill in passenger details to see if they would survive! 🎯

---

## 📊 Machine Learning Models Used

| Model               | Status          |
| ------------------- | --------------- |
| Random Forest       | ✅ Best accuracy |
| Logistic Regression | ✅ Tested        |
| Decision Tree       | ✅ Tested        |
| K-Nearest Neighbors | ✅ Tested        |

---

## 🧠 Feature Engineering Performed

* `Title` extracted from `Name`
* `FamilySize` = `SibSp` + `Parch` + 1
* `IsAlone` based on `FamilySize`
* Age binning (optional)
* Label Encoding and One-Hot Encoding
* Handling missing `Age`, `Embarked`, and `Fare`

---

## 💻 Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* Gradio

---

## 🧪 Kaggle Compatibility

This project is fully compatible with the [Kaggle Titanic Machine Learning Challenge](https://www.kaggle.com/c/titanic).

---

