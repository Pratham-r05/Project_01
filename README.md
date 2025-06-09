# Customer Churn Prediction

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)](https://www.tensorflow.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Predict customer churn using a deep learning model built with TensorFlow and Keras. This project provides an end-to-end pipeline for analyzing customer attributes, engineering features, training a model, and making predictions—all interactively demonstrated within a Jupyter notebook.

---

## 🚀 Project Overview

Customer churn prediction aims to identify customers who are likely to leave (churn) a business. By anticipating churn, companies can proactively engage at-risk users and improve retention.

**Key Steps:**
- Data loading and inspection
- Feature engineering (including one-hot encoding)
- Data scaling (StandardScaler)
- Model building with Keras (Dense, Dropout layers)
- Training and evaluation (metrics, confusion matrix, ROC curve)

> **Interactive Demo:**  
> See the Jupyter notebook: [Customer_Churn_Prediction.ipynb](Customer_Churn_Prediction.ipynb)

---

## 📊 Sample Data

The notebook uses the `Churn_Modelling.csv` dataset.  
Example features:
- `CreditScore`, `Geography`, `Gender`, `Age`, `Tenure`, `Balance`
- `NumOfProducts`, `HasCrCard`, `IsActiveMember`, `EstimatedSalary`
- Target: `Exited` (1 = churn, 0 = retained)

---

## 🛠️ Technologies & Libraries

- **Language:** Python 3.x
- **Data Manipulation:** numpy, pandas
- **Visualization:** seaborn, matplotlib
- **Deep Learning:** tensorflow, keras
    - Model: `Sequential`, `Dense`, `Dropout`
    - Optimization: `Adam`
    - Callbacks: `EarlyStopping`

---

## 📓 Usage

### 1. Installation

```bash
pip install numpy pandas seaborn matplotlib tensorflow
```

### 2. Running the Notebook

1. Download `Customer_Churn_Prediction.ipynb` and `Churn_Modelling.csv` to the same directory.
2. Launch Jupyter:

   ```bash
   jupyter notebook
   # or
   jupyter lab
   ```

3. Open the notebook and run cells sequentially.

### 3. Contributing

- Fork this repo
- Create a new branch (`git checkout -b feature-branch`)
- Make your changes
- Commit and push
- Open a pull request

---

## 🌟 Features

- **End-to-end pipeline:** Data cleaning → Feature engineering → Deep learning.
- **Interactive visualizations:** Data exploration and evaluation plots.
- **Easy to extend:** Modular code, well-commented.
- **No missing values:** Data integrity checks included.
- **Customizable architecture:** Quickly tune layers, activations, and callbacks.


---

## 🙏 Acknowledgments

- Dataset: [Kaggle - Churn Modelling Dataset](https://www.kaggle.com/datasets/adammaus/predicting-churn-for-bank-customers)
- TensorFlow & Keras documentation
- Community tutorials on customer churn prediction

---

## 🤔 FAQ

**Q: Can I use my own data?**  
A: Yes! Just format your CSV file with similar columns and update the data loading cell in the notebook.

**Q: How do I interpret the results?**  
A: The notebook explains model predictions with evaluation metrics and plots.

---

> _Feel free to open issues or contribute improvements!_
