🚦 Smart Traffic Analysis & Prediction System

Parma “30 Zone” | Data Analytics | Machine Learning | Smart City Project

📌 Executive Summary

Traffic congestion is a growing issue in modern cities, impacting daily life, safety, and urban efficiency. In this project, I analyzed 3 years (2022–2024) of traffic sensor data from Parma’s “30 Zone” to uncover patterns, predict traffic behavior, and detect unusual disruptions.

Using data analytics and machine learning, I built a system that not only explains what is happening in traffic, but also predicts what will happen next.

The project delivers:

- Accurate traffic predictions (MAE ≈ 0.36)
- Clear classification of traffic levels (Low / Medium / High)
- Detection of unusual traffic patterns (e.g., diversions, bottlenecks)
- Actionable insights for smarter city planning

👉 In simple terms:
This system helps cities reduce congestion, improve safety, and make better decisions using data.


❗ Business Problem

Traditional traffic systems are reactive—they respond after congestion has already happened.

In regulated zones like Parma’s “30 Zone”, city planners need to:

- Predict traffic before congestion builds up
- Detect unusual disruptions (accidents, diversions, sensor issues)
- Improve enforcement of speed limits
- Optimize traffic flow and infrastructure planning

Without predictive insights:

- Traffic jams increase
- Enforcement becomes inefficient
- Planning decisions rely on assumptions instead of data

👉 The goal of this project was to shift from reactive monitoring → proactive traffic intelligence.

🧠 Methodology

This project follows a complete end-to-end analytics pipeline:

1. Data Collection & Integration
- Combined 3 years of sensor data into a unified dataset
- Processed over 1.6 million records
- Standardized timestamps, sensor IDs, and formats

2. Data Cleaning & Preprocessing
- Removed missing and corrupted values
- Handled outliers using percentile-based filtering
- Ensured consistency across all sensors and years

3. Feature Engineering

Created meaningful features to improve analysis:

- Time-based features (hour, day, month, year)
- Estimated vehicle speed
- Traffic flow differences between sensors
- Vehicle count changes (vehicle_diff)

👉 This step transforms raw data into business-relevant insights.

4. Exploratory Data Analysis (EDA)
- Identified daily, monthly, and yearly traffic trends
- Visualized peak hours and seasonal patterns
- Compared traffic flow and speed behavior

5. Machine Learning Models
- Random Forest Classifier → Detect zero-traffic conditions
- XGBoost Regressor (Poisson) → Predict traffic volume
- Traffic categorized into Low / Medium / High levels

6. Anomaly Detection
- Compared traffic flow between sensor pairs
- Used statistical methods (Z-score) to detect anomalies
Identified:
- Traffic diversions
- Bottlenecks
- Sensor inconsistencies

🛠️ Skills Demonstrated

📊 Data Analysis
- Exploratory Data Analysis (EDA)
- Trend & pattern identification
- Statistical analysis (Z-score, distributions)

🧹 Data Processing
- Data cleaning & transformation
- Handling missing values and outliers
- Feature engineering

🤖 Machine Learning
- Regression (XGBoost)
- Classification (Random Forest)
- Model evaluation (MAE, Accuracy, F1-score)

🗺️ Data Visualization & Storytelling
- Time-series analysis
- Traffic pattern visualization
- Translating data into business insights

🧰 Tools & Technologies
- Python (Pandas, NumPy)
- Scikit-learn, XGBoost
- Matplotlib, Seaborn
- GeoPandas / Folium

📊 Results & Key Findings

The analysis uncovered several important real-world insights:

- 📈 Traffic peaks in December → Strong seasonal demand
- ⏱️ Rush hours identified → 7–10 AM and 4–7 PM
- 🚗 Speed violations occur during low traffic
- 🔁 Inverse relationship between speed and traffic volume
- 📉 Traffic drop observed in mid-2023, with recovery in 2024
- 🚨 Anomaly Detection Example

Route: Sensor 47 → 51
- Detected vehicle loss between sensors
- Indicates possible traffic diversion or route inefficiency

💡 Business Recommendations

Based on the analysis, the following actions can improve urban traffic management:

🚦 Traffic Optimization
- Adjust traffic signals based on predicted peak hours
- Reduce congestion at known hotspots

🚓 Enforcement Strategy
- Increase monitoring during low-traffic periods (higher speeding risk)

🧭 Infrastructure Planning
- Investigate routes with consistent vehicle loss (possible diversions)
- Improve road design in bottleneck areas

📅 Seasonal Planning
- Prepare for high traffic in December with better traffic control measures

🤖 Future Improvements
- Real-time traffic prediction system
- Integration with weather and event data
- Smart route recommendation systems
