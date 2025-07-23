# 🌫️ AirScanAI: Air Quality Analysis & Prediction for Indian Cities

**AirScanAI** is a full-stack data science project designed to analyze and predict air quality trends across major Indian cities. Leveraging a rich dataset of pollutants and environmental metrics, the project cleans, visualizes, and models air pollution behavior using both local and cloud-based tools.

---

## 📁 Folder Structure

```
AirScanAI/
│
├── datasets/
│   ├── city_day.csv
│   ├── data_cleaned.csv
│   └── Filled_data.csv
│
├── code/
│   ├── DataCleaning_Databricks.ipynb
│   ├── DataFilling_LocalNotebook.ipynb
│   ├── EDA_AirQualityAnalysis.ipynb
│   └── MLModeling_AQI_Prediction.ipynb
│
├── HTML/
    ├── DataCleaning_Databricks.html
    ├── DataFilling_LocalNotebook.html
    ├── EDA_AirQualityAnalysis.html
    └── MLModeling_AQI_Prediction.html
```

---

## 📊 Dataset Overview

- **Records**: 29,531  
- **Features**: 16  
- **Location**: Multiple Indian cities  
- **Core Pollutants**: PM2.5, PM10, NOx  
- **Purpose**: Calculate AQI and classify air quality levels across regions and time

---

## ⚙️ Requirements

- Python 3.x
- Databricks (for distributed computing)
- Jupyter Notebook (preferred for local use)
- Required Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `sklearn`
  - `pyspark`

---

## 🚀 How to Run the Project

### 1️⃣ Data Cleaning (Databricks)

**File**: `01_DataCleaning_Databricks.ipynb`

- Create a Databricks cluster
- Upload `city_day.csv` to DBFS
- Load and run the notebook
- Output: `data_cleaned.csv`

---

### 2️⃣ Data Filling (Local Notebook)

**File**: `02_DataFilling_LocalNotebook.ipynb`

- Use Jupyter Notebook or other IDEs (e.g., VS Code)
- Load the notebook and `data_cleaned.csv`
- Replace the file path in the code
- Output: `Filled_data.csv`

---

### 3️⃣ Exploratory Data Analysis (EDA)

**File**: `03_EDA_AirQualityAnalysis.ipynb`

- Run in Jupyter or any Python IDE
- Use `Filled_data.csv` as input
- Outputs: Visualizations and insights on air pollution distribution

---

### 4️⃣ Machine Learning Modeling

**File**: `04_MLModeling_AQI_Prediction.ipynb`

- Use Databricks for running the notebook
- Upload `Filled_data.csv` to DBFS
- Run the notebook to train and evaluate ML models
- Output: Model performance metrics and predictions

---

## 🌐 HTML Outputs

Each notebook has a corresponding `.html` version available in the `HTML/` folder for quick viewing of outputs and results.

---

## 🧠 Authors & Credits

Created by **AIT614 - Sec005 - Team 8**  
This project uses open air quality datasets and applies various data science techniques for environmental analysis and modeling.

---

## 📌 Future Enhancements

- 🌍 Geospatial AQI heatmaps
- ⏳ Time-series forecasting of pollutant levels
- 🌐 Deployment of ML model via Flask or Streamlit

---

## ⭐️ Show Your Support

If this project adds value:

- ⭐ Star the repo  
- 🍴 Fork it  
- 🛠️ Contribute improvements  
- 🗣️ Share your thoughts  

---

> _“Breathe cleaner. Code smarter. Let the air tell its story.”_
