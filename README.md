# 🚢 Titanic Dataset Analysis with Python

This repository contains an end-to-end exploratory data analysis (EDA) of the **Titanic dataset**, a classic dataset used for binary classification tasks and data science practice. The project is built using **Python**, leveraging popular libraries like `pandas`, `seaborn`, and `matplotlib`.

---

## 📂 Dataset Source

The dataset is loaded directly from GitHub:

📎 **URL:** [Titanic CSV](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)

---

## 🧠 Project Overview

This project is structured around key data science steps:

### 1. Data Loading & Inspection
- Load the dataset using `pandas`
- View basic info with `.info()` and `.describe()`
- Identify missing values

### 2. Univariate Analysis
- Distribution of the target variable (`Survived`)
- Histogram analysis of passenger `Age`

### 3. Bivariate Analysis
- Survival rate by passenger class (`Pclass`)
- Boxplot comparison of `Age` vs `Survived`

### 4. Data Cleaning
- Impute missing values for `Age` and `Embarked`
- Drop `Cabin` due to excessive missing values

### 5. Correlation Analysis
- Heatmap to visualize correlation between numerical features

---

## 📊 Visual Examples

Here are some of the key visualizations generated in this analysis:

| Visualization         | Description                                    |
|-----------------------|------------------------------------------------|
| Survival Count        | Bar plot of survived vs. non-survived         |
| Age Distribution      | Histogram with KDE curve for passenger ages   |
| Survival by Class     | Count plot showing class-wise survival rates  |
| Age vs. Survival      | Boxplot comparing age distributions            |
| Correlation Matrix    | Heatmap showing correlations among numerical features |

---

## 📦 Technologies Used

- Python 3.x
- pandas
- seaborn
- matplotlib
- Jupyter Notebook (optional)

---

## 🚀 How to Run This Project

1. **Clone the repository:**
```bash
git clone https://github.com/your-username/titanic-eda.git
cd titanic-eda
```

---

## Install dependencies
```bash
pip install pandas seaborn matplotlib

```

---

## Run the analysis

```bash

jupyter notebook

```

---

## Feedback & Contributions

Have ideas or want to extend this project?
Feel free to fork this repo, submit pull requests, or open an issue!

---

##  License

This project is licensed under the **MIT License**.

---
