# Hotel Booking Cancellation Analysis
## One Line Summary

Analyzing hotel booking data to identify patterns and factors that influence booking cancellations and provide insights to help hotels reduce revenue losses.

## Project Overview

Hotel booking cancellations are a major challenge in the hospitality industry because they lead to revenue loss, inefficient room allocation, and poor demand forecasting. This project analyzes hotel booking data to understand the factors that influence cancellations and identify patterns in customer behavior.

Using data analysis techniques, the project explores booking trends, cancellation rates, seasonal demand, and customer characteristics. The insights generated can help hotels improve operational planning and develop strategies to reduce cancellations.

## Problem Statement

Hotels frequently experience high cancellation rates which affect revenue management and resource planning. When customers cancel bookings at the last minute, hotels may lose potential revenue and struggle with room allocation.

The objective of this project is to analyze booking data to answer key business questions:

- What percentage of bookings are canceled?

- Which hotel type has the highest cancellation rate?

- How do price, lead time, and season affect cancellations?

- Which customer segments cancel bookings the most?

- What strategies can hotels use to reduce cancellations?

## Dataset
### Dataset Overview

The dataset used in this project is the Hotel Booking Demand Dataset, which contains booking information from two hotels in Portugal: a City Hotel and a Resort Hotel.

### Dataset Characteristics

- Total Records: 119,390

- Features: 32 columns

- Time Period: July 2015 – August 2017

The dataset contains booking details such as reservation dates, customer demographics, room type, and cancellation status.

### Key Variables

- Hotel type

- Booking lead time

- Arrival date

- Number of adults / children / babies

- Market segment

- Deposit type

- Customer type

- Average daily rate

- Previous cancellations

- Special requests

- Booking cancellation status

## Tools and Technologies

Python – Data cleaning and analysis

Pandas – Data manipulation

NumPy – Numerical analysis

Matplotlib & Seaborn – Data visualization

Jupyter Notebook – Analysis environment

## Methods
### Data Cleaning

- Loaded dataset using Pandas

- Checked missing values

- Removed unnecessary columns

- Converted date columns to proper formats

### Exploratory Data Analysis (EDA)

Performed exploratory analysis to understand patterns in the data:

- Cancellation rate analysis

- Booking trends over time

- Hotel type comparison

- Price distribution analysis

- Customer segment analysis

### Data Visualization

Visualizations were created to clearly understand booking patterns:

- Booking cancellations by hotel type

- Monthly booking trends

- Market segment distribution

- Lead time vs cancellation rate

- Average daily rate comparison

## Key Insights

- City hotels have a higher cancellation rate compared to resort hotels.

- Customers with longer lead times are more likely to cancel bookings.

- Online travel agencies contribute to a large portion of cancellations.

- Summer months show higher booking demand.

- Customers with no deposit bookings cancel more frequently.

These insights help hotels understand cancellation behavior and adjust their strategies accordingly.

## How to Run This Project
1 Clone the Repository
git clone https://github.com/yourusername/hotel-booking-cancellation-analysis.git
2 Install Required Libraries
pip install pandas numpy matplotlib seaborn
3 Run the Analysis Notebook

Open the Jupyter Notebook and run all cells to reproduce the analysis and visualizations.

## Results and Conclusion

The analysis reveals key factors influencing hotel booking cancellations such as lead time, booking channel, and pricing strategies. By understanding these patterns, hotels can implement strategies such as deposit policies, dynamic pricing, and targeted marketing campaigns to reduce cancellation rates and improve revenue management.

## Future Work

- Possible improvements for this project include:

- Building a machine learning model to predict booking cancellations

- Implementing customer segmentation analysis

- Developing real-time dashboards using Power BI or Tableau

- Applying predictive analytics for demand forecasting
