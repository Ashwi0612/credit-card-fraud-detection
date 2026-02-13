---

# **🚨 Credit Card Fraud Detection**

---

## **Description**

This project is a **Credit Card Fraud Detection system** that identifies fraudulent transactions using machine learning techniques. It analyzes transaction data to predict whether a transaction is **legitimate** or **fraudulent**, helping banks and financial institutions minimize fraud losses.

---

##  **Dataset**

The project uses the **Credit Card Fraud Detection dataset** from Kaggle:
[https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

---

##  **Features**

* Detects fraudulent credit card transactions with **high accuracy**.
* Implements **data preprocessing**, **feature scaling**, and **machine learning models**.
* Generates performance metrics like **accuracy, precision, recall, and F1-score**.
* Can be extended to **real-time transaction monitoring**.

---

## **Installation**

1. Clone the repository:

```bash
git clone https://github.com/Ashwi0612/credit-card-fraud-detection
cd <your-project-folder>
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Download the dataset from Kaggle and place it in the project folder.

---

## **Usage**

1. Run the main script:

```bash
python main.py
```

2. The system will train the model and output predictions for test transactions.
3. View the results in the console or in the generated output file (if applicable).

---

## **Sample Output**

* Example prediction:

```
Transaction ID: 123456789
Prediction: Fraudulent 
Probability: 0.92
```

* Example metrics after model training:

```
Accuracy: 99.85%
Precision: 92.3%
Recall: 88.7%
F1-Score: 90.5%
```

---

## **License**

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---
