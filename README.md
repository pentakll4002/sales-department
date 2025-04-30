# 🛒 Sales Department Analytics & Forecasting with PCA & ANN
This project analyzes and models sales data from a retail department using statistical visualization, PCA (Principal Component Analysis), and Artificial Neural Networks (ANN). The main objective is to reduce data complexity and predict sales performance across different stores.

## 📁 Dataset
- sales_train.csv: Contains historical sales transactions.

- stores.csv: Contains store-level metadata like store ID, type, and other characteristics.

## 🔧 Tools & Libraries
This project is built using the following Python libraries:

- NumPy – numerical computation

- Pandas – data manipulation and cleaning

- Matplotlib & Seaborn – data visualization

- Scikit-learn – PCA, preprocessing, and evaluation

- TensorFlow / Keras or PyTorch – building ANN models (you can specify which you used

## ⚙️ Project Workflow
1. Data Loading & Cleaning

  - Merge sales_train.csv and stores.csv

  - Handle missing values, outliers, and date formatting

2. Exploratory Data Analysis (EDA)

  - Visualize sales trends over time

  - Analyze store performance

  - Correlation analysis using heatmaps

3. Feature Engineering

  - Extract date features (month, year, etc.)

  - Encode categorical variables

4. Dimensionality Reduction

  - Apply PCA to reduce feature space and speed up model training

5. Model Building

  - Build an Artificial Neural Network (ANN) to predict sales

  - Train/test split and model evaluation

6. Model Evaluation

  - Metrics: MAE, RMSE, and accuracy (depending on regression or classification goal)

  - Visualize loss and accuracy trends

## 📊 Visualizations
- Time-series plots of sales

- Correlation heatmaps

- PCA variance ratio plots

- ANN training performance (loss/accuracy curves)

## 🚀 Getting Started
1. Clone the repository
```bash
git clone https://github.com/yourusername/sales-department.git
cd sales-department
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Run the project
```bash
python main.py
```
Make sure the CSV files are in the same directory or adjust the file paths accordingly.

## 🧠 Model Summary
- Dimensionality Reduction: PCA for compressing input features while retaining variance

- Prediction Model: Feed-forward ANN with multiple layers and dropout regularization

- Goal: Predict future sales or classify store performance

## 📎 Notes
- Suitable for forecasting sales trends or detecting high/low performing stores

- Can be extended to use time-series models (e.g., LSTM, ARIMA) in future





