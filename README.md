# 🏠 Boston Housing Price Prediction using Multiple Linear Regression

## 📌 Project Overview

This project builds a **Multiple Linear Regression model** to predict housing prices based on various property and neighborhood features. It helps understand how different factors influence house values.

---

## 📂 Dataset

* Dataset: Boston Housing Dataset
* Source: Kaggle
* Features used:

  * RM → Average number of rooms
  * LSTAT → % lower status population
  * PTRATIO → Pupil-teacher ratio
  * INDUS → Non-retail business acres
  * NOX → Nitric oxide concentration
  * AGE → Old houses proportion
* Target:

  * MEDV → Median house price

---

## ⚙️ Technologies Used

* Python 🐍
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🔄 Workflow

### 1. Data Loading

* Dataset loaded using pandas.

### 2. Data Exploration

* Checked missing values and statistics
* Used correlation heatmap for feature relationships

### 3. Data Preparation

* Selected important features
* Handled missing values using mean
* Split data (80% training, 20% testing)

### 4. Model Building

* Algorithm: Multiple Linear Regression

### 5. Model Evaluation

* Mean Squared Error (MSE)
* R² Score

### 6. Visualization

* Correlation heatmap
* Actual vs Predicted price scatter plot

---

## 📈 Results

* RM (rooms) positively affects house prices
* LSTAT negatively impacts prices
* NOX and PTRATIO also influence prices
* Model shows good prediction performance

---

## 📊 Sample Output

```
MSE: <value>
R2: <value>
```

---

## ▶️ How to Run

1. Clone the repository:

```
git clone https://github.com/your-username/boston-housing-prediction.git
```

2. Navigate to the folder:

```
cd boston-housing-prediction
```

3. Install dependencies:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Run:

```
python main.py
```

---

## 📌 Future Improvements

* Use advanced models (Random Forest, XGBoost)
* Feature scaling and normalization
* Hyperparameter tuning
* Deploy as a web application

---

## 🤝 Contributing

Feel free to fork and improve this project.

---

## 📜 License

This project is open-source under the MIT License.
