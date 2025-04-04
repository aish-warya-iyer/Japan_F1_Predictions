# 🏎️ F1 Qualifying Predictions

Predicts Formula 1 qualifying lap times (Q3) using Q1/Q2 performance data, team/driver factors, and machine learning.

![image](https://github.com/user-attachments/assets/b873c108-ec06-4a9d-92d1-8415301e13d2)


---

## 🔧 Features
- **Data Fetching**: Uses `FastF1` to fetch real qualifying session data.
- **Performance Modeling**: Adjusts predictions based on team/driver historical performance.
- **Machine Learning**: Linear regression to predict Q3 times from Q1/Q2.
- **Error Metrics**: Reports MAE (Mean Absolute Error) and R² scores.

---

## 📦 Dependencies
- Python 3.8+
- Libraries:
  ```bash
  pip install fastf1 pandas numpy scikit-learn matplotlib seaborn
