# 🔋 Electric Vehicle Specification Analysis (2025)

This project presents a complete data cleaning and exploratory analysis of electric vehicle (EV) specifications for 2025. Using Python, Pandas, and visualization libraries, it explores performance indicators like range, torque, towing capacity, charging power, and overall suitability for long-distance driving.

---

## 📁 Dataset Overview

- **Datset Source:** [Electric Vehicle Specs Dataset (2025)](https://www.kaggle.com/datasets/urvishahir/electric-vehicle-specifications-dataset-2025/data)
- **Rows:** 475  
- **Columns:** 22  
- **Fields Include:**
  - `brand`, `model`, `battery_capacity_kWh`, `range_km`, `efficiency_wh_per_km`, `torque_nm`, `towing_capacity_kg`, `fast_charging_power_kw_dc`, `car_body_type`, and more.

---

## 🧹 Data Cleaning Summary

- Dropped one unnamed record with null `model`
- Filled missing values in `number_of_cells` with `-1`
- Verified data types and removed all nulls and duplicates

---

## 📊 Exploratory Analysis Highlights

### 🔸 Top Range EVs
Identified top 10 models with the highest range (`range_km`)

### 🔸 Pulling Power Leaders
Created a new metric `pulling_power = torque + towing_capacity` to rank models and brands

### 🔸 Long-Distance Friendly EVs
Combined range and fast charging power to rank models suitable for road trips

---

## 📌 Key Questions Answered

- Which EVs have the longest range?
- Which manufacturers prioritize torque and towing?
- Which cars are best suited for long-distance travel?
- How does efficiency vary across brands or segments?

---

## 📈 Tools & Libraries

- Python
- Pandas
- Matplotlib
- Seaborn

---

## 📎 Folder Structure

```bash
ev-spec-analysis-2025/
├── cleaning-ev-spec-analysis.ipnyb
├── Project-ev-spec-analysis.ipynb
├── README.md


