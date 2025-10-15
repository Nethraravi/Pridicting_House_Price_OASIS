# 🏠 House Price Prediction using Linear Regression  


## 📘 Project Overview  
This project aims to **predict house prices** using **Linear Regression**, a fundamental yet powerful machine learning algorithm.  
The goal was to build a **data-driven model** and an **interactive Power BI dashboard** to understand how various factors — like area, bedrooms, furnishing status, and amenities — influence house prices.


## 🧠 Objectives  
- Analyze and clean housing data  
- Identify key features affecting house prices  
- Build and evaluate a Linear Regression model  
- Visualize trends and insights with Power BI  


## 🧩 Dataset  
The dataset used for this project is `Housing.csv`, containing attributes such as:  
- `area` — total area of the house  
- `bedrooms`, `bathrooms`, `stories` — property details  
- `mainroad`, `guestroom`, `airconditioning` — amenities indicators  
- `furnishingstatus` — furnished, semi-furnished, or unfurnished  
- `price` — target variable (house price)  


## ⚙️ Tools & Technologies  
| Tool / Library | Purpose |
|----------------|----------|
| **Python** | Data analysis & modeling |
| **Pandas / NumPy** | Data wrangling & cleaning |
| **Matplotlib / Seaborn** | Data visualization |
| **Scikit-learn** | Linear Regression model |
| **Power BI** | Dashboard & KPI visualization |
| **DAX** | Custom measures for business insights |


## 📈 Project Workflow  

### 1️⃣ Data Collection  
Loaded the dataset (`Housing.csv`) into a Pandas DataFrame and verified the schema.

### 2️⃣ Data Exploration & Cleaning  
- Checked for missing values and handled them using median imputation  
- Performed outlier detection and correlation analysis  
- Created visualizations for numerical and categorical features  

### 3️⃣ Feature Selection  
- Identified key drivers using correlation & feature importance  
- Selected optimal predictors for model training  

### 4️⃣ Model Training  
Implemented **Linear Regression** using Scikit-learn:  
```python
