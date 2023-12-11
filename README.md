# Splendor Hotel Groups: Customer behavior and booking pattern analysis 
data
dashboard

## Table of Contents
- [Project Overview](##Project-overview)
- [Data sources](##Data-sources)
- [Methodology](##Methodology)
- [Findings](##Findings)
  - [Booking patterns](###1.Booking-patterns)
  - [Customer behavior analysis](###2.Customer-behavior-analysis)
  - [Revenue trends](###3.Revenue-trends)
- [Conclusion and Recommendations](##Conclusions-and-recommendations)

## Project Overview

This data analysis project aims to provide insights into the customer behavior and booking patterns of a Hotel Group over 5 years of operations. By analyzing this comprehensive dataset comprising guest demographics, distribution channels, details of bookings, and financial metrics, a deeper understanding of the company's performance was achieved and data-driven recommendations were made possible. 


## Data sources
The primary dataset used for this analysis is in the "SHG_data.csv" file. The "Data" Excel sheet inside the "SHG_dashboard.xls" file is the cleaned and manipulated dataset used for further analysis. It contains detailed information about each booking made by the guests. This comprehensive dataset comprises of 119,391 rows and 21 columns after initial data cleaning and manipulation.

### Tools
- Microsoft Excel: data cleaning, manipulation, EDA, and interactive dashboard construction

## Methodology
The data was formatted as a table to ensure that future new entries are properly integrated. During data cleaning and manipulation, it was observed that there were no duplicated records. The dates were transformed to "short date" type and new columns with months and years were created to facilitate further filtering. It was noted that 488 countries were blank, and a placeholder value, "unknown", was assigned to these missing entries. The data from the year 2013 was not considered in the analysis, as only one booking was made.

## Findings

### 1. Booking patterns
- *What is the trend in booking patterns over time, and are there specific seasons or months with increased booking activity?*

There is a noticeable decline in the number of bookings made from January to June, indicating that there is a lowering demand after the end-of-year celebrations. Considering the sum of bookings throughout all operational years (2014-2017), January, July, and October are months with a spike in booking activity. 

The years 2016 and 2017 contributed the most to the January high demand seen in the overall trend. In absolute numbers, 2016 was the busiest year, accounting for more than 50% (58543) of all the bookings. 

- *How does lead time vary across different booking channels?*

The overall average lead time was 104 days. Bookings made through offline travel agents showed the highest lead time (135 days). Contract guests typically book rooms more in advance (142 days). In contrast, bookings made by undefined distribution channel (23 days) and by groups (55 days) revealed the shortest lead times. 

![Avg lead time](https://github.com/Irene-arch/Documenting_Example/assets/56026296/5ebedeb8-65e4-4f09-a2a5-0699119f5ff7)


### 2. Customer behavior analysis
- *Which distribution channel and customer type contribute the most to bookings and how does the average daily rate (ADR) differ across these?*

More than half (62%) of the bookings were made through online travel agents, which is also true for all years separately. This distribution channel also shows the highest ADR (108 USD). This tendency can be due to the convenience and flexibility that online services have. Direct bookings had the second highest ADR (106 USD), however account for only 12% of the bookings volume. Transient customers are the most prominent in booking volume (75%) and display the highest ADR among other customer segments. 

- *Can we identify optimal pricing strategies based on the ADR?*

Transient customers booking through online and direct services have the highest ADR and booking volume, indicating that they may be willing to pay more for a room reservation. On the contrary, corporate agreements with contract have the lowest ADR of the defined distribution channels. An optimal pricing strategy should rely on higher rates for online bookings made by transient customers and competitive rates for corporate and contract segments.


- *Can we identify any patterns in the distribution of guests based on their country of origin and how does this impact the revenue?*

Portugal is the highest contributor in number of guests and revenue in all years. The ten most prominent countries in revenue generation were from Europe. There is, in general, a direct proportionality in the number of guests and revenue generated, however, Brazil and China are exceptions probably due to their high cancellation rates and consequent revenue loss. This depicts the importance of understanding what influences revenue generation other than the sole number of guests.  

Given Portugal's dominance over the other countries in revenue and guest volume, it comprises a potential target for marketing efforts. The other countries that were among the top revenue bringers can be aimed to increase even more guest quantity and revenue.

- *How does revenue loss from cancellations compare across different customer segments and distribution channels?*

Transient customers who made the booking online were responsible for the highest revenue loss. This was expected since they are also the highest contributors to booking numbers and revenue generation. Almost half of the bookings were made by contract clients who booked online (49%). Knowing that this customer segment accounts for approximately 2000 bookings (3.4%), the revenue loss is lower compared to the other customer types. A prominent proportion of bookings made by transient customers either online or offline (46% and 43%, respectively) were canceled, which explains the highest revenue loss being related to this guest type. 

![Proportion of cancellations](https://github.com/Irene-arch/Documenting_Example/assets/56026296/5ebedeb8-65e4-4f09-a2a5-0699119f5ff7)

### 3. Revenue trends
- *What is the overall revenue trend?*

There is a notable increase in the average revenue in the two most recent years, with a prominent spike in January for both years, indicating that this could be a trend in the future as well. In 2017, a noticeable shrinkage of more than 45% of its revenue in relation to the previous year was mostly due to a sharp decline in revenue from January to August. 

- *How does the deposit type impact the likelihood of cancellations and revenue generation?*

Non-refundable deposits showed the highest cancellation rate (99.4%) whereas the refundable deposit had the lowest cancellation rate (22%). Most bookings were made without making a deposit (85%) and showed a relatively low cancellation rate (28%), with the highest average ADR among the other deposit types. 

These findings indicate that most guests do not want to commit to making a deposit when making a booking, which does not prevent them from spending more per room daily. The average ADR of refundable bookings is notably lower than the other two deposit categories. These findings demonstrate that paying a deposit (being it refundable or not) can, in the end, result in paying less per room per day. However, it may still sound counter-intuitive that almost all bookings without a refunding possibility were canceled.  

- *How does the time between booking and arrival date (lead time) affect revenue and the likelihood of cancellations?*

Bookings that were canceled showed a pattern of higher average lead time and were accountable for over 13 million USD in revenue loss over the years analyzed. 

## Conclusions and recommendations

Distribution channel, customer type, country of origin, and deposit type play pivotal roles in the business's financial performance. Transient clients from Europe who book without a deposit through online services are the most prominent contributors both in guest influx and revenue generation. Seasonality, as expected, is an important factor in tourism. Trying to compensate for low-demand periods and to ensure customer loyalty, special offers, flexible pricing, and directed marketing campaigns to this customer segment can bring a positive impact on revenue.      
