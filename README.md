# 📈 Weekly Demand Forecasting in Retail (Fictional Project)

This project presents a simulated case of a retail company aiming to forecast weekly product demand to reduce stockouts and optimize inventory levels.

---

## 📌 Case Description

A fictional retail company is experiencing frequent stockouts across its distribution centers. To proactively address this, a weekly demand forecasting model is developed using Python and Facebook Prophet.

---

## 🧩 Dataset

- Simulated dataset: `data/demanda_retail_ficticio.csv`
- Period: Weekly data from January 2023 to December 2024
- SKUs: 5 products across various categories
- Warehouses: North, Central, and South
- Variables:
  - `fecha` (date)
  - `sku`
  - `categoria` (category)
  - `almacen` (warehouse)
  - `unidades_vendidas` (units sold)
  - `stock`
  - `precio` (price)

> 📝 All data is entirely fictitious and generated for demonstration purposes only.

---

## 🧭 Project Flow

![Forecast Process](images/A_flowchart_infographic_illustrates_the_process_of.png)


## 🔮 Forecasting Model

- Library: [Facebook Prophet](https://facebook.github.io/prophet/)
- Objective: Forecast `unidades_vendidas` (units sold) for the next 6 weeks
- Evaluation metric: MAPE (Mean Absolute Percentage Error)
- Model training: One model per SKU and warehouse
- Output visualized in Jupyter Notebook and Tableau

---

## 📊 Tableau Dashboard

The final dashboard was built in Tableau and includes:

- Historical demand + forecast line chart
- Model performance KPIs
- Visual alerts for potential stockouts
- Stock vs. forecasted demand comparison

📁 See folder: `/dashboard`

---

## 🧠 Results

- Average MAPE (simulated): ~9.5%
- Estimated improvement in product availability: +5 percentage points
- Enables more efficient weekly replenishment planning

---

## 📂 Key Files

| File | Description |
|------|-------------|
| `data/demanda_retail_ficticio.csv` | Simulated weekly demand data |
| `notebooks/forecasting_model.ipynb` | Prophet-based forecasting model |
| `dashboard/dashboard_forecast.twbx` | Interactive Tableau dashboard |
| `images/forecast_chart.png` | Forecast summary chart for presentation |

---

## 💻 Requirements

To install dependencies:

```bash
pip install -r requirements.txt
```

Suggested content of `requirements.txt`:

```
pandas
numpy
matplotlib
prophet
```

---

## 👨‍💻 Author

**Daniel Alejandro Sánchez Colunga**  
📍 Monterrey, Mexico  
✉️ dscolunga@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/daniel-colunga-14559b86)  
📊 [Tableau Portfolio](https://public.tableau.com/profile/daniel.colunga4244)

---

## ⚠️ Disclaimer

This is a fictional project developed exclusively for educational and portfolio purposes. All data is artificial and does not represent any real business.
