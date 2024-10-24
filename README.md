# 🏢 Predicting Airflow Velocity, Temperature, and Humidity for Healthy Building Monitoring using Neural Networks

## 📑 Table of Contents
1. [Project Overview](#-project-overview)
2. [Tech Stack](#-tech-stack)
3. [Data Description](#-data-description)
4. [Contributors](#-contributors)
5. [References](#-references)
6. [How to Use](#-how-to-use)
7. [Getting Started](#-getting-started)

---

## 📖 Project Overview
This project develops a neural network model that predicts indoor airflow velocity 💨 and temperature 🌡️ and humidity 💧 levels to optimize healthy indoor environments. Using 8 key environmental and operational input variables, the model predicts 462 outputs that reflect the building's air quality and comfort conditions. The primary goal is to support real-time monitoring systems in healthy buildings 🏙️, improving overall indoor environments by managing ventilation, temperature, and humidity.

---

## 💻 Tech Stack
This project utilizes the following technologies and tools:

<p align="center">
  <img src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=matplotlib&logoColor=black"/>
</p>

---

## 📊 Data Description

### 🔑 Input Variables:
The 8 input variables represent environmental and building operational conditions:
1. **🪟 Window Status** (open/closed)
2. **❄️ Air Conditioning (AC) Status** (on/off)
3. **🌀 Fan Status** (on/off)
4. **☀️ Solar Radiation**
5. **🌡️ Outdoor Temperature**
6. **💨 Wind Velocity**
7. **🌬️ Wind Direction**
8. **💧 Outdoor Relative Humidity**

### 📈 Output Variables:
The 462 output variables capture the indoor environmental quality, specifically:
- **💨 Air Velocity:** The speed of air movement inside the building, essential for air circulation and comfort.
- **🌡️ Indoor Temperature:** Key for maintaining a comfortable and healthy environment for occupants.
- **💧 Indoor Relative Humidity:** Affects air quality, mold growth, and occupant comfort.

---

## 👥 Contributors
This project was developed by:
- **Dr. Ir. Faridah, ST., MSc., IPU** 🧑‍🏫 – Project Lead and Senior Researcher
- **Athallah Naufal Hadi, ST.** 🧑‍🏫 – Assistant Researcher

Feel free to reach out via email for collaboration or inquiries!

---

## 📚 References
Below are some key references and resources used during the development of this project:
- **Faridah, F. et al.** *An Indoor Airflow Distribution Predictor Using Machine Learning for a Real-Time Healthy Building Monitoring System in the Tropics*. Building Services Engineering Research and Technology, 2024.
  [DOI](https://doi.org/10.1177/01436244241231354) 
- PyTorch Documentation: https://pytorch.org/
- Scikit-learn Documentation: https://scikit-learn.org/

---

## 🛠️ How to Use

### 1. Clone the Repository
First, clone the repository to your local machine using the following command:

```bash
git clone https://github.com/username/indoor-airflow-predictor.git
cd indoor-airflow-predictor
```
### 1. Clone the Repository
First, clone the repository to your local machine using the following command:

```bash
git clone https://github.com/username/indoor-airflow-predictor.git
cd indoor-airflow-predictor
```
### 2. Install Dependencies
Ensure you have all necessary libraries installed by running:

```bash
pip install -r requirements.txt
```
### 3. Open the Jupyter Notebook
Start Jupyter Notebook and open the .ipynb file:

```bash
jupyter notebook
```


