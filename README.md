# UPI Fraud Detection Using Random Forest Algorithm

## Overview

UPI (Unified Payments Interface) has revolutionized digital payments in India by enabling fast and secure transactions. However, the rapid increase in digital transactions has also led to a rise in fraudulent activities.

This project uses Machine Learning techniques to detect fraudulent UPI transactions. The system analyzes historical transaction data, preprocesses it, extracts meaningful features, and trains classification models to identify whether a transaction is fraudulent or legitimate.

Among the evaluated models, the **Random Forest Classifier** demonstrated better performance due to its high accuracy and robustness.

---

## Features

- Detects fraudulent UPI transactions
- Data preprocessing and feature engineering
- Exploratory Data Analysis (EDA)
- Decision Tree and Random Forest implementation
- Model evaluation using multiple performance metrics
- Easy to understand and scalable architecture

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Machine Learning Algorithms

- Decision Tree Classifier
- Random Forest Classifier

---

## Dataset

The dataset contains UPI transaction details, including:

- Transaction Time
- Customer Age
- Amount
- Merchant Category
- Location
- Payment Gateway
- Transaction Type
- Year
- Month
- Fraud Label (Target)

---

## Project Workflow

```
Dataset Collection
        │
        ▼
Data Preprocessing
        │
        ▼
Feature Engineering
        │
        ▼
Train-Test Split
        │
        ▼
Model Training
(Decision Tree & Random Forest)
        │
        ▼
Prediction
        │
        ▼
Performance Evaluation
```

---

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## Project Structure

```
UPI-Fraud-Detection/
│
├── dataset/
│   └── upi_transactions.csv
│
├── notebooks/
│   └── UPI_Fraud_Detection.ipynb
│
├── models/
│   └── random_forest_model.pkl
│
├── images/
│
├── requirements.txt
├── README.md
└── app.py (Optional)
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/UPI-Fraud-Detection.git
```

Move into the project folder

```bash
cd UPI-Fraud-Detection
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook or Python script

```bash
jupyter notebook
```

or

```bash
python app.py
```

---

## Results

- Successfully detects fraudulent UPI transactions.
- Random Forest outperformed the Decision Tree model.
- Achieved high prediction accuracy with better generalization.
- Suitable for real-time fraud detection applications.

---

## Future Enhancements

- Hyperparameter tuning using Grid Search
- Feature importance analysis
- Integration with XGBoost or LightGBM
- Real-time fraud detection system
- Flask/Django web application
- Cloud deployment (AWS/Azure)

---

## Applications

- Digital Payment Security
- Banking Systems
- Financial Institutions
- FinTech Companies
- Online Payment Platforms

---

## Authors

- **Vankayalapati Nikhita**
- Tunuguntla Gouri Niteesha
- Peravali Veda Sai
- Pitta Vyshnavi

Department of CSE (Artificial Intelligence & Machine Learning)

Seshadri Rao Gudlavalleru Engineering College

---

## License

This project is developed for academic and educational purposes.

---

## Acknowledgements

- Jawaharlal Nehru Technological University Kakinada (JNTUK)
- Seshadri Rao Gudlavalleru Engineering College
- Department of CSE (AI & ML)
