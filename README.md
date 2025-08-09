# 📈 Stock Price Prediction (ML & LSTM)

## 📌 Overview
This project builds predictive models to forecast **future stock prices** based on historical data, including features like **Open, Close, High, Low, and Trading Volume**.  
Both **Random Forest Regressor** and **Long Short-Term Memory (LSTM)** models are trained and evaluated, allowing for performance comparison.

---

## 🗂 Dataset
The dataset contains historical stock data with the following columns:
- `Date` – Trading date
- `Open` – Opening price
- `High` – Highest price of the day
- `Low` – Lowest price of the day
- `Close` – Closing price
- `Volume` – Number of shares traded

---

## ⚙️ Steps Performed
1. **Data Loading & Inspection**
   - Load CSV dataset
   - Check for missing values and data types

2. **Data Preprocessing**
   - Handle missing values
   - Convert `Date` column to datetime
   - Feature scaling for LSTM
   - Train-test split

3. **Model Training**
   - **Random Forest Regressor**
   - **LSTM (Long Short-Term Memory)** network for sequential modeling

4. **Model Evaluation**
   - Mean Absolute Percentage Error (MAPE)
   - Visualization of predicted vs actual prices

5. **Future Price Forecasting**
   - Predict next 5 days' prices using both models

---

## 🛠️ Tools & Libraries
- Python 3.x
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn
- TensorFlow / Keras

---

## 📊 Results
**Model Comparison (in original price scale):**
- **Random Forest MAPE:** 13.97%
- **LSTM MAPE:** 2.88%

**Future Price Predictions:**
- **LSTM (next 5 days):**  
  `[186.73, 177.19, 162.93, 146.43, 129.41]`
- **Random Forest (next 5 days):**  
  `[134.04, 92.71, 75.44, 73.06, 70.52]`

---

## 📌 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Stock_Price_Prediction_ML_LSTM.git

2. Navigate into the project folder:
   ```bash
   cd Stock_Price_Prediction_ML_LSTM

3. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn tensorflow

4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook stock_price_prediction.ipynb


