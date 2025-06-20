# 🍷 Wine Classification Using Multinomial Naive Bayes

This project demonstrates how to classify different types of wine using the **Multinomial Naive Bayes** algorithm, a probabilistic machine learning model suitable for classification with discrete features.

---

## 📚 Project Overview

Wine classification is a popular task in the machine learning community. Using the **UCI Wine Dataset**, this project:

- Preprocesses the dataset
- Splits it into training and test sets
- Applies the **Multinomial Naive Bayes** algorithm
- Evaluates model performance using metrics such as accuracy and a confusion matrix

---

## 🧠 Algorithm: Multinomial Naive Bayes

Multinomial Naive Bayes is particularly effective for classification with discrete data (e.g., word counts in text classification). While it's less commonly used for continuous features like those in the wine dataset, it can still be applied by discretizing the features or transforming the data appropriately.

---

## 📁 Dataset

- **Source:** UCI Machine Learning Repository
- **Features:** 13 chemical attributes of wine
- **Classes:** 3 types of wine

---

## 🛠️ Technologies Used

- Python 3.x
- pandas
- scikit-learn
- matplotlib / seaborn (for visualization)

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/wine-classification-nb.git
cd wine-classification-nb
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the script

``` bash
jupyter naive-bayes.ipynb
```

## Results
-*Accuracy = 91.6*
-*Confusion Matrix as follow*
 [Confusion Matrix](output.png)
