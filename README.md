# CNN-Apriori-Evaluation-Validation-FDTP


# Food Delivery Time Prediction

## 📌 Overview
This project predicts whether a food delivery will be "Fast" (≤45 minutes) or "Delayed" using machine learning models.

## 🛠️ Requirements
- Python 3.x
- Libraries: 
  ```
  pandas numpy matplotlib seaborn scikit-learn torch haversine
  ```
  Install with:
  ```
  pip install pandas numpy matplotlib seaborn scikit-learn torch haversine
  ```

## 📂 Files
- `Food_Delivery_Time_Prediction.csv` - Dataset file
- Jupyter Notebook with the code

## 🚀 How to Run
1. Place the CSV file in the same folder as the notebook
2. Run the notebook cells one by one:
   - First cell: Load and check data
   - Second cell: Preprocess data
   - Third cell: Feature engineering
   - Fourth cell: Train models
   - Fifth cell: CNN model training
   - Sixth cell: Evaluate results

## 📊 Models Used
1. Logistic Regression
2. Random Forest
3. CNN (PyTorch)

## 📈 Results
The models will show:
- Accuracy scores
- Training graphs
- Confusion matrices
- ROC curves

## ⚠️ Note
The CNN model requires PyTorch. If you can't use PyTorch, focus on the Logistic Regression and Random Forest models.
