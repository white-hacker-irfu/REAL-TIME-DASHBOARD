# REAL-TIME-DASHBOARD

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: MOHD IRFAN

*INTERN ID*: CT08WY57

*DOMAIN*: POWER BI

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTHOSH KUMAR

## Real-Time Dashboard in Power BI Using Streaming Data
In Task 3 of our internship with CodTech, we successfully created a real-time dashboard in Power BI using streaming data. The dashboard dynamically updates as new data arrives, enabling real-time monitoring of temperature and humidity. The data is pushed from a Python script to a Power BI streaming dataset, which is visualized using multiple charts, gauges, and KPI cards.

# Objective of Task 3
The primary goal was to design a live Power BI dashboard that continuously updates with temperature and humidity readings. The dataset was populated using a custom API-based data stream, which we simulated using Python. The final dashboard provides real-time insights using various Power BI visual elements.

# Step-by-Step Execution

To create the real-time Power BI dashboard, we first set up a **streaming dataset** in Power BI Service by selecting "API" as the data source and defining the schema with fields for **timestamp, temperature, and humidity**. We enabled **historic data analysis** to store past values for trend insights. Since live sensor data was unavailable, we developed a **Python script** to simulate real-time readings by generating random **temperature and humidity values**. This data was formatted into JSON and sent to Power BI’s API endpoint using an **HTTP POST request** in a continuous loop, ensuring a steady flow of real-time data.  

With the streaming dataset in place, we built the **dashboard** titled **“Custom Streaming Data”** and incorporated multiple visual elements for live monitoring. We used **KPI Cards** to display the latest **temperature and humidity readings**, along with **bar charts** to track these metrics over time based on timestamps. **Horizontal bar charts** were added to visualize real-time values dynamically, while **gauge charts** were included to monitor trends effectively.  

To validate functionality, we ran the **Python script** and observed **instant updates** in all dashboard elements. The bar charts dynamically grew with new values, KPI cards updated in real-time, and the gauge charts adjusted automatically. The dashboard successfully provided **accurate, real-time insights into temperature and humidity fluctuations**, demonstrating seamless integration between **Python-based data streaming and Power BI visualization**.

# Final Outcome
By completing Task 3, we successfully developed a real-time Power BI dashboard with custom streaming data. The dashboard is designed to continuously update and visualize temperature & humidity, making it ideal for IoT-based monitoring systems.

#OUTPUT PICTURE 
![Image](https://github.com/user-attachments/assets/25d5c632-e728-467e-9c08-0f780ab65272)
![Image](https://github.com/user-attachments/assets/39b5d04c-8ebb-42b4-904e-4412bf7aa45f)
