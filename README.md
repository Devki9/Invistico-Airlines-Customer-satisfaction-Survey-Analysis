# Customer Satisfaction Survey Analysis

## Project Description
This project analyzes customer satisfaction survey data from the **Invistico Airline** dataset obtained from Kaggle. The objective is to identify the factors that influence customer satisfaction by cleaning, analyzing, and visualizing airline survey data using Python. The project demonstrates the complete data science workflow, including data cleaning, exploratory data analysis, visualization, and interpretation of results to support data-driven decision-making.

## Problem Statement
Airlines collect large amounts of customer feedback, but without proper analysis it is difficult to identify the factors that influence passenger satisfaction. This project aims to analyze airline customer survey data to determine how factors such as travel class, travel type, delays, and onboard services affect overall customer satisfaction.

## Dataset
- Source: Invistico Airline Customer Satisfaction Dataset (Kaggle)
- Number of rows: 129,880
- Number of columns: 23
- Key columns: `satisfaction`, `Customer Type`, `Type of Travel`, `Class`, `Flight Distance`, `Seat comfort`, `Inflight entertainment`, `Departure Delay in Minutes`, `Arrival Delay in Minutes`

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Data Cleaning
- Removed duplicate records.
- Handled missing values.
- Renamed column names for consistency.
- Standardized text values.
- Created a new **Total Delay** column by combining departure and arrival delays.
- Handled outliers where appropriate.

## Analysis Questions
- What is the distribution of customer satisfaction?
- Does travel class influence customer satisfaction?
- Does travel type affect customer satisfaction?
- How do flight delays relate to customer satisfaction?
- Which services receive the highest customer ratings?

## Visualizations
- **Bar Chart** – compares satisfaction levels across categories such as travel class and travel type.
- **Pie Chart** – shows the overall proportion of satisfied vs. dissatisfied customers.
- **Histogram** – displays the distribution of numerical variables such as age and flight distance.
- **Scatter Plot** – examines the relationship between delays and satisfaction.
- **Box Plot** – highlights the spread and outliers in delay and rating data across groups.
- **Heatmap** – visualizes correlations between service ratings and satisfaction.

## Key Insights
- Business class passengers generally reported higher satisfaction levels than economy passengers.
- Business travellers were more satisfied than personal travellers.
- Longer delays were associated with lower customer satisfaction.
- Some onboard services, such as seat comfort and inflight entertainment, received higher average ratings than others.
- Overall, the dataset contained more satisfied customers than dissatisfied customers.

## Recommendations
- Prioritize improvements to onboard services with lower ratings, such as inflight wifi and food and drink.
- Invest in initiatives that minimize departure and arrival delays, given their strong link to dissatisfaction.
- Tailor service offerings for economy and personal-travel passengers to close the satisfaction gap with business class and business travellers.
- Continue monitoring satisfaction trends over time to catch emerging issues early.
- Consider deeper segmentation (e.g., by age or flight distance) to personalize service improvements.

## How to Run the Project
1. Clone the repository
2. Install requirements
3. Open the notebook
4. Run all cells

## Author
Devki Chavda (678097)
Daniel Ngunya Maina (202603199)
