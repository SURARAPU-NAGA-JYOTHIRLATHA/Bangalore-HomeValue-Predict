# 🏡 Bangalore House Price Prediction

This project predicts house prices in Bangalore using machine learning. It includes data preprocessing, exploratory data analysis (EDA), model training, and serialization for deployment.

---

## 📊 Dataset Overview

The dataset (`bangalore house prices.csv`) contains Bangalore housing listings with the following columns:

| Column        | Description                                      |
|---------------|--------------------------------------------------|
| `area_type`   | Type of area (e.g., Super built-up Area, Plot)  |
| `availability`| Availability status (e.g., Ready To Move)       |
| `location`    | Area/location in Bangalore                      |
| `size`        | Number of bedrooms (e.g., 2 BHK, 4 Bedroom)     |
| `society`     | Name of the society or community                |
| `total_sqft`  | Total area in square feet                       |
| `bath`        | Number of bathrooms                             |
| `balcony`     | Number of balconies                             |
| `price`       | Price in lakhs (1 lakh = ₹100,000 INR)          |

---

## 🧠 Machine Learning Model

- **Model Type**: Linear Regression  
- **Goal**: Predict house price based on area, location, size, and other features  
- **Libraries Used**: `pandas`, `numpy`, `matplotlib`, `sklearn`, `pickle`, `json`

### Key Steps:
- Clean and preprocess data (handle missing values, encode categories, convert sqft)
- Feature engineering (convert size to number of bedrooms)
- One-hot encoding for location
- Outlier removal and dimension reduction
- Train-test split and model evaluation
- Model serialization with `.pickle`

---

## 📒 Notebook Workflow

`bangalore house prices.ipynb` contains:
1. **Exploratory Data Analysis (EDA)**  
2. **Data Cleaning and Transformation**  
3. **Feature Engineering**  
4. **Model Building (Linear Regression)**  
5. **Model Evaluation**  
6. **Exporting Model and Column Metadata**




