# Credit-Card-Fraud-Detection
This project aims to build a machine learning model to detect fraudulent credit card transactions. The dataset used for this project contains transaction details, and the model is trained to distinguish between legitimate and fraudulent transactions.

# Dataset
The dataset contains the following columns:

Time: Number of seconds elapsed between this transaction and the first transaction in the dataset.
V1, V2, ..., V28: Principal components obtained with PCA.
Amount: Transaction amount.
Class: Target variable (0 for legitimate transactions, 1 for fraudulent transactions).
📂 Note: Ensure the dataset file is in the project directory. If the dataset is public, you can provide the download link here.

# Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Shreyabhelekar/Credit-Card-Fraud-Detection.git
   cd Credit-Card-Fraud-Detection
   ```
   
2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

# Usage
1. Ensure you have the dataset file in the project directory.

2. Run the Jupyter Notebook or Python script to train and evaluate the model:

```bash
jupyter notebook Credit_Card_Fraud_Detection.ipynb
```
or
```bash
python credit_card_fraud_detection.py
```

# Model Training
1. Load and explore the dataset.
2. Preprocess the data, handle missing values, and balance the dataset.
3. Split the data into training and testing sets.
4. Train a logistic regression model using the training data.

# Model Evaluation
Evaluate the model on both training and testing datasets.

Calculate accuracy scores and other performance metrics.

# Visualization
Visualize the distribution of classes before and after under-sampling.

Analyze feature distributions for normal and fraudulent transactions.

Visualize model performance metrics.

# Results
The model achieved an accuracy of 94% on the training set and Y% on the test set.

Key insights and findings from the data and model are documented in the notebook.
