# 🚗 Car Price Prediction 

## 📌 Business Problem
The automotive industry experiences dynamic pricing influenced by several factors such as engine type, fuel system, aspiration, and car body. This project applies Exploratory Data Analysis (EDA) and Machine Learning techniques to explore variables affecting car prices and to develop a model capable of predicting car prices based on vehicle features.

## 📊 Dataset Overview
The dataset contains multiple vehicle features, including performance metrics, body types, engine specifications, and risk indicators. The goal is to uncover patterns that impact price and to build an efficient prediction model.

## 🧾 Key Features
- **Numerical Features**: Car length, wheelbase, curb weight, horsepower, engine size, risk factor, etc.
- **Categorical Features**: Number of doors, aspiration type, fuel system, car body, engine type, etc.
- **Target Variable**: Car price

## 🔍 Key Analyses & Insights

### 🔸 Cylinder Count vs. Price
- Cars with more cylinders have significantly higher prices.
- 4-cylinder engines dominate budget segments.

### 🔸 Doors vs. Price (Diesel)
- Price doesn’t vary much by number of doors in diesel cars.
- Diesel 4-door cars cover both low-end and luxury models.

### 🔸 Engine Type Impact
- DOHC and OHCV engines are more expensive due to performance and durability.
- Rotor engines, though rare, are expensive due to uniqueness and design.

### 🔸 Fuel System & Aspiration
- Turbocharged gas engines have higher prices.
- MPFI fuel systems dominate high-end cars for efficiency and precision.

### 🔸 Car Body & Size
- Sedans and convertibles are pricier than hatchbacks and wagons.
- Longer cars and those with wider wheelbases tend to cost more.

### 📈 Correlation Analysis
- **Highly Correlated with Price**:
  - Engine Size (0.87)
  - Curb Weight (0.84)
  - Horsepower (0.81)
  - Car Length & Width (~0.76)

- **Inter-feature Correlation**:
  - More cylinders → bigger engine size & higher horsepower
  - Bigger engines → heavier and more powerful cars

## 🧪 Model Training & Results
- Engine-related variables were most predictive.
- Feature selection improved R² score.
- Fuel efficiency and door count were less useful for predictions.

## 🛠 Tools Used
- **Orange** – Visual machine learning workflow and model building
- **Python (Optional)** – For supplementary data handling and visualization
- **PowerPoint** – For assignment presentation


## 📌 Final Takeaways
- Engine specifications are the most critical price drivers.
- Aspiration and advanced fuel systems (e.g., MPFI, turbo) elevate car value.
- Physical dimensions like wheelbase and length correlate strongly with higher pricing.
- Simplifying the feature set boosted model accuracy without compromising performance.
