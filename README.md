# Anomaly Detection in Weekly Sales Data for Walmart Store in US
This project focuses on anomaly detection in the weekly sales data for a Walmart store. The goal is to identify unusual patterns that may negatively or positively impact sales performance. Anomalies in sales data can indicate various issues such as stock shortages, marketing events, or even system errors.

The analysis is based on a time-series approach, and several machine learning techniques were applied to enhance the model's ability to detect anomalies effectively. The dataset used for this project consists of weekly sales records from a Walmart store.

## Project Overview
- Created By: Abdelaziz Mohamad.
- Date of Completion: July 2024.
- Project Type: Machine learning anomaly detection.
# Anomaly Detection in Weekly Sales Data for Walmart

## Dataset
- **Source**: Weekly sales data from Walmart
              Link: https://www.kaggle.com/datasets/ujjwalchowdhury/walmartcleaned
- **Features**:
  - Date
  - Weekly Sales
  - Holiday/Non-Holiday
  - Temperature
  - Fuel Price
  - CPI (Consumer Price Index)
  - Unemployment rate

## Methodology
1. **Data Cleaning**: Preprocessing the dataset to handle missing values, outliers, and other inconsistencies.
2. **Exploratory Data Analysis (EDA)**: Visualizing the sales data and understanding patterns, trends, and seasonality.
3. **Anomaly Detection**:
   - Utilized `KNN`, `Isolation Forest` and `DBSCAN` models for time-series anomaly detection.
   - Applied well-known Python libraries such as `pandas`, `matplotlib` and `scikit-learn`.
4. **Model Training**:
   - Training on past weekly sales data.
   - Testing models to capture sudden spikes, dips, or irregularities.
5. **Results**:
   - Detected anomalies corresponding to known events (like holidays or promotions).
   - Visualized the detected anomalies on a time-series plot.

## Project Setup

### Requirements
- Python 3.7+
- Install the required packages:

  ```bash
  pip install -r requirements.txt

### Requirements
- Python 3.7+
- Install the required packages:

  ```bash
  pip install -r requirements.txt
## How to Run
1. Clone the repository:
   ```bash
    git clone https://github.com/yourusername/Anomaly-Detection-Walmart-Weekly-Sales.git
    cd Anomaly-Detection-Walmart-Weekly-Sales
2. Download the dataset: Place your dataset in the data/ folder.

3 Run the script: Start the anomaly detection model with:

    ```bash
    python anomaly_detection.py

## Future Improvements
- Enhanced Model: Implementing more advanced models like LSTM or SARIMA for better accuracy in time-series forecasting.
- Feature Engineering: Adding more features (e.g., weather data, promotion schedules) to improve model predictions.
- Real-time Detection: Building a pipeline for real-time anomaly detection on streaming sales data.
