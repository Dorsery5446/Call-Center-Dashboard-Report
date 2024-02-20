# Call-Center-Dashboard-Report
This is the Power Bi Visualization report of the Call Center activities of Federal Communication Commission. This is a Descriptive Data Analysis Report (DDA) of an Independent Agency for the regulation of interstate and international Communication in United States of America.

![Sales Performance EDA Dashboard screenshot](https://github.com/Dorsery5446/Sales-Performance-Dashboard-Report/blob/main/Sales%20Performance%20Dashboard.PNG)

## Data Use
**Dataset:** Call Center
**Period Covered:** October, 2020
**Data Cleaning and Wrangling:** Power Bi Desktop
**Visualization:** Power Bi Desktop

## Project Requirements
The Call Center Overview of the Company captured some Key Performance Indexes (KPI), which are:
-  Total Number of calls: We need to track and display the total number of calls received by our call center over a specified period.
-  Total Call Duration in Hours: It is crucial to understand the total amount of time our call center staff spends on calls in hours, which can help us in resource allocation and capacity           
   planning.
-  Total call duration in minutes: Similar to the total call duration in hours, this KPI provides the total call time but in minutes, offering a more granular view of call durations.
-  Average Call Duration in Minutes: To assess the efficiency of our agents, we need to calculate and display the average call duration in minutes. This metric can help identify trends in call       
   handling.
-  Response Time Percentage: Response time is a critical factor in customer satisfaction. This KPI should display the percentage of calls answered within a predefined time frame, helping us 
   gauge our ability

## Chart Requirement
-  Total call by day (Column Chart): Display a column chart that shows the total number of calls on each day over a specified time period.
-  Total calls by state (Filled Map chart): Create a filled map chart that visualizes the total number of calls received from different states or regions.
-  Top reason for calls (Tree Map): Implement a tree map chart to display the top reasons for calls. Each box in the tree map represents a call reason.
-  Total calls by channel (Donut Chart): Create a donut chart to showcase the distribution of calls by different communication channels.
-  Total calls by sentiment (Column chart): Utilize a column chart to illustrate the distribution of calls by sentiment (e.g. positive, negative or neutral)
-  Total calls by call center (Bar chart): Create a bar chart that presents the total number of calls handled by each call center department.

## Required slicers
-  Sentiment Slicer
-  Channel Slicer
-  States

## Summary of Findings
1.	There are four (4) Communication Channels by Total Calls provided to lodge the complaints:
  -  Call – Center 
  -  Chat Box
  -  Email
  -  Web
However, Call – Center Channel accounted for 10,639 calls out of the Total Calls recorded, followed by Chat Box with 8,256, Email with 7,470 and Web with 6,576.

2.	There are three (3) Total Calls by Reasons, which are as follows:
  -  Billing Questions
  -  Payments
  -  Power Outage
Billing Questions accounted for a massive figure of 23,462 out of the total calls by reasons submitted followed by Payment with 4,749 and Power Outage with 4,730.

3.	There are also five (5) Total Calls by Sentiment, which are as follows:
  -  Negative
  -  Neutral
  -  Very Negative
  -  Positive
  -  Very Positive
Negative accounted for 11,063 (35.58%) calls out of the total calls by sentiments, followed by Neutral with 8,754 (26.57%), Very Negative with 6,026 (18.29%), Positive with 3,928 (11.92%) and Very Positive with 3,170 (9.62%).

4.	There are four (4) Call Centre’s Cities in United States of America, namely:
  -  Los Angeles
  -  Baltimore
  -  Chicago
  -  Denver
Los Angeles accounted for 13,734 calls out of the total calls recorded during the period, followed by Baltimore with 11,012 calls, Chicago with 5,419 and Denver with 2,776.

## Limitations
-  Total Number of Calls, Total Call duration in Hours, Total Call Duration in Minutes, Average Call Duration in Minutes and Response Time Percentage were not provided in the dataset. I adopted the      use of DAX function to arrive at the figures.
-  Adoption of Power Bi for Data Wrangling and Cleaning.
-  Creation of Date Table for Date Slicers.

## Recommendations
The recommendations for these underlisted findings need to be adopted for efficient performance of Call Center Agents:
-  Billing Questions: More efforts need to be put in place to reduce the billing rate of calls as it accounted for over 71% of Total Calls recorded during the period.
-  Call Center Channel: Call Center recorded highest percentage of 33% out of the whole Total Calls under Channel. Hence, the need to improve quality call services to accommodate more call       
    complaints through the channel.
-  Call Center’s Cities: Los Angeles accounted for highest number of Total Calls recorded. Hence, the need to employ more staff or divert staff from other Centers to improve response time of total 
    calls.











