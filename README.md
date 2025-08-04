# 🚦 Accident Data Analysis Dashboard

## 📊 Project Overview

Road traffic accidents remain a persistent public safety challenge globally. This project leverages statistical analysis and interactive data visualization to identify key patterns in road accident data and recommend actionable safety measures.

The core goal is to support data-driven decision-making for reducing accident severity and frequency through detailed analysis of speed limits, road conditions, weather patterns, and vehicle involvement.

## 🧰 Tools & Technologies
- Python (Pandas, Matplotlib, Seaborn)
- Microsoft Excel
- Power BI / Tableau (Dashboard Visualization)
- Jupyter Notebooks
- Statistical Analysis: Correlation, Descriptive Statistics

## 📂 Project Structure
├── data/ # Cleaned and raw datasets
├── notebooks/ # Jupyter notebooks for analysis
├── dashboard/ # Dashboard video or screenshots
├── presentation/ # Final PowerPoint slides
├── README.md # Project overview and documentation

## 🔍 Key Analyses & Insights

### ➤ Descriptive Statistics
- **Casualties per Accident**:  
  - Mean: 1.36 | Median: 1 | Std Dev: 0.82  
  - Insight: Most incidents involve a single injury, but rare multi-casualty events skew the average.
- **Vehicles per Accident**:  
  - Mean: 1.82 | Median: 2  
  - Insight: Two-vehicle collisions dominate the dataset, indicating the need for better collision prevention.
- **Speed Limits**:  
  - Mean: 38.87 mph | Median: 30 mph  
  - Insight: Risk increases with speed; some zones exceed safe thresholds.

### ➤ Correlation Analysis
- Casualties ↔ Vehicles: **0.234**  
- Casualties ↔ Speed Limit: **0.137**  
- Vehicles ↔ Speed Limit: **0.080**  
  - Interpretation: Weak correlations suggest that while speed and vehicle count are contributing factors, accidents are complex and multifactorial.

### ➤ Impact Analyses
- **Speed Limits & Accident Severity**
- **Weather Conditions & Road Surface Quality**
- **Trend Forecasting** using exploratory models to predict future accident rates

## 📈 Dashboard Highlight

A dynamic dashboard has been created to visually present:
- Time-based accident trends
- High-risk zones
- Severity by weather and road conditions
- Filtering by speed limits, accident types, and vehicle involvement

> 🎥 # 🚦 Accident Data Analysis Dashboard

## ✅ Recommendations

Based on insights from the analysis, we propose:
- **Policy Review**: Reassess speed limits in high-risk zones
- **Infrastructure Upgrades**: Better lighting, high-friction surfacing, improved drainage
- **Enforcement & Monitoring**: Stricter traffic law enforcement
- **Public Awareness**: Targeted campaigns on wet-weather driving and junction safety

## 📌 Conclusion

This analysis demonstrates that data can be a powerful tool in shaping safer transportation systems. While many accidents involve only minor injuries, targeted intervention at high-risk intersections and under poor weather conditions can yield major safety improvements.
---

