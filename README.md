# EDA_Optimising_NYC_Taxis_Prajakata_Patil
Analytical deep-dive into 2023 NYC Taxi operations to support pricing, dispatching, and fleet strategy.

# 🚕 NYC Yellow Taxi Data Analysis (2023)

This project presents a full-scale Exploratory Data Analysis (EDA) conducted on the **New York City Yellow Taxi trip records for the year 2023**. The analysis uncovers patterns in demand, revenue, and rider behavior to help optimize fleet operations, inform pricing strategies, and guide data-driven decision-making for urban mobility services.

---

## 📁 Deliverables

| File | Description |
|------|-------------|
| `EDA_Assg_NYC_Taxi_Starter.ipynb` | Fully coded Jupyter notebook with data preparation, EDA, insights, and visualizations |
| `Report_NYC_Taxi_Operations_Starter.docx` | Executive-level analytical report with interpretations, charts, and business recommendations |

---

## 🎯 Goals

- Clean, preprocess, and transform real-world NYC taxi trip data  
- Identify key usage trends across time, location, and passenger behavior  
- Evaluate vendor fare structures, tips, surcharges, and trip distribution  
- Deliver actionable insights for better routing, scheduling, and pricing  

---

## 🧠 Key Business Insights

### ⏰ Temporal Demand Trends
- Ride volumes **peak between 8–9 AM and 5–6 PM**, matching commuter hours  
- **Fridays and Saturdays** are consistently the busiest days  
- Revenue is highest in **Q3 and Q4**, indicating seasonal surges (summer, holidays)

### 🗺️ Zone-Level Observations
- Top pickup zones: **Midtown Center**, **JFK Airport**, **Times Square**  
- Drop-off/pickup imbalance in certain zones indicates opportunity for **smart repositioning**  
- Nighttime traffic spikes in areas like **East Village** and **Brooklyn nightlife hubs**

### 💵 Fare, Tip & Vendor Patterns
- **Fare is highly correlated with trip distance (0.95+)**  
- **Vendor 2** charges higher for short trips; **Vendor 1** shows stable pricing  
- **Tips are higher** on long trips, during late evenings, and when using card payments  
- **Shared rides reduce per-passenger cost**, making carpooling financially viable

---

## 📊 Visuals & Analysis Coverage

The notebook contains 25+ professional visualizations, including:
- Temporal distribution plots (hour, day, month)
- Revenue vs trip distance, fare trends
- Vendor comparison charts
- Pickup/dropoff heatmaps using zone shapefiles
- Tip percentage, passenger count, and surcharge trends

These visuals support clear business reasoning behind every insight.

---

## 🔧 Tools Used

- **Python**  
- **Pandas** – data manipulation  
- **Seaborn / Matplotlib** – charts and plots  
- **GeoPandas** – spatial analysis with shapefiles  
- **Jupyter Notebook** – development environment

---

## 📝 Summary

This project delivers a high-utility EDA pipeline that reveals critical metrics for NYC taxi operations. It supports:

- Demand-based vehicle allocation  
- Surge pricing strategies  
- Improved rider experience through data-backed planning  
- Identification of high-revenue zones and time windows  

The framework is modular and can be scaled further for machine learning-based trip forecasting, demand prediction, or API integration for real-time decision support.

---

## 📄 License

This project is licensed under the **MIT License**.

You are free to use, modify, and share this project with proper attribution. See the [LICENSE](LICENSE) file for full terms.
