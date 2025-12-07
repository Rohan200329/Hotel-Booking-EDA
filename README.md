🏨 Hotel Booking EDA Project

Author: Rohan Bhore
Guide: Abhishek Wavhal

📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Hotel Booking Dataset, containing booking details of City Hotel and Resort Hotel from 2015–2017.

The goal is to understand booking patterns, cancellations, customer behavior, revenue trends, and factors affecting hotel performance.

🎯 Business Objective

To analyze and visualize hotel booking data in order to:

Identify key drivers of hotel bookings

Compare performance between City and Resort hotels

Detect issues like high cancellations, long waiting times, low demand areas

Provide insights for business improvement and growth

📂 Dataset Details
Item	Details
Total Rows	119,390 (before cleaning)
Final Rows	87,392
Columns	32 → 33 (after adding Booking ID)
Hotel Types	City Hotel, Resort Hotel
Time Period	2015–2017
🛠️ Data Cleaning & Feature Engineering

✔ Removed duplicates
✔ Filled or replaced null values
✔ Created Total Stay column
✔ Added Total Customers column
✔ Added Booking ID (Primary Key)
✔ Merged Arrival Day, Month, Year → Arrival Date
✔ Created Customer Satisfaction column
✔ Converted columns to appropriate data types

📊 Topics Covered in EDA

Hotel booking comparison

Cancellation rate analysis

Lead time analysis

Year-wise bookings

Country-wise guests

Repeated guest analysis

Meal type preferences

Month-wise booking trends

Average waiting time

Preferred room types

Car parking requirement

ADR (Average Daily Rate) comparison

Agent-wise bookings

Customer type distribution

Total stay share

Special request analysis

📎 Full Analysis Available in the Presentation File:
Presentation1.pptx

🔍 Key Insights Summary

City Hotel has higher bookings but also higher cancellations

Resort Hotel has lower bookings but better stay ratio

August has the highest booking volume

BB (Bed & Breakfast) is the most preferred meal

City Hotel has higher ADR than Resort Hotel

Transient customers contribute maximum bookings

Agent bookings are highly unbalanced

Most guests come from PRT & GBR

📈 Tools & Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Power BI (for visualization)

Excel (data pre-processing)


💡 Conclusion
The EDA highlights several factors affecting hotel performance such as cancellations, waiting time, booking channels,
and seasonal trends. Proper optimization and targeted strategies can significantly improve bookings and revenue for both hotels.

