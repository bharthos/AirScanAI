# 🌫️ AirScanAI: Air Quality Analysis & Prediction for Indian Cities

**AirScanAI** is an end-to-end data science project that analyzes daily air quality metrics across major Indian cities and builds predictive models to understand air pollution patterns. From cleaning raw data to visualizing trends and developing machine learning models, this project delivers an insightful look into the urban airscape of India.

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
│   ├── AIT614_Sec005_Team8_Databricks1
│   ├── AIT614_Sec005_Team8_JupyterNotebook
│   ├── AIT614_Sec005_Team8_EDA
│   └── AIT614_Sec005_Team8_MLModels
│
├── HTML/
    ├── AIT614_Sec005_Team8_Databricks1_HTML
    ├── AIT614_Sec005_Team8_JupyterNotebook_HTML
    ├── AIT614_Sec005_Team8_EDA_HTML
    └── AIT614_Sec005_Team8_MLModels_HTML
```

---

## 📊 Dataset Overview

- **Records**: 29,531  
- **Features**: 16  
- **Location**: Various Indian cities  
- **Focus Pollutants**: PM2.5, PM10, NOx  
- **Goal**: Compute and study AQI (Air Quality Index) and AQI Buckets.

---

## ⚙️ Requirements

- Python 3.x
- Databricks (for Spark-based workflows)
- Jupyter Notebook (preferred for local use)
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `sklearn`
  - `pyspark`

---

## 🚀 How to Run the Project

### 1️⃣ Data Cleaning: `AIT614_Sec005_Team8_Databricks1`

- Launch a cluster on **Databricks**.
- Upload the notebook and `city_day.csv` to DBFS.
- Replace the dataframe `df1` with your loaded data.
- Run the notebook to generate a **cleaned dataset**.

### 2️⃣ Data Filling: `AIT614_Sec005_Team8_JupyterNotebook`

- Use **Jupyter Notebook** or another IDE.
- Load the notebook and `data_cleaned.csv`.
- Replace file paths appropriately.
- Execute all cells to create the **filled dataset**.

### 3️⃣ Exploratory Data Analysis: `AIT614_Sec005_Team8_EDA`

- Use a local Python IDE (Jupyter preferred).
- Load the notebook and `Filled_data.csv`.
- Replace file paths.
- Run cells to generate **visualizations** and insights.

### 4️⃣ Machine Learning Models: `AIT614_Sec005_Team8_MLModels`

- Run in **Databricks** with a cluster.
- Upload notebook and `Filled_data.csv` to DBFS.
- Replace dataframe `df1` and run the notebook.
- View **model results** and performance metrics.

---

## 🌐 HTML Outputs

All Jupyter and Databricks notebooks have corresponding `.html` exports in the `HTML/` folder for easy preview of outputs without running the code.

---

## 🧠 Authors & Credits

Project by **AIT614 - Sec005 - Team 8**  
Data sourced from Indian air quality datasets  
Visualization and modeling done using Pandas, Seaborn, Sklearn, and Spark.

---

## 📌 Future Enhancements

- 📍 Geospatial AQI visualization (heatmaps)
- 📈 Time-series forecasting for air quality trends
- 🤖 Deployment of prediction models via a web app

---

## ⭐️ Show Your Support

If you find this repo helpful:

- ⭐ Star this repository
- 🍴 Fork it
- 🛠️ Use it for your own AQI projects
- 📬 Share feedback or improvements

---

> _“Breathe easy, code cleaner, and let the data tell the story.”_

