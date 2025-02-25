# AAI-530-group1
## Zach Artman, Iman Hamdan, Diego Acevedo
# Smart Indoor Air Quality Monitoring System 🌍💨

## Note: The models are located in **[`main.ipynb`](/main.ipynb)**
## 📌 Introduction

Indoor air quality (IAQ) plays a crucial role in public health, well-being, and productivity. Poor air quality can lead to respiratory illnesses, reduced cognitive function, and an increased risk of chronic diseases. However, monitoring and predicting IAQ in real-time remains a challenge, especially in enclosed spaces like homes, offices, and industrial buildings.

This project, **Smart Indoor Air Quality Monitoring System**, leverages **IoT (Internet of Things) sensors and machine learning** to provide a data-driven approach to **monitor, analyze, and predict air quality levels**. Our system collects data from various environmental sensors measuring **CO₂ levels, PM2.5, humidity, and temperature**. The collected data is then processed using machine learning models to detect **anomalies, forecast trends, and offer actionable insights**.

### 🎯 Project Goals
- **Real-time Air Quality Monitoring**: Gather sensor data continuously for accurate indoor air assessments.
- **Predictive Analytics**: Use regression and deep learning models to forecast pollutant levels.
- **Anomaly Detection**: Identify dangerous pollutant spikes that may indicate health risks.
- **User-Friendly Visualization**: Provide clear and interactive dashboards for decision-makers.
- **Scalability & Deployment**: Build an easily adaptable system that can be implemented in various settings, such as smart homes, workplaces, and healthcare facilities.

### 🛠 Technologies Used
- **Python & Machine Learning**: Data processing, feature engineering, predictive modeling.
- **Tableau Public**: Data visualization and analytics dashboard.

### 💡 Why This Matters?
According to research, **indoor air pollution is often 2-5 times worse than outdoor pollution**. Prolonged exposure to high pollutant levels can lead to respiratory diseases, cardiovascular issues, and decreased productivity. By **leveraging AI-driven predictive insights**, our system provides **proactive air quality monitoring**, empowering users to make informed decisions and take preventive actions before air quality deteriorates.

## 🏗 IoT System Design

Our IoT framework consists of:
- **Machine Learning Models**: Predict air quality trends and detect anomalies.
- **Dashboard**: Displays insights through interactive visualizations.

## 📊 Dataset

We use the **[Indoor Air Quality Dataset](https://www.kaggle.com/datasets/hemanthkarnati/indoor-air-quality-dataset)** from Kaggle. The dataset includes:
- Timestamped air quality readings.
- Sensor data such as CO2 levels, PM2.5, humidity, and temperature.

## 🤖 Machine Learning Models

We implemented various machine learning models:
1. **Regression Analysis**: Linear Regression and Random Forest to predict air quality.
2. **Clustering**: k-means to group different air quality levels.
3. **Anomaly Detection**: Isolation Forest for detecting abnormal pollutant spikes.
4. **Time-Series Forecasting**: ARIMA and LSTM models for future air quality predictions.

## 📈 Visualization (Tableau Dashboard)

The interactive dashboard visualizes:
- Time-series trends of pollutants.
- Heatmaps showing pollutant distributions.
- Anomaly detection alerts.
- Model predictions.

🔗 **View the Dashboard:** [[Link](https://public.tableau.com/views/AAI530-Group1/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)]



## 🎓 Acknowledgments

- [Indoor Air Quality Dataset - Kaggle](https://www.kaggle.com/datasets/hemanthkarnati/indoor-air-quality-dataset)
- "Analytics for the Internet of Things" - Andrew Minteer

