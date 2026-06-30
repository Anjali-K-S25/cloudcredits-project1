# House Price Prediction Using Linear Regression

## Project Overview

This project builds a Machine Learning model to predict house prices using the **Linear Regression** algorithm. The model learns the relationship between various housing features and the target house price, allowing it to estimate prices for new houses.

---

## Objective

The objective of this project is to predict house prices based on housing characteristics such as income, house age, number of rooms, population, occupancy, and geographical location.

---

## Dataset

This project uses the **California Housing Dataset** provided by Scikit-learn (recommended replacement for the deprecated Boston Housing Dataset).

### Features

* **MedInc** – Median income in the area
* **HouseAge** – Average age of houses
* **AveRooms** – Average number of rooms
* **AveBedrms** – Average number of bedrooms
* **Population** – Population in the area
* **AveOccup** – Average occupancy per household
* **Latitude** – Geographic latitude
* **Longitude** – Geographic longitude

### Target Variable

* **MedHouseVal** – Median house value

---

## Machine Learning Algorithm

* Linear Regression

Linear Regression predicts continuous numerical values by finding the best-fit linear relationship between the input features and the target variable.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib

---

## Project Workflow

1. Import required libraries.
2. Load the California Housing dataset.
3. Perform data preprocessing.
4. Conduct Exploratory Data Analysis (EDA).
5. Select input features and target variable.
6. Split the dataset into training and testing sets.
7. Train a Linear Regression model.
8. Predict house prices.
9. Evaluate the model using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score.
10. Save the trained model using Joblib.

---

## Evaluation Metrics

The model is evaluated using the following metrics:

* **Mean Squared Error (MSE)** – Measures the average squared prediction error.
* **Root Mean Squared Error (RMSE)** – Represents the prediction error in the same unit as the target variable.
* **R² Score** – Indicates how well the model explains the variance in house prices.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/house-price-prediction.git
```

Move into the project directory:

```bash
cd house-price-prediction
```

Install the required dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

---

## Running the Project

Run the Python script:

```bash
python house_price_prediction.py
```

The program will:

* Load the dataset
* Display dataset information
* Perform EDA
* Train the Linear Regression model
* Predict house prices
* Evaluate the model
* Save the trained model as `house_price_model.pkl`

---

## Sample Output

```
Model Trained Successfully

Mean Squared Error : 0.56

Root Mean Squared Error : 0.75

R² Score : 0.78

Model Saved Successfully
```

*(Actual values may vary depending on the dataset and environment.)*

---

## Future Improvements

* Apply feature scaling.
* Perform hyperparameter tuning.
* Compare multiple regression algorithms.
* Build a web application using Flask or Streamlit.
* Deploy the model to a cloud platform for real-time predictions.

---

## Learning Outcomes

After completing this project, you will understand:

* Regression problems in Machine Learning
* Data preprocessing techniques
* Exploratory Data Analysis (EDA)
* Feature selection
* Model training and testing
* Model evaluation using regression metrics
* Saving and loading trained Machine Learning models

---

## Author

**Anjali K S**
---

## License

This project is intended for educational and learning purposes. Feel free to use, modify, and extend it for academic or personal projects.
