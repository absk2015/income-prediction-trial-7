# 📊 Income Prediction using Census Demographics Data

> A beginner-friendly Machine Learning project built as part of a Data Science course.

---

## 🎯 Objective

Predict whether a person earns **more than $50,000/year** based on demographic features such as age, education, occupation, marital status, and more.

This is a **binary classification** problem using real-world U.S. census data.

---

## 📂 Dataset

| Property | Detail |
|----------|--------|
| **Name** | Adult Census Income Dataset |
| **Source** | UCI Machine Learning Repository |
| **Link** | https://archive.ics.uci.edu/ml/datasets/adult |
| **Rows** | ~48,000 individuals |
| **Target** | `income` → `<=50K` (0) or `>50K` (1) |

**Features used:** age, workclass, education, marital status, occupation, relationship, race, gender, capital gain/loss, hours per week, native country.

---

## 🛠️ Tech Stack

- **Language:** Python 3
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
- **Environment:** Jupyter Notebook

---

## 🧠 Models Trained

| Model | Description |
|-------|-------------|
| **Logistic Regression** | Linear baseline classifier |
| **Decision Tree** | Tree-based non-linear classifier |

---

## 📈 Results

| Model | Accuracy | F1-Score |
|-------|----------|----------|
| Logistic Regression | ~82% | ~0.65 |
| Decision Tree | ~85% | ~0.68 |

---

## 📁 Project Structure

```
📦 income-prediction-project
 ┣ 📓 income_prediction_project.ipynb   ← Main Jupyter Notebook
 ┗ 📄 README.md                         ← Project documentation
```

---

## 🚀 How to Run

1. **Clone this repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/income-prediction-project.git
   cd income-prediction-project
   ```

2. **Install dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook income_prediction_project.ipynb
   ```

4. **Run all cells** — the dataset is loaded automatically from the internet (no manual download needed).

---

## 📌 Key Insights

- **Education** and **age** are the strongest predictors of income.
- People working more **hours per week** generally earn more.
- **Capital gain** is a highly discriminating feature.

---

## 📝 Course Info

- **Course:** Data Science  
- **Project Type:** ML Model Training  
- **Domain:** Social / Demographics

---

*Dataset courtesy of UCI Machine Learning Repository.*
