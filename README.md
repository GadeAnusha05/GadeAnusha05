Network Traffic Anomaly Visualization — UNSW-NB15
Description:

This project aims to provide a comprehensive analysis and visualization of network traffic data, with a specific focus on detecting anomalies and malicious activity. The project utilizes the UNSW-NB15 dataset, a well-known dataset used for network intrusion detection, containing both normal and attack network traffic data.

The main goal is to visualize and understand the characteristics of different types of network traffic, including protocols, flow duration, and service usage, as well as identifying patterns that can indicate potential attacks. The project leverages various data visualization tools such as Plotly, Matplotlib, Seaborn, and Streamlit to create an interactive and informative dashboard.

Key Features:
**Normal vs Attack Traffic Distribution:**
A bar chart comparing the distribution of normal and attack traffic labels. It helps to get a quick overview of the dataset and the prevalence of attacks in the traffic data.
**Protocol Usage Distribution:**
A visualization showing the distribution of various protocols used in the dataset (e.g., TCP, UDP). This feature helps to understand which protocols are most frequently used in network communication.
**Flow Duration Histogram:**
An interactive histogram displaying the duration of network flows. It highlights the distribution of how long the network connections last, which can help identify irregularities or long-duration attacks.
**Service Type Distribution:**
A bar chart displaying the usage of different network services (e.g., HTTP, DNS). This can help identify which services are more commonly used in normal and attack traffic.
**Correlation Heatmap:**
A heatmap that illustrates the correlations between numeric features in the dataset. This helps to understand relationships between variables like duration, protocol, and service type.
**Technologies Used:**
01.Python 3.x: The primary programming language used for the project.
02.Pandas: Used for data manipulation and cleaning.
03.Matplotlib & Seaborn: Used for static and statistical data visualizations.
04.Plotly: Used to create interactive visualizations.
05.Streamlit: Used to build the interactive web-based dashboard.

**Use Case:**
This project is especially useful for cybersecurity professionals, network analysts, or anyone interested in detecting and analyzing network anomalies. It provides an easy-to-use and interactive interface that can be used to:

Explore the UNSW-NB15 dataset.

Detect patterns in network traffic that could indicate potential cyber threats or attacks.

Gain insights into the general network traffic behavior.

Target Audience:
Cybersecurity professionals who are analyzing network traffic for anomaly detection and intrusion prevention.

Data scientists and researchers who want to use network traffic data for anomaly detection research.

Students and educators in the fields of cybersecurity, data science, and machine learning who want to learn about network traffic analysis and visualization.

