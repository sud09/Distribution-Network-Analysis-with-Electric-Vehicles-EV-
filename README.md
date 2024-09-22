# Distribution Network Analysis with Electric Vehicles (EV)
Project Overview
PowerCharge Utilities is facing critical challenges due to the rapid adoption of electric vehicles (EVs), which has led to increased demand on the power grid. This project performs a Distribution Network Analysis to assess the impact of EVs on the electrical distribution network, identify bottlenecks, and propose cost-effective strategies for network upgrades.

The project analyzes various factors such as electricity consumption, geographical distribution, customer types, EV charging behavior, and weather conditions, with the goal of optimizing network reliability, improving customer satisfaction, and managing costs effectively.

Problem Statement
The rise of electric vehicles has introduced several challenges for PowerCharge Utilities:

Increased Load Demand: EV charging during peak times strains the power grid.
Grid Overloads: Voltage fluctuations and outages due to overloads in the network.
Customer Satisfaction: Ensuring reliable EV charging services is key to retaining customers.
Cost Management: Balancing demand growth with grid reliability while managing expenses.
Objectives
This project aims to achieve the following:

Assess Network Capacity: Analyze current network capacity to handle the increased load from EVs.
Identify Bottlenecks: Pinpoint vulnerabilities in the network that hinder reliable electricity delivery.
Optimize Network Upgrades: Propose data-driven strategies to minimize costs and improve grid reliability.
Visualize Insights: Use geospatial and load analysis techniques to gain insights into network performance.
Data Description
Electric Vehicle (EV) Distribution Data: Includes information on timestamps, geographical areas, customer types, electricity consumption, charging station locations, EV types, charging habits, and the number of EVs.
Geospatial Data: Contains substation IDs, their locations, and transmission line capacities.
Weather Data: Records temperature, precipitation, and weather conditions at different timestamps.
Tech Stack
Python
Numpy: Mathematical operations
Pandas: Data analysis and manipulation
Matplotlib & Seaborn: Data visualization
GeoPandas: Geospatial data analysis
Jupyter Notebook: For documenting and presenting the analysis
Analysis and Findings
1. Exploratory Data Analysis
We performed an in-depth analysis of electricity consumption patterns, charging habits, and geographical distribution to identify key trends.

2. Capacity Assessment
By analyzing historical data, we identified areas of the network that are likely to experience higher demand growth, allowing for strategic planning of infrastructure upgrades.

3. Geospatial Analysis
Using geospatial data, we mapped EV charging station locations and substation capacities to identify areas prone to grid overloads.

4. Load Impact Analysis
We visualized electricity consumption across different customer types and geographical regions, highlighting areas with the highest grid load. This analysis revealed strong correlations between temperature, EV charging behavior, and load demand.

5. Recommendations
Based on the analysis, we provide several key recommendations:

Focus on infrastructure upgrades in high-consumption areas to prevent overloads.
Incorporate weather forecasting into load prediction models.
Segment customer types and create tailored load management strategies.
Visualizations
Electricity Consumption vs. Temperature: Highlights the relationship between weather conditions and electricity usage.
Geospatial Distribution of EV Charging Stations: Provides an overview of the geographical distribution of EV charging stations and potential network vulnerabilities.
Consumption Trends by Customer Type and Area: Shows how electricity demand varies across customer types and regions.
Conclusion
This project provides a comprehensive analysis of the distribution network to help PowerCharge Utilities optimize their infrastructure in the face of growing EV adoption. By identifying bottlenecks and analyzing key load indicators, PowerCharge Utilities can improve grid reliability, reduce costs, and enhance customer satisfaction.
