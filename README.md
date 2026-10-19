# Bike Trips Analysis

## Project Overview

This project analyzes bike-sharing trip data to identify usage patterns, investigate customer behavior, and develop data-driven business recommendations.

The analysis includes data cleaning, exploratory data analysis (EDA), hypothesis testing, data visualization, and business insights aimed at improving bike-sharing operations.

## Objectives

- Clean and validate the original dataset.
- Explore trip patterns by time, weather, bike type, and user type.
- Test hypotheses about trip duration, distance, pricing, ratings, and technical issues.
- Visualize demand patterns using charts and a weekday-hour heatmap.
- Identify the five most popular routes under the selected route-ranking criteria.
- Develop business recommendations based on the analysis.

## Tools and Technologies

- **Python** — data analysis and processing
- **Pandas** — data cleaning, transformation, and aggregation
- **Matplotlib** — data visualization
- **Seaborn** — statistical visualization
- **Jupyter Notebook** — interactive analysis
- **Excel, CSV, and JSON** — data export formats

## Project Structure

```text
bike-trips-analysis/
├── Images/                     # Data visualizations
├── output/                     # Exported datasets
├── bike_trips_analysis.ipynb   # Main analysis notebook
├── bike_trips_dirty.csv        # Original dataset
├── requirements.txt            # Python dependencies
└── README.md                   # Project documentation
```

## Analysis Workflow

1. **Data Cleaning** — identified duplicates, missing values, inconsistent categories, invalid values, and potential outliers.
2. **Feature Engineering** — created additional time-related and analytical variables, including weekday, hour, weekend status, time of day, speed, and age group.
3. **Exploratory Data Analysis** — examined trip patterns across different user and bike categories.
4. **Hypothesis Testing** — investigated relationships involving trip duration, distance, pricing, weather, ratings, and technical issues.
5. **Data Visualization** — created comparison charts, trend charts, and a heatmap of trip counts by weekday and hour.
6. **Business Recommendations** — proposed opportunities to improve bike availability, customer engagement, electric bike adoption, and data quality.

## Key Findings

- **Demand patterns:** Trip activity varies by weekday and hour, with notable morning and evening peaks.
- **Bike type preference:** Standard bikes were used approximately 2.5 times as often as electric bikes.
- **Trip distance:** Electric bike trips had a higher average distance than standard bike trips (4.21 km versus 3.13 km).
- **Customer behavior:** Casual users had a higher average trip duration than subscribers (36.42 minutes versus 26.43 minutes).
- **Technical issues:** The observed technical issue rate was higher for electric bikes (5.14%) than for standard bikes (2.40%).

These findings describe patterns in the available dataset and do not necessarily establish causal relationships.

## Business Recommendations

The analysis generated several proposals for further evaluation:

- Promote electric bike adoption through trial rides and targeted discounts.
- Introduce reminders to help users end rentals when appropriate.
- Improve age validation and data quality during registration.
- Develop loyalty rewards for frequent subscribers.
- Test weather-based promotions and demand-based pricing.
- Encourage users to switch to subscriptions by communicating their potential benefits.

These proposals require further evaluation of financial impact, operational feasibility, and customer response before implementation.

## How to Run the Project

### 1. Clone or download the repository

Download the repository from GitHub and extract the files if necessary.

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Open the notebook

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open `bike_trips_analysis.ipynb` and run the cells from top to bottom.

The original dataset should remain available at the path expected by the notebook. Exported files are saved in the `output/` directory when the corresponding export cell is executed.

## Project Deliverables

- A Jupyter Notebook containing data cleaning, analysis, hypothesis testing, visualizations, and interpretations.
- Visualizations stored in the `Images/` directory.
- Cleaned datasets exported to CSV, JSON, and Excel formats.
- Business recommendations based on the observed data.

## Limitations

The analysis is based on the available dataset. Some values required cleaning or assumptions because their validity could not be confirmed. Observed associations should not be interpreted as proof of causation, and business recommendations should be validated through further testing.

---

**Project type:** Data Analytics  
**Focus:** Data Cleaning, Exploratory Data Analysis, Hypothesis Testing, Data Visualization, Business Insights
