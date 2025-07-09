# 🧠 Day 16: Multivariate Regression with Multiple Outputs (Concrete Properties Prediction)

Today, I explored **multi-output regression** using a real-world datasets. The datasets are of arff format I collected the data and loaded it innto a dataframe using pandas. I realied data cleaning is a very essential part in Machine Learning. A model trained on clean data makes better predictions. I used the IQR method for data cleaning and scaled using MinMaxScaler.


### 🧹 Data Preprocessing

- ✅ No missing values detected
- ✅ Outliers removed using IQR method with 10th and 90th quantiles
- ✅ Applied `MinMaxScaler` separately to inputs and outputs
- ✅ Used `.reshape()` to fit input/output shapes properly

---

### 📉 Training Results

- Trained for 400 epochs
- Loss consistently decreased
---

### 📈 Evaluation

- Plotted **Actual vs Predicted** graphs for all 3 outputs
- Graphs show very high alignment to the diagonal (ideal), indicating **strong performance**
- Inverse-transformed predictions to original scale showed **reasonable accuracy** for sample inputs

---
