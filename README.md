# 🏢 Predicting Airflow Velocity, Temperature, and Humidity for Healthy Building Monitoring using Neural Networks

### 📖 Project Overview
This project develops a neural network model that predicts indoor airflow velocity 💨 and temperature 🌡️ and humidity 💧 levels to optimize healthy indoor environments. Using 8 key environmental and operational input variables, the model predicts 462 outputs that reflect the building's air quality and comfort conditions. The primary goal is to support real-time monitoring systems in healthy buildings 🏙️, improving overall indoor environments by managing ventilation, temperature, and humidity.

### 📊 Data Description

#### 🔑 Input Variables:
The 8 input variables represent environmental and building operational conditions:
1. **🪟 Window Status** (open/closed)
2. **❄️ Air Conditioning (AC) Status** (on/off)
3. **🌀 Fan Status** (on/off)
4. **☀️ Solar Radiation**
5. **🌡️ Outdoor Temperature**
6. **💨 Wind Velocity**
7. **🌬️ Wind Direction**
8. **💧 Outdoor Relative Humidity**

#### 📈 Output Variables:
The 462 output variables capture the indoor environmental quality, specifically:
- **💨 Air Velocity:** The speed of air movement inside the building, essential for air circulation and comfort.
- **🌡️ Indoor Temperature:** Key for maintaining a comfortable and healthy environment for occupants.
- **💧 Indoor Relative Humidity:** Affects air quality, mold growth, and occupant comfort.

### 🧠 Modeling Approach
This project uses a neural network model 🤖 to predict how changes in outdoor conditions (e.g., solar radiation, wind velocity) and building systems (e.g., AC, fan status) impact the indoor environment.

- **Training:** The model is trained to predict real-time airflow conditions that contribute to healthy building environments 🏢, focusing on thermal comfort and air quality.
- **Applications:** Designed to optimize HVAC system settings and improve indoor air circulation.


