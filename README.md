# 🚗 Traffic Accident Data Analysis (Task-05)

## 📌 Project Overview
This project analyzes traffic accident data using Exploratory Data Analysis (EDA) techniques to identify patterns, trends, and key factors contributing to road accidents. The dataset used contains information such as time, location, weather conditions, and severity of accidents.

---

## 📊 Objectives
- Analyze accident trends over time (hour, day, month)
- Identify accident hotspots using geospatial visualization
- Study the impact of weather conditions on accidents
- Understand road-related factors contributing to accidents
- Visualize accident severity distribution

---

## 📂 Dataset
The dataset used is the **US Accidents dataset** from Kaggle:
- Source: https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents
- Contains information about:
  - Time of accident
  - Location (latitude, longitude)
  - Weather conditions
  - Road features
  - Severity level

---

## 🛠️ Technologies Used
- Python 🐍
- Pandas 📊
- NumPy 🔢
- Matplotlib 📈
- Seaborn 🎨
- Folium 🌍 (for heatmaps)
- Jupyter Notebook 📓

---

## 📌 Steps Performed

### 1. Data Loading & Cleaning
- Imported dataset using Pandas
- Handled missing values
- Converted time columns into datetime format

### 2. Feature Engineering
- Extracted Hour, Day, and Month from time column
- Selected important road-related features

### 3. Exploratory Data Analysis (EDA)

#### ⏰ Time Analysis
- Accidents by hour of the day
- Accidents by day of the week

#### 🌦️ Weather Analysis
- Most common weather conditions during accidents

#### 🛣️ Road Features
- Contribution of road elements like traffic signals, junctions, crossings, etc.

#### ⚠️ Severity Analysis
- Distribution of accident severity levels

### 4. Geospatial Analysis
- Created heatmap to identify accident hotspots
- Visualized high-risk accident zones

---

## 📈 Key Insights
- Most accidents occur during peak traffic hours (morning & evening)
- Weekdays show higher accident rates than weekends
- Clear and cloudy weather conditions have the highest accident counts
- Urban areas and highways are major accident hotspots
- Traffic signals and junctions contribute significantly to accidents

---

## 📊 Visualizations Included
- Accidents by Hour of Day
- Accidents by Day of Week
- Weather Condition Analysis
- Road Feature Impact Analysis
- Accident Severity Distribution
- Accident Hotspot Heatmap (Folium)

---
