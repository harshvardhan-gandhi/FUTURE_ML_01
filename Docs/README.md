# FUTURE_ML_01 – AI-Powered Sales Forecasting Dashboard  

## 📌 Overview  
This project is part of my **Future Interns Machine Learning Internship** (Task 1).  
The aim is to build an **AI-powered sales forecasting system** that predicts future sales trends using machine learning and presents insights through an **interactive Power BI dashboard**.  

---

## 🎯 Objectives  
- Preprocess and clean historical retail sales data  
- Engineer features such as monthly sales and seasonal patterns  
- Train a **time series forecasting model** using **Facebook Prophet**  
- Build an interactive Power BI dashboard for visualization  
- Provide clear **business insights** for decision-making  

---

## 🛠️ Tools & Technologies  
- **Python**: Pandas, Prophet, Matplotlib, Scikit-learn, NumPy  
- **Power BI Desktop**  
- **Superstore Sales Dataset**  
- **GitHub** for code hosting & version control  

---

## 📊 Dashboard Features  
- Sales trend line (**actual vs forecasted**)  
- **Monthly & yearly comparisons**  
- Filters for **Category** and **Region**  
- Highlighted **top-selling products** and seasonal lows  
- KPI cards (Total Sales, Profit, Avg. Discount)  

---

## 📂 Project Structure  
```text
FUTURE_ML_01/
│
├── code/                 # Python forecasting scripts
│   ├── prophet_model.py
│   └── requirements.txt
│
├── data/                 # Raw data & forecast outputs
│   ├── Superstore.csv
│   └── forecast_results.csv
│
├── dashboard/            # Power BI files
│   ├── Task1_Dashboard.pbix
│   └── Dashboard_Screenshot.png
│
├── docs/                 # Documentation
│   └── README.md
```

---

## 📈 Model Performance
- **MAE**  : 5665.18  
- **RMSE** : 7260.16  
- **MAPE** : 13.22%  
- **sMAPE**: 13.16%  

The model provides a reliable monthly sales forecast for decision-making.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/harshvardhan-gandhi/FUTURE_ML_01.git
2. Navigate into the project folder:
   cd FUTURE_ML_01/code

3. Install dependencies:
   pip install -r requirements.txt

4. Run the Prophet forecasting script:
   python prophet_model.py

5. The forecast results will be exported as forecast_results.csv.
   Open the Power BI file (Task1_Dashboard.pbix) to explore the dashboard.

📌 Internship Details

- **Internship Program** : Future Interns – Machine Learning Track

- **Candidate ID (CIN)** : FIT/AUG25/ML2358

- **Task** : AI-Powered Sales Forecasting Dashboard (Task 1)

