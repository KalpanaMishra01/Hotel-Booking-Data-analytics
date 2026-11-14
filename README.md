Hotel Booking Data Analysis

Project Overview

This project focuses on analysing hotel booking data to understand booking patterns, customer behaviour, cancellations, and other important business trends.

Objectives

- Perform data cleaning and preprocessing.
- Conduct Exploratory Data Analysis (EDA).
- Create meaningful data visualizations.
- Develop an interactive Power BI dashboard.
- Identify business insights and recommendations.

Tools & Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook
- Power BI
- Git and GitHub

Project Status

Currently in progress as part of the InternNova Data Analytics Internship.

Dataset Description

The project uses the Hotel Booking Demand dataset from Kaggle.

- Original records: 119,390
- Original columns: 32
- Cleaned records: 87,395
- Final columns: 35

The dataset contains hotel type, arrival dates, customer details, market segments, lead time, length of stay, ADR, and booking cancellation information.

Problem Statement

Hotel businesses face challenges related to booking cancellations, seasonal demand, and changing customer booking behaviour.

This project aims to analyse historical hotel booking data, identify important patterns, and provide insights that can help hotels improve their planning and decision-making.

Data Cleaning and Preprocessing

The dataset was inspected for missing values, duplicate records, incorrect values, and data types.

The following steps were performed:

- Removed 31,994 duplicate records.
- Handled missing values in children and country columns.
- Filled missing agent and company values with 0.
- Removed one record with a negative ADR.
- Retained unusually high ADR values for further analysis.
- Converted reservation status dates into datetime format.
- Created new features: total guests and total nights.

The final cleaned dataset contains 87,395 records and 35 columns, with no missing values or duplicate rows.

Exploratory Data Analysis (EDA)

EDA was performed using Python to understand booking patterns and customer behaviour.

The analysis covered:

- Hotel-wise booking distribution.
- Cancellation analysis.
- Monthly booking trends.
- Market segment and customer type analysis.
- Length of stay and ADR distribution.
- Correlation analysis.
- Outlier detection.

Visualizations

Seven visualizations were created using Matplotlib and Seaborn:

1. Bookings by Hotel Type
2. Cancellation Rate by Hotel
3. Monthly Booking Distribution
4. Bookings by Market Segment
5. Total Nights Distribution
6. ADR Distribution
7. Correlation Heatmap

The charts are saved in the "visualizations" folder.

Power BI Dashboard

An interactive dashboard was developed using Power BI Desktop.

It includes three KPI cards:

- Total Bookings
- Cancellation Rate
- Average ADR

The dashboard also contains charts for hotel-wise bookings, cancellation rates, monthly booking distribution, and market segment analysis.

Slicers for Hotel Type, Arrival Year, and Market Segment allow users to explore the data interactively.

Key Business Insights

- City Hotels recorded 53,428 bookings, compared to 33,967 for Resort Hotels.
- City Hotels had a higher cancellation rate of 30.04%, compared to 23.48% for Resort Hotels.
- Online TA contributed 51,618 bookings and had a cancellation rate of 35.35%.
- August recorded the highest number of bookings (11,257), followed by July (10,057).
- Transient customers formed the largest customer group, with 71,986 bookings.
- Resort Hotel guests stayed for an average of 4.39 nights, compared to 3.15 nights at City Hotels.

Business Recommendations

- Improve booking confirmations and send timely reminders, particularly for Online TA bookings, to help reduce cancellations.
- Plan staff availability and room inventory in advance for peak booking months such as July and August.
- Review City Hotel cancellation patterns and introduce suitable strategies to improve booking confirmation.

Conclusion

The project helped identify important patterns in hotel booking behaviour, customer preferences, and cancellation trends.

The analysis and interactive Power BI dashboard provide useful information that can help hotels understand their performance and make better business decisions.

