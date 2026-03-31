# 📘 Student Pass Prediction System

A simple machine learning project that predicts whether a student will **pass or fail** based on study habits and academic behavior using a **Decision Tree Classifier**.

---

## 🚀 Features

* Generates a synthetic dataset of student performance
* Uses key factors:

  * Hours studied
  * Attendance
  * Assignments completed
  * Class participation
* Trains a Decision Tree model
* Evaluates model performance with:

  * Accuracy score
  * Classification report
* Saves a visual representation of the decision tree

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## 📂 Project Structure

```
├── README.md
├── Student Pass Prediction System.py
├── Student Pass Prediction System.txt
```

---

## ⚙️ How It Works

1. **Dataset Creation**

   * Generates synthetic student data using NumPy
   * Defines passing criteria:

     * Total effort score > 22
     * Attendance > 65%

2. **Data Preparation**

   * Splits dataset into training and testing sets (80/20)

3. **Model Training**

   * Uses a Decision Tree Classifier (max depth = 3)

4. **Evaluation**

   * Predicts outcomes on test data
   * Displays accuracy and classification report

5. **Visualization**

   * Saves the decision tree as an image (`model_visualization.png`)

---

## ▶️ How to Run

### 1. Install dependencies

```
pip install pandas numpy matplotlib scikit-learn
```

### 2. Run the script

```
python "Student Pass Prediction System.py"
```

---

## 📊 Output

* Console output:

  * Sample dataset preview
  * Model accuracy
  * Classification report

* File generated:

  * `model_visualization.png` (Decision Tree diagram)

---

## 🎯 Use Case

This project demonstrates:

* Basic machine learning workflow
* Classification using decision trees
* Model evaluation techniques
* Data visualization for interpretability

---

## 🔮 Future Improvements

* Use real student datasets
* Add more features (e.g., exam scores)
* Try other models (Random Forest, Logistic Regression)
* Build a web interface using Flask or Streamlit
