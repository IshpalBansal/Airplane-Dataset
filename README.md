# Airplane-Dataset
This project utilizes a comprehensive airplane dataset containing over 27 million entries. The data was meticulously cleaned and formatted using Excel and Power Query in Power BI to ensure consistency and accuracy. The dataset includes detailed flight-level information such as arrival and departure delays, flight numbers, tail numbers, states, and cancellation status, forming the foundation for advanced analysis and interactive dashboards.

The dashboard consists of multiple pages (Home, 2021, 2022, 2023, 2024) that provide a complete overview of the whole dataset.
The Home Page showcases:
1. Year-over-Year (YoY) comparisons for on-time flights, total flights, and cancellations.
2. Key KPIs including total flights, number of states and cities, average flight delay, total cancellations, and on-time flights.
3. A delay distribution chart segmented by delay intervals.
4. Top 10 states by cancellations and Top 12 aircraft by on-time performance.
Year-wise Analysis Page Description:

Each yearly page in the dashboard provides an in-depth view of flight operations and performance for the selected year. It includes:

Key KPIs:
1. Total Flights shown through a dynamic line chart.
2. Total Cancellations represented as a percentage of overall cancellations.
3. Average Delay and On-Time Flights, with on-time performance visualized using a gauge chart.
Geographic Analysis:
1. An interactive map displaying average arrival and departure delays across U.S. states, highlighting regional performance.
Performance Rankings:
1. Top 10 aircraft (tail numbers) with the least average delay.
2. Top 10 states with the highest average delays.
3. Monthly Trend Visualization:
4. A bar-line combo chart shows average delay by month (bars) alongside monthly on-time percentage (line).
5. A month slicer allows for custom monthly views.
Traffic Volume Insights:
1. A bar chart displaying the Top 5 states by flight volume in the selected year.
This layout enables users to track performance, delays, and reliability trends in a detailed, visually engaging format—making it easier to identify operational issues or areas of improvement.

Tech Stack • 📊 Power BI Desktop – Main data visualization platform used for report creation. • 📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the data. • 🧠 DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional logic. • 📝 Data Modeling – Relationships established among tables (resorts, snow, and data_dictionary) to enable cross-filtering and aggregation. • 📁 File Format – .pbix for development and .png for dashboard previews.

Goal of the Project:
The goal of this project is to analyze and visualize large-scale U.S. flight operations data (27M+ records) to uncover patterns in delays, cancellations, and on-time performance across different years, aircraft, and states. By leveraging Power BI, Power Query, and Excel, the project aims to deliver an interactive, year-wise dashboard that helps stakeholders quickly identify trends, evaluate airline and state-level performance, and make informed decisions to improve operational efficiency and flight reliability.

Business Impact & Insights:
This project provides a clear and scalable framework for understanding nationwide flight performance over multiple years. The dashboard enables airlines, aviation authorities, and policy makers to:
1. Identify underperforming routes or states based on high cancellation and delay rates.
2. Highlight top-performing aircraft and states with consistent on-time performance.
3. Monitor year-over-year trends in total flights, delays, and cancellations for strategic planning.
4. Pinpoint months or periods of high disruption, aiding in proactive operational decisions.
5. Improve customer satisfaction and cost efficiency by targeting areas for operational improvement.
The insights empower decision-makers to optimize scheduling, resource allocation, and policy implementation based on data-driven evidence

Screenshots / Demos here is the main picture of the property dashboard :-
(https://github.com/IshpalBansal/Airplane-Dataset/blob/main/home.png)
