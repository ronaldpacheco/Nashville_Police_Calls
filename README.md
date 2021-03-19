# Nashville_Police_Calls

Data Source: https://data.nashville.gov/Police/Metro-Nashville-Police-Department-Calls-for-Servic/kwnd-qrrm

#Conclusions
- Most of these calls happen in the Nashville area, as expected, since other cities/counties are cover by different police departments
- The number of calls has been somewhat steady in the last ~7 years. However, we can see how its slope has decreased a little towards the last few years
- Highest number of service calls happened on January 4th of 2013 with 4,395 calls.
- Lowest number of service calls happened on December 8th of 2020 with 4 calls. This outlier is most likely due to an error in the system, however, I could not find any news articles about this specific day to make sure this is not an error.
- Second lowest number of service calls happened on November 26th of 2020 with 1001 calls.
- The month with the most calls overall is January. With most common tencodes being:

93 Traffic Violation
96 Business Check
43 Want Officer for Investigation / Assistance And if we break it down by year:
From 2013 to 2018 we have the same ones:

93 Traffic Violation
96 Business Check
43 Want Officer for Investigation / Assistance
For 2019 we have:

96 Business Check
43 Want Officer for Investigation / Assistance
15 Community Policing Activity
And for 2020:

96 Business Check
43 Want Officer for Investigation / Assistance
44 Disorderly Person
So far, for 2021 we have:

96 Business Check
43 Want Officer for Investigation / Assistance
44 Disorderly Person
-Sundays is the day with the least calls, followed by Saturday. The rest are pretty equally distributed. This might be because there are not as many people driving during Saturday and Sunday as there is during the week.
-We do not have enough data to make any claims about the sectors
-The bulk of the calls are actually minor issues. Traffic violations being the top one
-We selected the tencodes we felt were the most important/interesting and got:
  -Theft and Burglary are the most common types of calls
  -There have been 9987 Dead on Arrival calls, it would be interesting to see how many of those are actual homicides. And, in looking deeper into the most common types of calls, we could see:
    -Around half the calls about residential bulglary are closed out as 'Disregard'
    -Most theft calls are closed out with a report
    -Most calls end up by 'Securing Location/Building,' 'Assisted Citizen,' and 'Disregard'
