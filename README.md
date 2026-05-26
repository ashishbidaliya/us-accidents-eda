# US Accidents Exploratory Data Analysis

This project performs Exploratory Data Analysis (EDA) on the US Accidents Dataset (2016–2023).

The objective of this project is to:

- analyze accident patterns across the United States
- identify accident-prone cities and regions
- study accident trends over time
- visualize geographical accident distributions
- derive useful insights from large-scale accident data

Dataset Source:

- Kaggle
- US Accidents Dataset (2016–2023)

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Folium
- Jupyter Notebook

---

# Project Structure

```text
US-ACCIDENTS-EDA/
│
├── data/
│   ├── raw/
│   │   └── US_Accidents_March23.csv
│   │
│   └── processed/
│
├── images/
│
├── notebooks/
│   ├── 01-data-preparation-and-cleaning.ipynb
│   ├── 02-missing-values-analysis.ipynb
│   ├── 03-city-analysis.ipynb
│   ├── 04-time-analysis.ipynb
│   ├── 05-source-analysis.ipynb
│   ├── 06-geospatial-analysis.ipynb
│   ├── 07-questions-and-insights.ipynb
│   └── workspace.ipynb
│
├── reports/
│
├── venv/
│
├── .gitignore
├── README.md
└── requirements.txt
```

---

# Analysis Performed

## 1. Data Preparation and Cleaning

- Loaded dataset using Pandas
- Explored dataset structure
- Analyzed datatypes and numeric columns

## 2. Missing Values Analysis

- Calculated missing value percentages
- Visualized missing value distribution

## 3. City Analysis

- Identified cities with highest accident counts
- Analyzed accident distribution across cities

## 4. Time Analysis

- Analyzed accidents by:
  - hour
  - weekday
  - month
  - year
- Compared weekday vs weekend accident patterns

## 5. Source Analysis

- Analyzed accident reporting sources
- Compared source distributions

## 6. Geospatial Analysis

- Visualized accident coordinates
- Created scatter plots
- Created heatmaps using Folium

## 7. Questions and Insights

- Explored important business and analytical questions
- Derived conclusions from accident trends

---

# Key Insights

- Accident counts decrease exponentially across cities
- Peak accident timings are:
  - 6 AM to 10 AM
  - 3 PM to 6 PM
- Weekdays show higher accident frequency than weekends
- Large accident clusters appear around highly populated regions
- Some inconsistencies exist across different accident data sources
- No significant New York data was found in this dataset version

---

# How To Run

## Clone Repository

```bash
git clone <repository-url>
```

## Move Into Project Directory

```bash
cd US-ACCIDENTS-EDA
```

## Create Virtual Environment

```bash
python -m venv venv
```

## Activate Virtual Environment

### Windows

```bash
venv\Scripts\activate
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# Dataset

Dataset used:

- US Accidents Dataset (2016–2023)
- Source: Kaggle

The dataset contains millions of accident records collected from multiple traffic and accident reporting sources across the United States.

---

# Future Improvements

- Weather-based accident analysis
- State-wise accident analysis
- Machine learning prediction models
- Interactive dashboards
- Advanced geospatial visualizations
