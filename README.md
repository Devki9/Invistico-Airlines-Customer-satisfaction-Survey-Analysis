# Customer Satisfaction Survey Analysis

## Project Overview
This project analyzes customer satisfaction survey data from the **Invistico Airline** dataset obtained from Kaggle. The objective is to identify the factors that influence customer satisfaction by cleaning, analyzing, and visualizing airline survey data using Python.

The project demonstrates the complete data science workflow, including data cleaning, exploratory data analysis, visualization, and interpretation of results to support data-driven decision-making.


## Problem Statement
Airlines collect large amounts of customer feedback, but without proper analysis it is difficult to identify the factors that influence passenger satisfaction.

This project aims to analyze airline customer survey data to determine how factors such as travel class, travel type, delays, and onboard services affect overall customer satisfaction.


## Objectives
- Clean and prepare the dataset for analysis.
- Perform exploratory data analysis (EDA).
- Identify patterns and trends affecting customer satisfaction.
- Create meaningful visualizations.
- Draw conclusions and provide recommendations based on the findings.


## Dataset
**Dataset:** Invistico Airline Customer Satisfaction Dataset
**Source:** Kaggle
The dataset contains customer demographic information, flight details, service ratings, delays, and customer satisfaction responses.


## Technologies Used
- Python (Pandas, NumPy, Matplotlib)
- Google Colab
- Seaborn
- Git
- GitHub

## Setup
pip install -r requirements.txt

## Data Cleaning
The following data cleaning steps were performed:
- Removed duplicate records.
- Handled missing values.
- Renamed column names for consistency.
- Standardized text values.
- Created a new **Total Delay** column by combining departure and arrival delays.
- Handled outliers where appropriate.


## Exploratory Data Analysis
The analysis included:
- Filtering
- Sorting
- Grouping
- Aggregation
- Value Counts
- Summary Statistics

Key questions explored included:
- What is the distribution of customer satisfaction?
- Does travel class influence customer satisfaction?
- Does travel type affect customer satisfaction?
- How do flight delays relate to customer satisfaction?
- Which services receive the highest customer ratings?


## Data Visualizations
The project includes the following visualizations:
- Bar Chart
- Pie Chart
- Histogram
- Scatter Plot
- Box Plot
- Heatmap
These visualizations were used to identify trends and relationships within the dataset.


## Project Structure
```
Invistico-Airline-Customer-Satisfaction-Survey-Analysis/
│
├── data/
│   ├── Invistico_Airline.csv
│   └── Cleaned_Invistico_Airline.csv
│
├── notebooks/
│   └── Group Work(3)(1).ipynb
│
├── visuals/
│   ├── bar_chart.png
│   ├── pie_chart.png
│   ├── histogram.png
│   ├── scatter_plot.png
│   ├── box_plot.png
│   └── heatmap.png
│
├── presentation/
│   └── final_presentation.pdf
│
├── README.md
└── requirements.txt
```

## Key Findings
- Business class passengers generally reported higher satisfaction levels.
- Business travellers were more satisfied than personal travellers.
- Longer delays were associated with lower customer satisfaction.
- Some onboard services, such as seat comfort and inflight entertainment, received higher average ratings than others.
- Overall, the dataset contained more satisfied customers than dissatisfied customers.



## Conclusion
The analysis shows that customer satisfaction is influenced by several factors, including travel class, purpose of travel, flight delays, and service quality. By understanding these factors, airlines can make informed decisions to improve customer experience and increase passenger satisfaction.


## Future Improvements
Possible extensions of this project include:
- Building a machine learning model to predict customer satisfaction.
- Creating an interactive dashboard using Power BI or Tableau.
- Performing customer segmentation based on travel behaviour.
- Comparing satisfaction across different airlines.

## Authors
Student Names
Devki Chavda (678097)
Daniel Ngunya Maina (202603199)


## License
This project was developed for academic purposes as part of an Introduction to Data Science programming project.