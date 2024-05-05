# Data_analysis_of_hotel_booking
Project Description:

This project analyzes a dataset containing hotel booking information to gain insights into reservation trends, cancellation patterns, and average daily rates (ADR) in two types of hotels: Resort Hotel and City Hotel. The dataset includes various features such as reservation status, arrival date, market segment, country of origin, and more.

Key Steps and Findings:

Data Cleaning and Preprocessing:
Loaded the dataset using Pandas and inspected its structure.
Removed irrelevant columns ('name', 'email', 'phone-number', 'credit_card', 'company', 'agent') and dropped rows with missing values.
Converted the 'reservation_status_date' column to datetime format for further analysis.
Exploratory Data Analysis (EDA):
Investigated the distribution of the 'adr' (average daily rate) column and removed outliers.
Calculated the percentage of canceled reservations ('is_canceled') and visualized the distribution using bar charts.
Explored the cancellation rates in different hotel types (Resort Hotel vs. City Hotel) and visualized the results.
Time Series Analysis:
Calculated the daily average ADR for both hotel types over time and visualized the trends using line charts.
Analyzed cancellation rates and ADR variation across different months of the year.
Country-wise Analysis:
Examined the top 10 countries with the highest number of canceled reservations and visualized the results using a pie chart.
Explored the distribution of market segments and analyzed cancellation rates by market segment.
Conclusion:

Through this analysis, we gained valuable insights into reservation patterns, cancellation trends, and ADR variations in the hotel industry. By understanding these factors, hotel management can make informed decisions to optimize booking processes, minimize cancellations, and improve revenue management strategies.

Next Steps:

This project can be further extended by implementing predictive modeling techniques to forecast future reservation trends and identify factors influencing cancellation probabilities. Additionally, conducting deeper analysis on customer demographics, booking channels, and promotional strategies can provide more comprehensive insights for hotel management and marketing teams.
