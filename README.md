# Anomaly Detection System for Financial Transactions
This project implements an Anomaly Detection System designed to identify outliers in sales and profit data from retail datasets. It employs three powerful anomaly detection techniques:
3-Sigma Method
Isolation Forest
Cluster-based Local Outlier Factor (CBLOF)

In addition to the detection models, this system visualizes the detected anomalies using the Matplotlib library to offer clear insights into the data.

**Anomaly Detection Models**
1. 3-Sigma Method
The 3-Sigma Method is a simple statistical technique used to detect anomalies. It identifies data points that lie more than three standard deviations away from the mean. These points are flagged as potential outliers.

2. Isolation Forest
Isolation Forest works by creating random partitions of the dataset. It isolates the outliers more quickly than the normal data points, as anomalies tend to have fewer similar neighbors, making them easier to separate.

3. Cluster-based Local Outlier Factor (CBLOF)
The CBLOF algorithm detects anomalies by evaluating the density of data points within clusters. Points that are located far away from their cluster centroids are classified as outliers, as they exhibit unusual patterns compared to other data points.

**Installation**
To get started with this project locally, you'll need to install the necessary Python dependencies. You can do so by using pip:
pip install -r requirements.txt

**Usage**
Clone the repository:
git clone https://github.com/your-username/anomaly-detection-retail-data.git
cd anomaly-detection-retail-data

Run the anomaly detection script:
python detect_anomalies.py

This script will apply the three anomaly detection models to your retail sales and profit data and output the detected outliers.

