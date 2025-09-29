# 🌦️ Weather & Air Quality Time-Series Analysis

This project analyzes a **time-series dataset from the University of Tehran** and applies machine learning techniques to predict **rainfall and drought patterns** based on long-term atmospheric and air quality data.

## ✨ Project Highlights
- **Dataset**: Hourly air quality and pollutant data (`O3`, `NO`, `NO2`, `NOx`, `SO2`, `PM 2.5`) with timestamps (Persian calendar).  
- **Notebook**: `weather.ipynb` — contains preprocessing, exploratory analysis, and ML models.  
- **Models used**: Decision Trees, Random Forest, regression and classification approaches.  
- **Goals**:  
  - Task 1: Initial predictive modeling  
  - Task 2: Multi-level analysis approaches (2-level, 3-level)  
  - Task 3: Extended time-series evaluation  

## 🧱 Project Structure
```
weather.ipynb    # Main Jupyter notebook (analysis & modeling)
Time-Series-Dataset-University-of-Tehran.xlsx   # Input dataset (hourly pollutant data)
```

## 🔧 Requirements
- Python 3.8+
- Install dependencies:
```bash
pip install pandas numpy scipy scikit-learn jupyter
```

## 🚀 Usage
1. Launch Jupyter:
```bash
jupyter notebook
```
2. Open **`weather.ipynb`**.  
3. Run all cells to preprocess the dataset, visualize trends, and train ML models.  

## 📊 Dataset Info
- **Source**: University of Tehran (Report Data sheet)  
- **Columns**:  
  - تاریخ (Date, Persian calendar)  
  - ساعت (Hour)  
  - O3 (ppb), NO (ppb), NO2 (ppb), NOx (ppb), SO2 (ppb), PM 2.5 (µg/m³)

## 🎯 Research Context
This project was prepared as a **university research presentation**:  
- Presentors: Amirabbas RezaSoltani & Amin Ariafar  
- Supervisor: Dr. Abdollah Safari  
- Institution: **University of Tehran**, Summer 2024

---

Made for research & learning 📚 — demonstrating how time-series analysis and ML can be applied to environmental studies.
