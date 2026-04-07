🚦 Smart Traffic Analysis & Prediction System
📍 Parma “30 Zone” | Machine Learning | Smart City Analytics
🔥 Project Overview

Urban traffic congestion is a growing challenge in modern cities. This project transforms multi-year traffic sensor data (2022–2024) from Parma’s “30 Zone” into actionable insights using data analytics, machine learning, and geospatial techniques.

The system not only analyzes historical traffic patterns but also predicts future congestion levels and detects anomalies—supporting smarter, data-driven urban planning.

❗ Problem Statement

Traditional traffic monitoring systems rely heavily on static rules and lack predictive capabilities. In regulated urban zones like Parma’s “30 Zone”, there is a need to:

Anticipate congestion before it occurs
Detect unusual traffic disruptions in real time
Optimize traffic flow and enforcement strategies
Support smart city decision-making with data
🎯 Key Achievements

✔ Built an end-to-end traffic analysis pipeline
✔ Developed a machine learning model for traffic prediction (MAE ≈ 0.36)
✔ Accurately classified traffic into Low / Medium / High levels
✔ Identified hidden traffic anomalies and route inefficiencies
✔ Extracted real-world insights from 3 years of sensor data

📊 Key Insights (Business Impact)
📈 Traffic peaks consistently occur in December, indicating seasonal demand
📉 Significant traffic drop observed in mid-2023, with recovery in 2024
🚗 Speed violations are more frequent during low-traffic hours
⏱️ Model accurately predicts rush hours (7–10 AM, 4–7 PM)
🔁 Strong inverse relationship between traffic volume and speed

👉 These insights can help city planners:

Improve enforcement strategies,
Optimize traffic signals,
Reduce congestion hotspots.

🧠 Methodology
1. Data Analysis
Exploratory Data Analysis (EDA) on multi-year sensor data
Trend analysis across time (hourly, monthly, yearly)

2. Machine Learning Models
XGBoost Regressor (Poisson) → Traffic prediction

<img width="427" height="333" alt="image" src="https://github.com/user-attachments/assets/2f1d540d-adee-4b6d-9178-df7016bc6984" />

Random Forest Classifier → Zero-traffic detection

<img width="430" height="335" alt="image" src="https://github.com/user-attachments/assets/c006014c-f920-49f9-a410-d3cd3cf88c50" />


4. Traffic Classification
Categorized traffic into:
- Low
- Medium
- High

<img width="443" height="263" alt="image" src="https://github.com/user-attachments/assets/b79a479f-89f6-46e1-90ca-a91af060b2f9" />


4. Anomaly Detection
Flow-based detection between sensor pairs
Identifies:
- Bottlenecks
- Route diversions
- Traffic inconsistencies

<img width="739" height="364" alt="image" src="https://github.com/user-attachments/assets/7254af19-5591-4ad3-94c3-c33289d06e90" />

📋 Route Summary:
Route 47 -> 51:
  - Average Flow Difference: -21.93
  - Anomalies Detected: 13
  - Possible Diversion: Vehicle loss between Sensor 47 and Sensor 51. Average flow difference (-21.93) suggests vehicles are diverting.
  - Anomaly Insight: 13 anomalies detected. Types: {'None': 273, 'NegativeDrop': 13}


5. Visualization
Geospatial mapping of traffic flow
Time-series visualizations

<img width="288" height="335" alt="image" src="https://github.com/user-attachments/assets/7350ea4a-9d53-4c55-94dd-d348e2fc66f8" />

📊 Results
Model Performance
MAE: ~0.36.
Strong alignment between predicted and actual traffic

🛠️ Tech Stack
- Programming: Python
- Data Analysis: Pandas, NumPy
- Machine Learning: Scikit-learn, XGBoost
- Visualization: Matplotlib, Seaborn
- Geospatial Analysis: Folium / GeoPandas

⚠️ Limitations
- Limited sensor coverage
- No real-time deployment (offline analysis)
- Model struggles with rare/unseen events (e.g., road closures)
- Static thresholds in anomaly detection

🔮 Future Improvements
🔄 Real-time traffic prediction system
🌦️ Integration of weather & event data
🤖 Deep learning for adaptive anomaly detection
🧭 Route recommendation system
🏙️ Policy simulation tools for smart cities
