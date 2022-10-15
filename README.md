Data Visualization Project regarding US domestic Flight delays and cancellations report.
Dashboard Links: 
•	Map showing worst destination delay airport: https://public.tableau.com/app/profile/olugbenga.felix.ajiga/viz/map-showing-worst-destination-delay-airport/map-arrival-delay-at-airport?publish=yes

•	Arrival delay at airport destination: https://public.tableau.com/app/profile/olugbenga.felix.ajiga/viz/arrival-delay-at-airport-destination/arrival-delay-at-airport-destination?publish=yes

•	Airlines arrival departure delay: https://public.tableau.com/app/profile/olugbenga.felix.ajiga/viz/airlines-arrival-departure-delay/airlines-arrival-departure-delay?publish=yes

•	Dashboard 1:
https://public.tableau.com/app/profile/olugbenga.felix.ajiga/viz/dashboard-one-us-domestic-flight-delays-report-2015/location-delay-airport?publish=yes

•	Dashboard 2: https://public.tableau.com/app/profile/olugbenga.felix.ajiga/viz/avg-delays-at-origin-destination-airport/avg-delays-at-origin-destination-airport?publish=yes

•	Dashboard 3: https://public.tableau.com/app/profile/olugbenga.felix.ajiga/viz/reasons-for-delay/reasons-for-delay?publish=yes

•	Story- Putting all together: https://public.tableau.com/app/profile/olugbenga.felix.ajiga/viz/Story-putting-all-together/Story-Putting-all-together?publish=yes

Summary:
This data comes from a Kaggle dataset, it tracks the on-time performance of US domestic flights operated by large air carriers in 2015. 
Analysis was carried out by comparing airline delays to arrival delays, departure delays, speciﬁc states, airports, and months in the year, as well as air time and travel distance to discover insight that will reveal the following:
•	What are the causes of delays.
•	What part of the flight causes the most delays.
•	And if these causes vary by airport or time of year.
•	Which destinations and arrival have the most delays.
After analyzing the data, it becomes clear that a variety of factors appear to be correlated with airline delays, including arrival and departure delays, longer distances, and greater airtime. However, the factors with the largest inﬂuence on higher-than-average airline delays seem to be the month of the year and the location of ﬂights. Although this insight cannot be explicitly drawn from the available data, it appears that the human factor (perhaps surrounding holidays and travel as well as location) may be the greatest inﬂuence on larger-than-average airline delays. 
Insight 1
The below map and bar charts show information about flight destination delays in 2015 at each Airport in the US.
•	It showed that the worst destination delay airport in the US in 2015 was ATL Hartsfield-Jackson Atlanta International Airport Atlanta (17,877 times arrival delays and airtime of 1,583,332).
•	LGA LaGuardia Airport (Marine Air Terminal) New York Airport in 2015 with an Average arrival delay of 9.864 rank the 1st worst arrival delay Airport in the US.

Insight 2
The following visualization chart showed the major causes of flight delays at the origin airport, filtered by either airport and month of the year.
•	There are about eight major causes for flight delays as shown in the chart attached:  Whether delay, Security delay, Diverted, Late Aircraft delay, Departure delay, Arrival delay, Airline delay, and Air System delay. All eight major causes of the chart tell us that Departure delay is the most common and (ORD) Chicago O'Hare International Airport Chicago has the most combined cause of delay. 
Insight 3
The following visualization chart is for Airline information for the most arrival and departure delays at most US domestic airports in 2015.
•	There are 14 airlines to carry out US domestic flights in 2015. Among them, (HA) Hawaiian Airlines Inc. had the lest records: 6,494 arrival delays and 589 departures delay.
•	While (WN) Southwest Airlines Co. had the worst records: 12,629 arrival delays and 30,167 departure delay.
•	There seem to be a linear and positive correlation between the arrival delay and departure delay with the airlines.
 
Dashboard 1
•	This dashboard shows the airport location on the map, reasons for delays at the origin airport, and arrival/destination delays at a glance.
•	One can filter by any of the chart dimensions or parameters and it will apply to all.
•	The dashboard on the down left examines the relationship between arrival delay as well as airline departure delay across all airports. There appears to be a strong relationship between arrival delays and departure delays with a few outliers, speciﬁcally Delta Airlines Inc. with an arrival delay of -382 departure delay of 2,820, and Southwest Airlines Co. with an arrival delay of 3,818 and departure delay of 28,448. 
Dashboard 2- average delays at the origin-destination airport
•	This dashboard shows the average delays at the origin airport and destination airport with (LGA) LaGuardia Airport (Marine Air Terminal) New York ranked 1st with an average of 9.86 at the origin airport while (EWR)	Newark Liberty International Airport Newark ranked 1st with an average of 14.08 at the destination airport.
•	Filter can be used to drill down to some more individual origin and destination airport
 
Dashboard 3 – Factors that cause delays
This dashboard shows at a glance those factors that are responsible for flight delays at the origin and destination airport.
•	There are about eight major causes for flight delays as shown in the chart attached:  Whether delay, Security delay, Diverted, Late Aircraft delay, Departure delay, Arrival delay, Airline delay, and Air System delay. All eight major causes of the chart tell us that Departure delay is the most common and (ORD) Chicago O'Hare International Airport Chicago has the most combined cause of delays.
 
Design Choices:
The choices for this design were primarily made to keep things simple and easy to use. When
available, the Tableau palette speciﬁcally designed to be colorblind-friendly has been optimized.
When that palette was not an available choice, the colors chosen are oranges and blues, which
are colorblind-friendly choices. Values that span a range of numbers are encoded in a range of
colors, speciﬁcally orange: blue diverging. To make numerical diﬀerences more obvious
in state maps, the colors were stepped in ﬁve steps, with the colors reversed so that higher
numbers (in terms of delay minutes) were orange, while low delay numbers were blue. This is
because people are generally familiar with colors closer to red being the less-desirable ﬁgures.
Axis titles were made larger and rendered in bold for better legibility, while chart titles were
removed from dashboards to reduce clutter. The most user-friendly design for a month and
airport ﬁlters seemed to be single-value dropdown menus while utilizing a highlighter for states
wound up being the most user-friendly tool.

Resources: 
ﬂights.csv 
https://classroom.udacity.com/paid-courses/cd12399/lessons/1d2d00f8-e884-40f0-8c66-a7c2cbc606ad/project#
Video Walkthrough: https://www.youtube.com/watch?v=9xqHA732LMA
Original dataset from Kaggle: https://www.kaggle.com/usdot/flight-delays/data

Conclusion
Story- Putting all together:
All the dashboards have been put together to make a presentation,
With four slides a story on the finding of US domestic flights operated by large air carriers in 2015 has now been put together to tell a story.
I can find out three major insights from this visualization dashboard regarding flight arrival delays at major US domestic airports & airlines with major causes. 
 
