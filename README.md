# Bankruptcy Prediction

A machine learning project focused on identifying companies at risk of bankruptcy using financial data.

## Project Overview

The goal is to build a classification model that identifies potentially bankrupt companies. Since bankruptcies are relatively rare, the project focuses on class imbalance and the ability to detect the minority class.

## Dataset

The project uses the `1year.arff` dataset, which contains financial attributes for bankruptcy prediction.

The target variable indicates whether a company went bankrupt.

## Methods

- Data loading and preprocessing
- Handling missing values
- Feature scaling
- Logistic Regression
- L1 regularization
- Evaluation on an imbalanced classification task
- Precision, recall, and other classification metrics

## Results

The model achieved a recall of approximately **0.70** for the bankruptcy class and a precision of approximately **0.08**.

This means the model identified around 70% of bankrupt companies in the evaluated data, but only around 8% of its bankruptcy predictions were correct. The results illustrate the difficulty of detecting rare events in an imbalanced dataset.

## Project Structure

```text
bankruptcy-classification/
├── bankruptcy_risk.ipynb
├── 1year.arff
└── README.md
```

## Installation and Usage

1. Clone or download this repository.
2. Install the required dependencies:

```bash
pip install numpy pandas scipy scikit-learn matplotlib seaborn jupyter
```

3. Make sure `1year.arff` is in the same directory as the notebook.
4. Start Jupyter Notebook:

```bash
jupyter notebook bankruptcy_risk.ipynb
```

5. Run the notebook cells sequentially.

## Technologies

- Python
- pandas
- NumPy
- SciPy
- scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook