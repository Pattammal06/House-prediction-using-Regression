#  House Price Prediction Using Regression

##  Project Overview

This project predicts house prices using Machine Learning Regression techniques. The model is trained on housing-related features such as area, number of bedrooms, bathrooms, parking spaces, and other property characteristics to estimate the house price accurately.

The project demonstrates the complete Machine Learning workflow including data preprocessing, exploratory data analysis (EDA), model training, prediction, and evaluation.

---

##  Objectives

- Predict house prices using regression algorithms.
- Analyze the factors affecting house prices.
- Evaluate model performance using regression metrics.
- Visualize relationships between features and target values.

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

##  Dataset

The dataset contains various housing attributes such as:

- Area
- Bedrooms
- Bathrooms
- Stories
- Parking
- Main Road Access
- Guest Room Availability
- Basement
- Air Conditioning
- Furnishing Status
- House Price

---

##  Project Workflow

### 1. Import Required Libraries
Load all necessary Python libraries for data analysis and machine learning.

```
import numpy as np
import pandas as pd
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split
from sklearn.metrics import mean_absolute_error,mean_squared_error,root_mean_squared_error,r2_score
import matplotlib.pyplot as plt
import seaborn as sns

```

### 2. Load Dataset
Read the housing dataset using Pandas.

### 3. Data Preprocessing
- Check missing values
- Remove duplicates
- Handle categorical variables
- Feature encoding
- Data cleaning

### 4. Exploratory Data Analysis (EDA)
- Dataset information
- Statistical summary
- Correlation analysis
- Data visualization

### 5. Feature Selection
Select relevant features affecting house prices.

### 6. Train-Test Split
Split data into:
- Training Set (80%)
- Testing Set (20%)

### 7. Model Training
Train a Regression model using the training data.

### 8. Prediction
Predict house prices for test data.

### 9. Model Evaluation
Evaluate performance using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

##  Visualizations

The project includes:

- Correlation Heatmap
- Scatter Plots
- Distribution Plots
- Regression Analysis Graphs

## Simple Linear Regression :

<img width="467" height="393" alt="image" src="https://github.com/user-attachments/assets/7a11a500-b75d-4a42-83d9-4ec19acf49a5" />

<img width="540" height="470" alt="image" src="https://github.com/user-attachments/assets/4ff1a105-f04e-4642-8755-2b4ad75083cf" />


## Multi Linear Regression :

<img width="562" height="470" alt="image" src="https://github.com/user-attachments/assets/81b1ebe2-e719-49f6-aa25-81e776cf28c8" />

<img width="695" height="470" alt="image" src="https://github.com/user-attachments/assets/55667a42-c957-4b1c-9caa-1dccb07ff96a" />

<img width="463" height="470" alt="image" src="https://github.com/user-attachments/assets/59182ebb-b10a-4488-9f81-1453ffe3ef7f" />

<img width="405" height="427" alt="image" src="https://github.com/user-attachments/assets/2b16d507-8533-4a4b-a4f1-f5b877e10d65" />


---

##  How to Run

### Clone the Repository

```bash
git clone https://github.com/yourusername/House-Price-Prediction-Using-Regression.git
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

### Run the Project

```bash
House_Prediction_using_Regression.ipynb
```

---

## 📈 Results

The regression model successfully predicts house prices based on housing features and achieves reliable performance on the test dataset.

---

## 🔮 Future Improvements

- Hyperparameter Tuning
- Feature Engineering
- Multiple Regression Models Comparison
- Deployment using Flask or Streamlit
- Real-Time House Price Prediction Web App

---

## 👩‍💻 Author

**Pattammal M**

B.E. Computer Science and Engineering (AIML)

---

## ⭐ GitHub

If you found this project useful, please give it a ⭐ on GitHub.
