# 🔬 ResisNO: ML-Based Nitric Oxide Estimation from Sensor Resistance

A machine learning-based solution that predicts **Nitric Oxide (NO)** gas concentration from **sensor resistance data** collected over time. This project demonstrates the power of real-time sensing combined with data-driven modeling for environmental and health monitoring applications.

---

## 📌 Project Overview

This project utilizes a real-time dataset comprising the **resistance values of an NO-sensitive sensor** exposed to a gas mixture over time. The aim is to estimate the **NO concentration (in ppb)** using ML techniques trained on this resistance data.

---

## 🧠 Key Features

- 📈 Real-time resistance data analysis
- 🤖 ML model trained to predict NO concentration
- 📁 End-to-end data pipeline in a single Jupyter Notebook
- 🧪 Ready for future integration with hardware/sensors

---

## 🗂 Dataset Description

The dataset contains:
- **Time (s)**: Time in seconds during gas exposure
- **Sensor Resistance (Ω)**: Measured resistance values from the NO sensor
- **NO Concentration (ppb)**: Ground truth concentration of NO gas

---

## 🧮 Machine Learning Approach

- **Input Features**:
  - Time (s)
  - Sensor resistance (Ω)
- **Target**:
  - NO Concentration (ppb)
- **Models Tried**:
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting
- **Final Selection**:
  - [Your chosen model from the notebook]

---

## 📒 Notebook Contents

The main notebook walks through:
1. Data preprocessing and cleaning
2. Feature selection and engineering
3. Model training and evaluation
4. NO concentration prediction
5. Visualization of results

---

## 🛠️ How to Run

1. Clone the repo or download the notebook:
   ```bash
   git clone https://github.com/adityajoshi1362/your-repo-name.git
