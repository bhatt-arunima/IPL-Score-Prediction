# 🏏 IPL Score Prediction using Deep Learning

This project uses deep learning to predict the final score of a team in an IPL (Indian Premier League) match based on live match data such as overs, runs, wickets, teams, and players. It leverages a neural network built with TensorFlow and Keras to provide accurate score predictions.

## 📌 Project Objective

To build a regression-based deep learning model that can forecast the final score of a batting team in a T20 cricket match using historical IPL data.

## 📂 Dataset

- Source: Kaggle / IPL dataset (2008–2017)
- Features used:
  - Batting team
  - Bowling team
  - Current runs, wickets
  - Overs completed
  - Striker and non-striker
  - Venue

## 🧠 Technologies Used

- Python
- Pandas, NumPy – Data Handling
- Matplotlib, Seaborn – Visualization
- Scikit-learn – Preprocessing
- TensorFlow / Keras – Deep Learning Model

## ⚙️ Workflow

1. **Data Cleaning & Preprocessing**
   - Removed irrelevant columns
   - Label encoding for categorical features
   - Normalized numerical values

2. **Model Building**
   - Sequential Neural Network
   - Dense layers with ReLU activation
   - Final output layer for score prediction
   - Loss Function: Mean Squared Error
   - Optimizer: Adam

3. **Evaluation**
   - Trained on historical data
   - Evaluated using RMSE and visualized predicted vs actual scores

## 📈 Results

- The model achieved high accuracy in predicting final scores.
- Visual graphs showed close alignment between predicted and actual scores.

## ✅ What I Learned

- Real-world application of deep learning for regression tasks
- Feature engineering and selection
- Building and tuning neural networks using Keras
- Evaluating model performance effectively

## 🚀 Future Improvements

- Integrate LSTM or time series models for sequence prediction
- Add player form/stats as additional features
- Use live match data for real-time prediction



