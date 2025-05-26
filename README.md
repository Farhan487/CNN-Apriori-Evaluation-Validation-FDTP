# CNN-Apriori-Evaluation-Validation-FDTP

# Food Delivery Time Prediction Project

## 📋 Overview
This project predicts whether food deliveries will be "Fast" or "Delayed" based on factors like distance, weather, traffic, and delivery person experience. It helps restaurants and delivery services optimize their operations.

## 🛠️ Requirements
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

Install requirements:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## 🚀 How to Run
1. Place `Food_Delivery_Time_Prediction.csv` in the same folder
2. Run the Jupyter Notebook cells in order
3. View the results and visualizations after each step

## 🔍 What the Code Does

### 1️⃣ Data Preparation
- Converts delivery times to "Fast" or "Delayed" categories
- Calculates exact distances between locations using coordinates
- Creates new features like:
  - Time of day categories (Daytime/Rush Hour/Night)
  - Weather impact scores
  - Traffic impact scores

### 2️⃣ Machine Learning Model
- Uses a Random Forest classifier to predict delivery status
- Handles both numerical and categorical data automatically
- Evaluates model accuracy using multiple methods

### 3️⃣ Key Features
- Distance between restaurant and customer
- Weather conditions (Sunny/Cloudy/Rainy/Snowy)
- Traffic levels (Low/Medium/High)
- Delivery person experience
- Vehicle type
- Time of day

## 📊 Results
The model provides:
- Accuracy score (how often predictions are correct)
- Feature importance (which factors matter most)
- Confusion matrix (detailed breakdown of predictions)

## 💡 Insights
The analysis typically shows:
1. Distance is the most important factor in delivery time
2. Bad weather significantly increases delivery times
3. Experienced delivery persons complete orders faster
4. Rush hour and night deliveries take longer

## 📂 Files
- `Food_Delivery_Time_Prediction.csv`: The dataset
- `Delivery_Time_Prediction.ipynb`: Jupyter Notebook with the code

## 🤝 Recommendations for Delivery Services
1. Optimize delivery zones to reduce distances
2. Provide weather-appropriate gear for delivery staff
3. Schedule more staff during rush hours
4. Prioritize experienced staff for time-sensitive orders

