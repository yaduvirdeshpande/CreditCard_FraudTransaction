# CreditCard_FraudTransaction

This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques.

## Dataset Information

The dataset contains credit card transactions made by European cardholders.

- Total Transactions: 284,807
- Features: 31
- Target Column: `Class`
    - 0 → Normal Transaction
    - 1 → Fraud Transaction

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Scaling
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Fraud Prediction

## Dataset Columns

- Time
- V1 to V28
- Amount
- Class

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/CreditCard_FraudTransaction.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Run the Project

```bash
python app.py
```

or

```bash
jupyter notebook
```

## Machine Learning Models

- Logistic Regression
- Random Forest
- Decision Tree
- XGBoost (Optional)

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Project Structure

```text
CreditCard_FraudTransaction/
│
├── data/
├── notebooks/
├── models/
├── app.py
├── requirements.txt
└── README.md
```

## Future Improvements

- Deploy using Flask or Streamlit
- Real-time fraud detection
- Hyperparameter tuning

## Author

Your Name

## License

This project is open-source and available under the MIT License.
