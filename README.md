# 🐟 Fish Species Classification from Real-Time Pond Water Data

This project explores real-time water quality monitoring and fish species classification using machine learning. The dataset was generated using an IoT setup with pH, temperature, and turbidity sensors. The goal is to predict which fish species are likely present based on water parameters.

---

## 📦 Dataset

- **Source**: [Real-Time Pond Water Dataset for Fish Farming - Kaggle](https://www.kaggle.com/datasets/monirmukul/realtime-pond-water-dataset-for-fish-farming?utm_source=chatgpt.com)
- **Published Paper**:  
  Islam, Md Monirul. *"Real-time dataset of pond water for fish farming using IoT devices."*  
  *Data in Brief*, Volume 51, 2023, 109761  
  [Link to Paper](https://www.sciencedirect.com/science/article/pii/S2352340923008302)

### 📄 Dataset Description

- **Total Samples**: 591 rows
- **Columns**:
  - `ph`: Water pH value
  - `temperature`: Temperature in °C
  - `turbidity`: Water turbidity level
  - `fish`: Fish species (target class; 11 unique categories)

- **Data Collected Using**:
  - IoT system based on Arduino with pH, turbidity, and temperature sensors
  - Real-time monitoring of 5 ponds in a fish farming setup

---

## 🎯 Project Objectives

1. Visualize the distribution and relationships in the dataset
2. Explore environmental preferences for different fish species
3. Build a predictive model to classify fish species based on water parameters

---

## 📊 Exploratory Data Analysis (EDA)

### 1. Fish Type Distribution
- Bar chart (counts)
- Pie chart (proportions)

### 2. Boxplots
- pH vs. Fish
- Temperature vs. Fish
- Turbidity vs. Fish

### 3. Correlation Heatmap
- Explore relationships between pH, temperature, and turbidity

---

## 🤖 Predictive Modeling

- Model: **Random Forest Classifier**
- Input: pH, Temperature, Turbidity
- Output: Fish type
- Performance: ~90% accuracy
- Evaluation: Confusion Matrix

---

## 🛠️ Tools and Libraries

- Python 3.x
- pandas, matplotlib, seaborn
- scikit-learn (for machine learning)

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fish-species-classification.git
   cd fish-species-classification
