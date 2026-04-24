# 🏥 Patient Health Deterioration Analysis & Interactive Dashboard

## 📌 Overview

This project analyzes time-series healthcare data to understand patient health dynamics and identify patterns associated with clinical deterioration. Using real-world hospital monitoring data, the study examines how vital signs such as heart rate, oxygen saturation (SpO₂), respiratory rate, temperature, and blood pressure evolve over time.

The project combines exploratory data analysis (EDA) with interactive visualization to transform complex medical data into meaningful insights. A browser-based dashboard was developed to enable dynamic exploration of patient conditions across different time intervals and admission types.



## 🎯 Objectives

* Analyze trends in vital signs over time
* Detect abnormal patterns and extreme values
* Identify relationships between multiple health indicators
* Compare deteriorated vs non-deteriorated patient groups
* Build an interactive dashboard for real-time data exploration



## 📊 Key Features

* 📈 Time-series analysis of vital signs
* 📉 Distribution and outlier detection
* 🔗 Correlation heatmap for feature relationships
* 🧪 Lab marker comparison across patient groups
* 📊 Interactive dashboard with filters and dynamic visuals



## 🖥️ Interactive Dashboard

The dashboard is built using **Panel and hvPlot**, and runs in a browser environment. It allows users to:

* Filter data by admission type and time
* Visualize patient trends dynamically
* Explore deterioration patterns interactively
* Analyze relationships between multiple health metrics



## 🛠️ Technologies Used

* Python
* Pandas & NumPy
* Panel
* hvPlot
* Data Visualization & EDA Techniques



## 📁 Project Structure

* `hospital_deterioration_dashboard.ipynb` → Main dashboard notebook
* `hospital_deterioration_hourly_panel.csv` → Dataset
* `README.md` → Project documentation



## 🚀 How to Run

1. Install required libraries:

   ```bash
   pip install pandas numpy panel hvplot
   ```
2. Run the dashboard:

   ```bash
   panel serve hospital_deterioration_dashboard.ipynb --show
   ```

---

## 📌 Outcome

The project demonstrates how data science can be applied in healthcare to monitor patient conditions, detect early warning signals, and support data-driven clinical decisions.

---

## 🔮 Future Scope

* Integration with real-time hospital data systems
* Predictive modeling for early risk detection
* Deployment as a web-based healthcare analytics tool

---

## 👩‍💻 Author

**Krishika Malhotra**
B.Tech Student | Aspiring Data Scientist
