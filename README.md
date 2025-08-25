# 🔐 Cybersecurity: Suspicious Web Threat Interactions

## Tableau Dashboard
You can view the interactive Tableau dashboard here:  
👉 [View Dashboard on Tableau Public](https://public.tableau.com/app/profile/pasupula.siva.geetha/viz/Cybersecurity_17559735318690/Dashboard1)

# 📌 Project Overview

This project focuses on analyzing suspicious web traffic interactions to identify potential security threats such as malicious requests, unauthorized access, and anomaly patterns. The analysis includes data preprocessing, exploratory data analysis (EDA), and visualization of attack trends. The insights can help cybersecurity teams in detecting, monitoring, and preventing web-based threats.

# 📊 Dataset

You can download the dataset from the following link:

👉 [Download Dataset (Google Drive)](https://drive.google.com/file/d/1-OpnR9FK8EqGuLFB1k45ctPbl-vuZnC-/view)

## Usage

- Clone this repository:
  ```bash
  git clone https://github.com/USERNAME/google_playstore_app.git

Key Columns:

Src IP → Source IP address of request

Dst IP → Destination IP address

Detection Type → Attack type detected (e.g., SQL Injection, DDoS, Brute Force)

Protocol → Communication protocol (HTTP, HTTPS, TCP, UDP, etc.)

Country → Source country of traffic

Timestamp → Request time

# 🔑 Process

Data Collection – Imported dataset into Python using Pandas.

Data Cleaning – Removed null values, formatted IPs, standardized attack categories.

Feature Engineering – Extracted country codes, attack frequency, time-based features.

Exploratory Data Analysis (EDA) – Visualized frequency of attack types, countries, and trends over time.

Threat Insights – Identified top attacking countries, most common attack vectors, and peak attack times.

# 📈 Key Insights

DDoS & SQL Injection are among the most frequent suspicious activities.

Top source countries contribute to the majority of attacks, indicating region-based monitoring is required.

Attack frequency spikes during specific time intervals, showing possible coordinated attempts.

Certain protocols (HTTP, TCP) are heavily targeted in web threats.

Visualization reveals high-risk IPs that repeatedly attempt malicious activity.

# 🛠️ Tech Stack

Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Plotly (if used)

Visualization: Bar charts, pie charts, heatmaps, maps for geolocation

Environment: Jupyter Notebook

# 🚀 How to Run

Clone the repository:

git clone https://github.com/yourusername/Cybersecurity-Web-Threat-Analysis.git
cd Cybersecurity-Web-Threat-Analysis


Install dependencies:

pip install -r requirements.txt


Run the notebook:

jupyter notebook Cybersecurity_Web_Threat_Analysis.ipynb

# ✅ Results

Categorized and visualized attack types.

Detected top attacking countries via geo-mapping.

Identified patterns of suspicious behavior across protocols and time.

Built a framework for monitoring suspicious activity logs.

# 🔮 Future Work

Apply Machine Learning (ML) classification models to predict suspicious vs. normal traffic.

Use clustering techniques to detect new/unseen attack patterns.

Build a real-time dashboard for security analysts.

Integrate with SIEM tools (Security Information and Event Management).

# 📌 Author

👤 Pasupula Siva Geetha
