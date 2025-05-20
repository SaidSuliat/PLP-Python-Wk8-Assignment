# 🦠 COVID-19 Global Data Tracker

## 📌 Project Overview

The **COVID-19 Global Data Tracker** is a data analysis project that uses real-world COVID-19 data to visualize and compare global trends in cases, deaths, and vaccinations over time. The project is implemented in a well-documented Jupyter Notebook using Python and popular data libraries.

This analysis provides both visual insights and narrative summaries, making it ideal for presentations, reports, or dashboards.

---

## 🎯 Objectives

- ✅ Import and clean COVID-19 global data  
- ✅ Analyze time trends (cases, deaths, vaccinations)  
- ✅ Compare key metrics across countries/regions  
- ✅ Visualize trends with line charts, bar plots, and maps  
- ✅ Summarize findings in a report format using markdown  

---

## 📊 Key Features

- Compare COVID-19 data across selected countries (e.g., USA, India, Kenya)  
- Track trends in total cases, deaths, and vaccination rates  
- Calculate critical metrics such as death rates  
- Optional interactive choropleth map of global cases  
- Generate insights with narrative explanations using markdown  

---

## 🗂️ Project Structure

```

COVID-19-Global-Data-Tracker/
│
├── owid-covid-data.csv                # Source dataset (Our World in Data)
├── COVID-19\_Global\_Data\_Tracker.ipynb # Main Jupyter Notebook
├── README.md                          # Project documentation
└── output/                            # (Optional) Folder for visuals or reports

````

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/COVID-19-Global-Data-Tracker.git
cd COVID-19-Global-Data-Tracker
````

### 2. Install Required Libraries

Ensure Python 3.x is installed. Then install dependencies:

```bash
pip install pandas matplotlib seaborn plotly jupyter
```

### 3. Run the Notebook

```bash
jupyter notebook
```

Open `COVID-19_Global_Data_Tracker.ipynb` and run the cells sequentially.

---

## 📈 Sample Visuals

* 📉 Line charts: Cases & deaths over time
* 📊 Bar charts: Top countries by cases
* 🌍 Choropleth map: Case density by country (optional with Plotly)

---

## 📌 Data Source

* [Our World in Data - COVID-19 Dataset](https://ourworldindata.org/coronavirus-source-data)

---

## 💡 Insights

> * The United States consistently reported the highest total case count.
> * India showed a significant surge in vaccinations from mid-2021.
> * Kenya maintained a relatively lower death rate compared to total cases.

---
