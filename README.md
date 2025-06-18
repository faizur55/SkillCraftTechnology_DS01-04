# 🚧 US Traffic Accidents (2016–2023) — A Data Science Case Study

## 📌 Project Overview
A comprehensive data science project analyzing 7.7M+ traffic accidents across the US from 2016 to 2023. This project uncovers key insights, predicts accident severity, and presents data visually for real-world impact.

## 🔍 Objective
- Understand patterns behind traffic accidents.
- Identify contributing factors like weather, time, location, and road conditions.
- Build ML models to predict accident severity.
- Present actionable insights through maps, plots, and dashboards.

## 📁 Dataset
- Source: [US Accidents - S.Moosavi](https://smoosavi.org/datasets/us_accidents)
- Records: 7.7 million+
- Features: 47 columns — including date/time, location, weather, road conditions, etc.

## 📊 Project Phases

### 🔹 Phase 1: Data Loading & Initial Exploration
- Loaded 2.87GB+ dataset via Google Drive mount in Colab.
- Explored datatypes, missing values, sample records.

### 🔹 Phase 2: Data Cleaning
- Handled missing values, null-heavy columns, incorrect data.
- Converted columns to proper data types.

### 🔹 Phase 3: EDA – Univariate & Bivariate
- Severity distribution
- Time, weather, visibility, pressure analysis
- Grouped bar charts and proportions

### 🔹 Phase 4: Geo-Spatial Mapping
- Choropleth maps (state/city-wise accidents)
- Heatmaps of dense accident areas

### 🔹 Phase 5: Time-Series Analysis
- Trends by year, month, day of week, hour
- Visualized peaks in accidents using line & bar plots

### 🔹 Phase 6: Machine Learning (Severity Prediction)
- Preprocessed categorical, boolean & numerical data
- Trained models:
  - Logistic Regression
  - Random Forest
  - XGBoost
  - Decision Tree, SVM, KNN
- Evaluated using F1-Score, Accuracy, Confusion Matrix

### 🔹 Phase 7: Final Analysis & Model Comparison
- Compared multiple models
- Explored:
  - Location trends (State, County, City)
  - Weather impact
  - Road features (Junctions, Signals)
  - Day vs. Night comparison
  - Top cities with highest severity
  - Correlation heatmaps

---

## 📈 Key Insights

- ❗ California & Florida report the highest accident counts.
- 🌙 More accidents occur at night, but day accidents are more severe.
- 🌧️ Poor weather, especially fog and rain, correlate with higher severity.
- 🚦 Accidents are more common at crossings, junctions, and traffic signal points.
- 🌡️ Low visibility and wind speed contribute to accident severity.

---

## 🤖 Best Performing Model
**Random Forest Classifier**
- Accuracy: ~75%
- F1 Score (Severity=2 vs. 3): Strong balance
- Handles class imbalance and feature importance well.

---

## 📌 Tools Used

- Python (Pandas, Matplotlib, Seaborn, Plotly)
- GeoPandas, Folium
- Scikit-learn, XGBoost
- Google Colab
- GitHub for version control

---

## 📊 Future Work
- Streamlit dashboard for real-time interaction
- Deploy severity predictor as an API
- Add deep learning models for better accuracy
