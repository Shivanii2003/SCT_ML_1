# SCT_ML_1 - Machine Learning Task 1

## 📘 Task Overview
This task involves implementing a **Linear Regression** model using `scikit-learn` to predict house prices based on features such as square footage, number of bedrooms, and number of bathrooms.

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- scikit-learn

## 📂 Files Included
- `Task1.ipynb` - Jupyter notebook containing:
  - Dataset creation
  - Preprocessing
  - Model training
  - Evaluation and prediction

## 📊 Key Features
- Linear Regression from scratch using a small, structured housing dataset
- Model training and testing using `train_test_split`
- Evaluation using Mean Squared Error (MSE) and R² score
- Final prediction using new example input

## 🧠 What I Learned
- How to train and evaluate a regression model
- How different features (square footage, bedrooms, bathrooms) impact house price
- Interpreting model coefficients and intercept
- Making predictions on new/unseen data

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Shivanii2003/SCT_ML_1
   ```
2. Open the `Task1.ipynb` notebook using Jupyter or Google Colab.
3. Run all cells to view model training, prediction, and output.

## 📌 Example Output
```
Mean Squared Error: 625000000.00
R² Score: 0.95

Model Coefficients:
Square Foot Coefficient: 150.25
Bedrooms Coefficient: 5000.75
Bathrooms Coefficient: 8000.00
Intercept: 20000.00

Predicted Price for 2000 sq ft, 3 bedrooms, 2 bathrooms: $380,000.00
```
