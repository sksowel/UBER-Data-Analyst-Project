# UBER-Data-Analyst-Project

🏷️ 1. Project Title

UBER Data Insights: Bengaluru Ride Analysis Dashboard
An interactive data visualization and analytics project that explores ride patterns, cancellations, customer satisfaction, and revenue trends from Uber’s Bengaluru dataset—highlighting operational efficiency and key business insights through Power BI.

📝 2. Short Description / Purpose

The UBER Data Insights Dashboard is a comprehensive and dynamic Power BI report built to analyze a month’s worth of simulated Uber ride data (1,00,000+ records) for Bengaluru city. It enables users to visualize booking trends, cancellation behaviors, ride distances, and customer-driver performance metrics.
This project is designed for data analysts, business strategists, and transportation planners seeking to optimize operations, understand customer patterns, and identify revenue opportunities within the ride-sharing ecosystem.

🧰 3. Tech Stack

The dashboard was built using the following tools and technologies:

• 📊 Power BI Desktop – Primary visualization tool used to create dynamic and interactive dashboards.
• ⚙️ Power Query – For data transformation, cleaning, and preprocessing of the raw dataset before visualization.
• 🧠 DAX (Data Analysis Expressions) – Applied for calculated metrics, key performance indicators (KPIs), and dynamic filtering.
• 🧩 Data Modeling – Established relationships between tables (bookings, customers, drivers, and payments) to enable accurate cross-analysis.
• 💾 Excel / CSV Data Source – Generated synthetic data for 1 month of rides with over 1 lakh records.

📂 4. Data Source

Source: Simulated Uber Bengaluru Ride Dataset (Created for Data Analysis Practice)

The dataset was synthetically generated to represent Uber ride data for Bengaluru city over a one-month period, comprising 100,000+ booking records.

Each record captures detailed ride-level information such as:

• Booking and trip timestamps
• Pickup and drop locations (50 major Bengaluru areas)
• Vehicle categories (Auto, Bike, eBike, Mini, Prime Sedan, Prime Plus, Prime SUV)
• Customer and driver interactions (ratings, cancellations, incomplete rides)
• Fare details, distance covered, and payment modes

Data Structure Overview:
The dataset contains the following key variables:

Category	Columns

| Category               | Columns                                                               |
| ---------------------- | --------------------------------------------------------------------- |
| Booking Details        | Date, Time, Booking_ID, Booking_Status                                |
| Customer & Driver Info | Customer_ID, Driver_Ratings, Customer_Rating                          |
| Trip Information       | Vehicle_Type, Pickup_Location, Drop_Location, Ride_Distance           |
| Timings                | Avg_VTAT (Vehicle Time to Arrive), Avg_CTAT (Customer Time to Arrive) |
| Financials             | Booking_Value, Payment_Method                                         |
| Cancellations          | Cancelled_Rides_by_Customer, Cancelled_Rides_by_Driver, Reasons       |
| Incomplete Rides       | Incomplete_Rides, Incomplete_Rides_Reason                             |


📊 Key Data Constraints Applied:

• 62% Successful rides
• ≤7% Customer cancellations
• ≤18% Driver cancellations
• ≤6% Incomplete rides
• Higher ride demand on weekends and match days
• Booking values range from ₹100 to ₹1000+, with 70% rides under ₹500

🌟 5. Features / Highlights
💼 Business Problem

Uber’s operations involve thousands of rides daily, each influenced by customer demand, driver behavior, vehicle type, and city traffic. However, understanding these operational trends from raw transactional data is difficult.

Business challenges include:

• Identifying cancellation patterns and reasons.
• Measuring driver and customer performance through ratings.
• Understanding revenue trends across payment methods and ride types.
• Optimizing supply-demand based on ride volume trends and timing.

🎯 Goal of the Dashboard

• To build a data-driven, interactive Power BI dashboard that:
• Analyzes ride performance and booking outcomes.
• Provides a clear visual understanding of cancellations, incomplete rides, and revenue.
• Helps stakeholders identify trends in customer satisfaction and driver reliability.
• Enables data-driven decision-making for improving operational efficiency and user experience.

📊 Walkthrough of Key Visuals

| Section                 | Visuals                                                                        | Insights                                                                             |
| ----------------------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------ |
| **Overall Performance** | 📈 *Ride Volume Over Time*, 🥧 *Booking Status Breakdown*                      | Tracks total rides, success ratio, and cancellation distribution daily.              |
| **Vehicle Analysis**    | 🚘 *Top 5 Vehicle Types by Ride Distance*, ⭐ *Average Ratings by Vehicle Type* | Identifies which vehicle types drive the most distance and receive the best ratings. |
| **Revenue Analysis**    | 💰 *Revenue by Payment Method*, 🧾 *Top 5 Customers by Booking Value*          | Highlights the most popular payment channels and high-value customers.               |
| **Cancellations**       | ❌ *Cancelled Ride Reasons (Customer & Driver)*                                 | Reveals common causes for cancellations to support policy improvements.              |
| **Performance Ratings** | 🌟 *Driver vs Customer Ratings*, 📦 *Ratings Distribution*                     | Compares service quality from both perspectives and identifies rating trends.        |

📈 Business Impact & Insights

• Operational Optimization: Identified peak hours and weekend surges for better resource allocation.
• Customer Retention: Cancellation analysis revealed that “Driver not moving towards pickup” was a major issue, prompting process improvement.
• Revenue Growth: Visualization of high-value customer clusters enabled targeted incentive strategies.
• Quality Improvement: Rating correlation insights supported driver training and reward programs.

6. Screenshots / Demos

Dashboard: ![Dashboard Preview](https://github.com/sksowel/UBER-Data-Analyst-Project/blob/main/UBER_Dashboard_1.png)
