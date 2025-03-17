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
1️⃣ Setting Up a Streaming Dataset in Power BI
The first step involved creating a streaming dataset in Power BI Service:

Opened Power BI Service (app.powerbi.com).
Navigated to Workspaces and created a new streaming dataset.
Selected "API" as the data source.
Defined the dataset schema with fields:
  timestamp (Date/Time)
  temperature (Numeric)
  humidity (Numeric)
Enabled historic data analysis, allowing Power BI to store past values for trend analysis.
This setup ensured that Power BI could continuously receive temperature and humidity data.

2️⃣ Creating a Python Script for Real-Time Data Streaming
Since a live API source was unavailable, we wrote a Python script to simulate real-time sensor data:

  Generated random temperature and humidity values in real-time.
  Formatted the data into JSON and sent it to Power BI's API endpoint using an HTTP POST request.
  Used a loop to continuously push new data every few seconds.
  
This allowed us to simulate IoT-based real-time monitoring.

3️⃣ Designing the Power BI Real-Time Dashboard
Once the streaming dataset was active, we built the Power BI dashboard using multiple visual elements:

(a) Creating a Dashboard
  Opened Power BI Service and created a new dashboard.
  Named it “Custom Streaming Data” (as seen in the screenshot).

(b) Adding Key Performance Indicators (KPIs)
  Two Card Tiles were added to display real-time values of:
    Temperature
    Humidity

(c) Implementing Graphical Visualizations
  Two Bar Charts showing:
    Temperature over time (by timestamp)
    Humidity over time (by timestamp)
    Two Horizontal Bar Charts for:
    Live temperature values
    Live humidity values
  
(d) Adding Gauge Charts
  Two Gauge Charts were included to monitor live trends:
    One for humidity
    One for temperature
  
The dashboard was now fully interactive and capable of real-time updates.

4️⃣ Testing and Monitoring Live Data Updates
  To validate real-time functionality, we ran our Python script and observed:
  
    Instant updates in all dashboard elements every few seconds.
    Bar charts dynamically growing as new data arrived.
    Gauge charts adjusting automatically based on real-time values.
    The dashboard worked flawlessly, reflecting accurate temperature and humidity readings with minimal latency.

# Final Outcome
By completing Task 3, we successfully developed a real-time Power BI dashboard with custom streaming data. The dashboard is designed to continuously update and visualize temperature & humidity, making it ideal for IoT-based monitoring systems.

#OUTPUT PICTURE 
![Image](https://github.com/user-attachments/assets/25d5c632-e728-467e-9c08-0f780ab65272)
![Image](https://github.com/user-attachments/assets/39b5d04c-8ebb-42b4-904e-4412bf7aa45f)
