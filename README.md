# Flight-Capacity-Utilization-Analysis

n this project, I analyzed airline travel data to uncover insights into flight occupancy trends and built a machine learning model to predict underfilled flights.
The goal was to help airlines optimize flight schedules and improve revenue by identifying flights likely to have low passenger load.

📚 Technologies Used
SQL (SQLite) – for data extraction

Python – for data analysis and modeling

Pandas, Matplotlib, Seaborn – for EDA and Visualization


⚙️ Steps Performed
1. Data Extraction
Connected to the travel.sqlite database.

Queried and explored tables to retrieve flight data.

Preprocessed important columns like route, flight_type, departure_time, seats_filled, and capacity.

2. Exploratory Data Analysis (EDA)
Analyzed flight occupancy trends by route, flight type, and departure time.

Visualized occupancy rates and identified peak/low-performing routes and times.



📊 Key Results
Departure time and route were key factors influencing flight occupancy.

Afternoon flights had significantly better occupancy compared to early morning slots.

Specific routes consistently underperformed and could be optimized or rescheduled.



🚀 Business Recommendations
Reschedule underperforming flights to peak demand times where possible.

Offer dynamic pricing or promotions for low-occupancy routes and times.

Adjust fleet assignments to smaller aircraft for routes consistently under 50% occupancy.

