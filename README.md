# McKinsey_Hackathon_I
Time Series Analysis of Vehicular Volume

Project is derived from a 24-hr McKinsey Hackathon held 19 November 2017. 
https://datahack.analyticsvidhya.com/contest/mckinsey-analytics-hackathon/?utm_source=sendinblue&utm_campaign=McKinsey_Hackathon__Go_live&utm_medium=email
<br>Due to family obligations, I did not submit a solution but analyzed the problem on my own time.  Still a work in progress.

Scenario: You are working with the government to transform your city into a smart city. 
The vision is to convert it into a digital and intelligent city to improve the efficiency of services for the citizens. 
One of the problems faced by the government is traffic. You are a data scientist working to manage the traffic of the city 
better and to provide input on infrastructure planning for the future.

The government wants to implement a robust traffic system for the city by being prepared for traffic peaks. 
They want to understand the traffic patterns of the four junctions of the city. Traffic patterns on holidays, 
as well as on various other occasions during the year, differ from normal working days. This is important 
to take into account for your forecasting.

Task: To predict traffic patterns in each of these four junctions for the next 4 months.

Data: The sensors on each of these junctions were collecting data at different times, hence you will see traffic 
data from different time periods. To add to the complexity, some of the junctions have provided limited or sparse 
data requiring thoughtfulness when creating future projections. Depending upon the historical data of 20 months, 
the government is looking to you to deliver accurate traffic projections for the coming four months. Your algorithm 
will become the foundation of a larger transformation to make your city smart and intelligent.

The evaluation metric for the competition is RMSE. Public-Private split for the competition is 25:75.

Data Dictionary Variable Definition

              ID   Unique ID

        DateTime   Hourly Datetime Variable

        Junction   Junction Type

        Vehicles   Number of Vehicles (Target)
