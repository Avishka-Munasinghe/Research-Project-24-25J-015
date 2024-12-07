# Research-Project-24-25J-015


# Empowering Sri Lankan Households: A Data-Driven Approach to Managing Electricity Consumption and Promoting Sustainable Energy Practices  

## Overview  

This project aims to address the rising electricity costs and promote sustainable energy practices in Sri Lanka. By leveraging IoT and machine learning technologies, the system empowers households with tools to monitor, predict, and manage electricity consumption more effectively.  

### Key Objectives:  
1. **Real-Time Electricity Monitoring**: Provide households with data to track and manage electricity usage.  
2. **Promote Sustainable Energy Practices**: Deliver actionable insights for adopting energy-saving methods.  
3. **Predictive Analytics**: Use machine learning to forecast electricity consumption and costs, enabling better energy planning.  

---

## System Components  

### **1. Smart Electricity Meter Reading and Bill Prediction Alert System**  
**Contributor**: A.J. Munasinghe  
- **Automated Meter Reading**: Uses an LDR sensor and ESP32 microcontroller to detect electricity consumption in real-time (via LED meter blinks).  
- **Predictive Analytics**: Employs machine learning models to forecast monthly electricity consumption and bills.  
- **Mobile App Dashboard**: Provides users with visualizations of consumption trends, peak usage, and alerts when thresholds are exceeded.  
- **Alerts and Notifications**: Warns users about abnormal usage and promotes cost-saving actions.  

### **2. Smart Electrical Safety Monitoring System**  
**Contributor**: J.M.D.T. Jayasooriya  
- **IoT-Based Current Monitoring**: Utilizes ACS712 current sensors to track electrical current in real time, detecting overloading or breaker trips.  
- **Weather Data Integration**: Analyzes weather conditions using APIs to predict potential electrical hazards.  
- **Notifications**: Sends real-time alerts to users for safety issues, reducing the risk of hazards like short circuits or power surges.  

### **3. Solar System Monitoring and Analysis**  
**Contributor**: N.B.C.A.W. Gunawardana  
- **Real-Time Monitoring**: Displays solar energy production and current weather conditions on a dashboard.  
- **Solar Generation Prediction**: Predicts next-day solar energy output using weather and temperature forecasts.  
- **Notifications**: Alerts users about production changes or inefficiencies in solar power generation.  
- **Data Storage and Insights**: Logs historical energy data for trend analysis and better decision-making.  

### **4. IoT-Driven Smart Electricity Management System**  
**Contributor**: S.U. Madarasinghege  
- **Appliance Monitoring**: Tracks real-time electricity usage of appliances (e.g., refrigerators, ACs, lights) with IoT sensors.  
- **Predictive Analytics**: Forecasts electricity usage for individual appliances to optimize energy consumption.  
- **User Recommendations**: Provides insights on reducing costs and optimizing energy usage based on appliance-specific data.  
- **Alerts**: Notifies users of unusual consumption patterns or potential energy wastage.  

---

## System Architecture  

![System Architecture Diagram](Images/overall%20system%20digram.png)


The system integrates four key modules using the following flow:  
1. **IoT Devices**: Collect real-time data from electricity meters, appliances, and solar panels.  
2. **Firebase**: Stores data for real-time and historical analysis.  
3. **Machine Learning Backend**: Processes data for predictions and analytics.  
4. **Mobile Application**: Visualizes insights and sends alerts to users.  

---

## Dependencies  

### IoT Devices  
- **ESP32 Microcontroller**: For capturing and transmitting meter readings.  
- **LDR Sensor**: Detects LED blinks for electricity usage monitoring.  
- **ACS712 Current Sensor**: Monitors electrical current in safety systems.
- **230 Voltage Signal Capture Circuit**: Monitors circuit breaker offline or online.

### Backend  
- **NumPy**: Numerical computation and array manipulation.  
- **Pandas**: Data manipulation and dataset handling.  
- **TensorFlow**: Builds machine learning models for prediction.  
- **Matplotlib**: Data visualization for analysis and trends.  
- **Scikit-learn**: Provides tools for data preprocessing and model evaluation.  

### Mobile Application  
- **Flutter**: For cross-platform mobile development.  
- **Dart**: Programming language for Flutter.
