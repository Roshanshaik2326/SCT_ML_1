# 🏠 House Price Prediction using Linear Regression

## 📌 Overview
This project uses a Linear Regression model to predict the price of a house based on:

- 📏 Square footage (area of the house)  
- 🛏️ Number of bedrooms  
- 🛁 Number of bathrooms  

The goal is to find a relationship between these features and the house price using past data.

The dataset used for this task is from the **[Kaggle House Prices Competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)**.

---

## 🛠️ Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📈 Workflow

1. **Data Loading**  
   Loaded `train.csv` containing structured housing data.

2. **Data Preprocessing**  
   Selected key features (`GrLivArea`, `BedroomAbvGr`, `FullBath`) and target (`SalePrice`).

3. **Train-Test Split**  
   Used `train_test_split` to divide data (80% train, 20% test).

4. **Model Training**  
   Trained a `LinearRegression` model on training data.

5. **Model Evaluation**  
   Evaluated using:
   - Mean Squared Error (MSE)
   - R² Score

6. **Visualization**  
   Plotted feature relationships using Seaborn and Matplotlib.

## 📊 Results
- The model successfully learned the relationship between the input features and house prices.
- Performance metrics such as **R² score** and **MSE** indicate good prediction capability for a basic regression model.# 🏠 House Price Prediction using Linear Regression

## 📌 Overview
This project uses a Linear Regression model to predict the price of a house based on:

- 📏 Square footage (area of the house)  
- 🛏️ Number of bedrooms  
- 🛁 Number of bathrooms  

The goal is to find a relationship between these features and the house price using past data.

The dataset used for this task is from the **[Kaggle House Prices Competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)**.

---

## 🛠️ Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📈 Workflow

1. **Data Loading**  
   Loaded `train.csv` containing structured housing data.

2. **Data Preprocessing**  
   Selected key features (`GrLivArea`, `BedroomAbvGr`, `FullBath`) and target (`SalePrice`).

3. **Train-Test Split**  
   Used `train_test_split` to divide data (80% train, 20% test).

4. **Model Training**  
   Trained a `LinearRegression` model on training data.

5. **Model Evaluation**  
   Evaluated using:
   - Mean Squared Error (MSE)
   - R² Score

6. **Visualization**  
   Plotted feature relationships using Seaborn and Matplotlib.

## 📊 Results
- The model successfully learned the relationship between the input features and house prices.
- Performance metrics such as **R² score** and **MSE** indicate good prediction capability for a basic regression model.
