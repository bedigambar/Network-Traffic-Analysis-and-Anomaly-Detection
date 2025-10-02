# Network Traffic Analysis and Anomaly Detection

[![License](https://img.shields.io/github/license/bedigambar/Network-Traffic-Analysis-and-Anomaly-Detection)](LICENSE)
[![Repo Language](https://img.shields.io/badge/language-Jupyter%20Notebook%20%26%20Python-blue)](https://github.com/bedigambar/Network-Traffic-Analysis-and-Anomaly-Detection)


## Overview

This project provides a comprehensive solution for analyzing network traffic and detecting anomalies using machine learning techniques.

Network traffic analysis is essential for understanding the behavior of devices in a network, identifying suspicious activities, and protecting against security threats. Anomaly detection helps in finding unusual patterns or outliers that may indicate security breaches, malware infections, or network misconfigurations.


## Requirements

- Python 3.x
- Scapy
- Pandas
- Matplotlib
- Scikit-learn
- ipaddress


## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/bedigambar/Network-Traffic-Analysis-and-Anomaly-Detection.git
   cd Network-Traffic-Analysis-and-Anomaly-Detection
   ```

2. **Install dependencies**
   - Ensure the Requirements are installed.
   - Run the Python script or the Jupyter Notebook.
   - Or use `conda` as an `environment.yml` file is provided:
     ```bash
     conda env create -f environment.yml
     conda activate net-traffic-analysis
     ```


## Methodology

1. Read the pcap file using Scapy.
2. Extract relevant packet information (source IP, destination IP, protocol, timestamp, etc.).
3. Create a Pandas DataFrame from the extracted data.
4. Perform exploratory data analysis (EDA) to understand the distribution of protocols, top talkers, and traffic volume over time.
5. Use the most active IPs as known malicious IPs.
6. Train an Isolation Forest model to detect anomalies.
7. Predict anomalies and save them to a CSV file.


## Results

- Top 20 source IPs
- Top 20 destination IPs
- Protocol distribution
- Traffic volume over time
- Detected threats (known malicious IPs)
- Detected anomalies (using Isolation Forest)
- Anomalies CSV file


## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements, features, or bug fixes.
