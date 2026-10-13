# Weather Data Analysis Using Python

## 📌 Project Overview

This project focuses on analyzing weather data using Python libraries such as **Pandas, NumPy, and Matplotlib**. The goal is to explore weather patterns, calculate descriptive statistics, compare monthly and seasonal weather conditions, and identify extreme weather observations.

The project demonstrates essential data analysis skills, including data cleaning, data manipulation, statistical analysis, and data visualization.

## 🎯 Objectives

- Load and explore weather data using Pandas.
- Clean and prepare the dataset for analysis.
- Calculate mean, median, and standard deviation using NumPy.
- Analyze monthly and seasonal weather patterns.
- Visualize temperature and precipitation trends using Matplotlib.
- Identify extreme temperature and precipitation observations.
- Summarize key insights from the analysis.

## 📂 Dataset Information

The dataset contains weather observations from multiple locations around the world.

**Dataset details:**
- **Original records:** 170,538
- **Locations:** 268 unique locations
- **Date range:** May 16, 2024 – October 11, 2026
- **Selected columns:** 6

### Key Columns

| Column | Description |
|---|---|
| `last_updated` | Date and time of the weather observation |
| `country` | Country associated with the location |
| `location_name` | Name of the location |
| `temperature_celsius` | Temperature in degrees Celsius |
| `humidity` | Humidity percentage |
| `precip_mm` | Precipitation in millimeters |

## 🛠️ Tools and Technologies

- **Python** – Programming and data analysis
- **Google Colab** – Notebook development and execution
- **Pandas** – Data cleaning, manipulation, and grouping
- **NumPy** – Statistical calculations and percentile analysis
- **Matplotlib** – Data visualization
- **GitHub** – Project hosting and version control

## 🔍 Project Workflow

1. **Data Loading and Exploration:** Load the dataset and inspect its structure, columns, and data types.
2. **Data Cleaning:** Check missing values and duplicates, and convert the date column into datetime format.
3. **Feature Engineering:** Extract year, month, month name, and season from the observation date.
4. **Descriptive Statistics:** Calculate the mean, median, and standard deviation of temperature, humidity, and precipitation.
5. **Monthly Analysis:** Compare monthly average temperature, average humidity, and precipitation.
6. **Seasonal Analysis:** Examine weather patterns across the defined seasons.
7. **Data Visualization:** Create charts to explore temperature and precipitation patterns.
8. **Extreme Weather Analysis:** Identify observations with extreme temperatures and high precipitation using percentile thresholds.
9. **Key Findings:** Summarize the results of the analysis.

## 📊 Visualizations

The project includes the following visualizations:

- **Line Plot:** Monthly average temperature over time.
- **Bar Chart:** Total precipitation by calendar month.
- **Histogram:** Distribution of temperature observations.
- **Seasonal Comparison Chart:** Average temperature by season.

## 📈 Key Analysis

The analysis explores:

- Temperature variation across the dataset.
- Differences in average humidity between months and seasons.
- Monthly and seasonal precipitation patterns.
- The distribution of temperature observations.
- The warmest, coolest, and highest-precipitation records.
- Observations that fall within extreme temperature and heavy precipitation thresholds.

Actual numerical findings should be added after completing and validating the analysis.

## ⚠️ Limitations

- The dataset includes multiple locations, so overall averages combine observations from different places.
- The seasonal categories used in this project follow a predefined calendar and may not represent the actual seasons in every country.
- Percentile-based extreme weather thresholds are relative to this dataset and are not official meteorological warning thresholds.
- The monthly precipitation totals combine observations across multiple years and locations.

## 💡 Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Statistical analysis with NumPy
- Data aggregation using Pandas `groupby()`
- Date and time feature engineering
- Data visualization using Matplotlib
- Interpreting analytical results
- Python programming

## 🚀 How to Explore the Project

1. Open the Python notebook (`.ipynb`) in this repository.
2. Open it in Google Colab or Jupyter Notebook.
3. Upload or load the dataset required by the notebook.
4. Run the cells in order to reproduce the analysis and visualizations.

## 👩‍💻 Author

**Pranita Shirsekar**

Aspiring Data Analyst | Python | Pandas | NumPy | Matplotlib

---

*This project was developed as part of my Python data analysis learning journey.*
