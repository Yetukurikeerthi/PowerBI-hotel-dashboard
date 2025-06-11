PowerBI Real-Time Data Analyst Dashboard

This project is a solution to the Dashboard Project Challenge, where I build a real-time interactive dashboard for a hotel business using Power BI. It showcases the full analytics workflow from data cleaning to visualization.

Project Overview

Domain: Hospitality / Hotel Revenue Analytics  
Tools Used:Power BI, Power Query, DAX  
Skills Demonstrated: Data Cleaning, Metrics Building, Dashboard Design, Stakeholder Communication  

This dashboard enables hotel executives to:
- Track key revenue metrics across properties
- Identify booking trends and seasonal patterns
- Compare performance by region and property type
- Make data-driven operational decisions

Objectives

- Analyze hotel KPIs like Revenue, Bookings, RevPAR, Occupancy Rate
- Build dynamic filters (e.g., by region, property, date)
- Deliver actionable insights through visual storytelling


Process

1. Business Requirement Review
2. Data Transformation (Power Query)
3. Metric Calculation (DAX) 
4. Dashboard Design (Power BI) 

 Dataset Description

This project uses 5 core datasets:

 1. `dim_date.csv`
- `date`: Calendar date  
- `mmm yy`: Month and year  
- `week no`: Week number  
- `day_type`: Weekend or Weekday  

 2. `dim_hotels.csv`
- `property_id`: Unique hotel ID  
- `property_name`: Hotel name  
- `category`: Hotel class (Luxury, Business)  
- `city`: Hotel location  

3. `dim_rooms.csv`
- `room_id`: Room type code (RT1–RT4)  
- `room_class`: Room category (Standard, Elite, Premium, Presidential)  

4. `fact_aggregated_bookings.csv`
- `property_id`, `check_in_date`, `room_category`  
- `successful_bookings`: Number of confirmed bookings  
- `capacity`: Total room availability  

5. `fact_bookings.csv`
- `booking_id`: Unique booking reference  
- `booking_date`, `check_in_date`, `check_out_date`  
- `no_guests`, `room_category`, `booking_platform`  
- `ratings_given`, `booking_status`  
- `revenue_generated`, `revenue_realized` *(adjusted based on cancellation/no-show rules)*  

> 💡 *Revenue is partially refunded if a booking is cancelled (60% retention); otherwise, the full revenue is realized.*

