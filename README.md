# Hotel-Booking-Analysis
🏨 Hotel Booking Analysis
📌 Overview
This project analyzes hotel booking data for both City Hotels and Resort Hotels. The dataset includes booking details such as:

Booking timelines
Length of stay
Guest composition (adults, children, babies)
Parking availability
Booking modifications and cancellations

All personally identifying information has been removed to ensure privacy.
The objective is to perform Exploratory Data Analysis (EDA) and build a predictive model to uncover patterns and insights related to hotel bookings and cancellations.

🚀 Motivation
This project aims to answer key business questions such as:

How many bookings were canceled?
What is the booking ratio between Resort and City hotels?
What is the yearly booking trend?
Which months are busiest for hotels?
Which countries contribute the most guests?
What is the average length of stay?
What is the most common accommodation type (Single, Couple, Family)?
Can we predict if a booking will be canceled?


🛠️ Tools & Libraries Used
The project is implemented in Python 3 using the following libraries:

Pandas – Data manipulation
Matplotlib – Data visualization
Seaborn – Advanced visualization
Scikit-learn – Machine learning


📂 Project Files
Hotel Booking.ipynb → Jupyter Notebook with:

Data cleaning
Feature engineering
Visualization
Model building

hotel_bookings.csv → Dataset used for the analysis

📊 Dataset Features
The dataset includes the following important features:
hotel, is_canceled, lead_time, arrival_date_year,
arrival_date_month, arrival_date_week_number,
arrival_date_day_of_month, stays_in_weekend_nights,
stays_in_week_nights, adults, children, babies,
meal, country, market_segment, distribution_channel,
is_repeated_guest, previous_cancellations,
previous_bookings_not_canceled, reserved_room_type,
assigned_room_type, booking_changes, deposit_type,
agent, company, days_in_waiting_list, customer_type,
adr, required_car_parking_spaces,
total_of_special_requests, reservation_status,
reservation_status_date


🔍 Approach
The project follows these steps:


Data Cleaning

Handling missing values
Removing inconsistencies



Feature Engineering

Creating new meaningful features



Exploratory Data Analysis

Visualizing trends using charts and graphs
Data Selection
Selecting relevant features for modeling
Predictive Modeling
Classification model to predict booking cancellations

📈 Key Insights

✅ ~35% of bookings were canceled
✅ City Hotels account for more than 60% of bookings
✅ Bookings significantly increased in 2016, then dropped by ~15% in 2017
✅ Peak season: July–August
✅ Low demand: Beginning and end of the year
✅ Top 5 countries contributing 80%+ guests:
Portugal
UK
France
Spain
Germany


✅ Typical stay duration:
1–3 nights most common
✅ Accommodation trends:
Couples (2 adults) are the most frequent guests
🔄 Updates After Forking
✨ This repository has been forked and significantly improved with the following updates:

✅ Enhanced data preprocessing and cleaning techniques
✅ Improved feature engineering for better model performance
✅ Refined visualizations for clearer insights
✅ Optimized machine learning pipeline
✅ Better documentation and code readability
✅ Structured notebook for easier understanding and reproducibility

These enhancements make the analysis more robust, interpretable, and suitable for real-world applications.

📚 Reference
Original inspiration:

Exploratory Data Analysis of Hotel Booking Demand with Python (Medium article)


✅ Conclusion
This project demonstrates how data analysis and machine learning can help hotels:

Understand booking behavior
Improve customer targeting
Reduce cancellations
Optimize revenue strategies

<p float="left" align="middle">  
  <img src="https://user-images.githubusercontent.com/37020354/79042910-0c418780-7c15-11ea-8ddb-f17cf6b1fb2c.png" width="280" />
  <img src="https://user-images.githubusercontent.com/37020354/79042912-0e0b4b00-7c15-11ea-956c-c4ffd1c8525f.png" width="280" />
  <img src="https://user-images.githubusercontent.com/37020354/79042909-0b105a80-7c15-11ea-8d4b-317802f73077.png" width="280" />
  <img src="https://user-images.githubusercontent.com/37020354/79042911-0cda1e00-7c15-11ea-98ea-dcc11e217f32.png" />
</p>

<!---
-- ![4](https://user-images.githubusercontent.com/37020354/79042911-0cda1e00-7c15-11ea-98ea-dcc11e217f32.png)
![1](https://user-images.githubusercontent.com/37020354/79042912-0e0b4b00-7c15-11ea-956c-c4ffd1c8525f.png)
--->
