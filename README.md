# 📊 Sales Data Visualization & Forecasting (Infosys Springboard Internship)

![Sales Forecasting](https://img.shields.io/badge/Data%20Visualization-Power%20BI-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn%20%7C%20XGBoost-orange)
![Forecasting](https://img.shields.io/badge/Time%20Series%20Forecasting-ARIMA%20%7C%20LSTM-red)


---

## 📖 Project Overview
This repository contains an advanced **Sales Data Visualization and Forecasting** project . The project focuses on **interactive dashboards with Power BI** and **predictive analytics using Machine Learning models** to forecast sales and demand trends.

### 🚀 Key Objectives:
- Create interactive **Power BI dashboards** for sales insights.
- Implement **Machine Learning models** for demand and sales forecasting.
- Analyze time series trends to improve business decision-making.
- Automate data processing and visualization workflows.

---

## 🔥 Tech Stack & Tools
| Category                 | Tools & Libraries Used              |
|--------------------------|-------------------------------------|
| 📊 Data Visualization    | Power BI, Matplotlib, Seaborn       |
| 🔍 Data Processing       | Pandas, NumPy, Scikit-learn         |
| 🏆 Machine Learning      | XGBoost, LightGBM, ARIMA, LSTM      |
| 📈 Forecasting           | Time Series Models (SARIMA, Prophet)|
| ⚙️ Deployment            | Streamlit (for interactive ML dashboards)|

---

## 📂 Project Structure

```
📁 Sales-Data-Visualization-Forecasting
│── 📂 data                   # Raw & processed datasets
│── 📂 notebooks              # Jupyter Notebooks for EDA & ML models
│── 📂 powerbi_dashboard      # Power BI reports & dashboards
│── 📂 notebooks              # Scripts for preprocessing & ML models
│── 📂 streamlit_app          # Streamlit-based interactive web app
│── 📄 README.md              # Project documentation
│── 📄 requirements.txt       # Dependencies for ML models
```

---

## 🏆 Key Features

### 📊 1. Power BI Sales Dashboard
- Interactive sales reports with real-time filtering.
- KPIs like revenue, profit, and regional sales trends.
- Dynamic drill-downs and comparisons for deeper insights.

### 🤖 2. Machine Learning Forecasting Models
- **ARIMA/SARIMA** for time series forecasting.
- **Prophet** for robust trend and seasonality predictions.
- **XGBoost/LightGBM** for demand forecasting.
- **LSTM (Deep Learning)** for advanced trend prediction.

### 🚀 3. Demand & Sales Forecasting Web App (Streamlit)
- Upload new datasets for on-the-fly predictions.
- Interactive visualizations and model comparisons.
- API-ready forecasting module for integration with other apps.

---

## 📌 Installation & Usage

### ⚙️ Setup & Installation

#### 1. Clone the Repository
```bash
https://github.com/Greeshma-Medathati/VizPredict.git
cd VizPredict
```

#### 2. Install Required Libraries
```bash
pip install -r requirements.txt
```

#### 3. Run Jupyter Notebook for ML Models
```bash
jupyter notebook
# Open notebooks inside the /notebooks folder
```

#### 4. Run the Streamlit Web App for Interactive Forecasting
```bash
cd streamlit_app
streamlit run app.py
```

#### 5. Access Power BI Dashboard
- Open the **`powerbi_dashboard.pbix`** file in Power BI Desktop.
- Ensure dataset connectivity before visualizing insights.

---

## 📊 Example Results & Visuals

### 📈 Sales Dashboard in Power BI
![Image](https://github.com/user-attachments/assets/23f77dfa-52e2-4ee9-ac8e-57d5ce0c7be5)

### 📉 Forecasting Sales Trends
![Image](https://github.com/user-attachments/assets/ca67e634-4357-4676-af66-8a18d5ac4a5d)

### 🏆 Performance Metrics
| Model     | RMSE  | MAE   | R² Score |
|-----------|-------|-------|----------|
| ARIMA     | 12.3  | 10.5  | 0.87     |
| Prophet   | 11.8  | 10.1  | 0.89     |
| LSTM      | 9.7   | 8.2   | 0.91     |
| XGBoost   | 10.1  | 8.5   | 0.93     |

---


