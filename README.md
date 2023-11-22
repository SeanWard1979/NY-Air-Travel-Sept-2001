# Introduction/ Source

This is a dataset from the Bureau of Transportation Statistics.( https://www.transtats.bts.gov/Fields.asp?gnoyr_VQ=FGJ ). It reports flights in the United States showing extensive arrival and departure delays from 1987 to 2022. I decided to filter the data to be merely only New York departures and arrivals from the month of September back in 2001. I wanted to show the consequences on air travel that the 9/11 attacks had specifically on New York during that month.

I do some data wrangling, and various forms of exploring (univariate, bivariate and multivariate) with various visualizations. 

# Conclusions
I will summarize the findings through going variable by variable. 
When I refer to each Section, Section 1= 1st to 10th, Section 2= 11th to 20th, Section 3 = 21st to 30th:

1. Cancelled flights started off in Section 1 to be extremely low (all days below 200 cancelled except the 10th). The first half of Section 2 have anywhere from 1200 to 1500 cancellations daily, it gradually came down to around 400 by the end of Section 2...then gradually went from the 300's to nearly 100 in Section 3. This implies that it was starting to go back to pre-9/11 levels, but not quite there.

2. In terms of Total Airtime of all flights arriving and departing New York, it stayed at 140,000 miles or higher for Section 1. 9/11 had only morning flights, then the rest of the flights for 9/11 and 9/12 were cancelled....Airtime was extremely low until it finally surpassed 100,000 miles on the 17th. Airtime stuck near the 100,000-115,000 level for the rest of the month, implying that less flights were scheduled as compared to Section 1. The number of scheduled flights (including cancelled and delayed flights) stayed consistantly through most of the month until it dropped off on the last three days (from 1300-1600 most of the month, down to 1050-1200 the last three days).

3. Arrival delays peaked on the 4th and on the 10th, and overall were the heaviest in Section 1, and the middle part of Section 2 (14th= 11,067 minutes, 15th= 26,022 minutes, 16th= 16,513 minutes) which was the first weekend after 9/11. Departure delays were less than arrival delays for most of the 1st Section, but were higher than Arrival delays for the 2nd and 3rd sections. Departure delays also peaked on the 4th and on the 10th, and the middle part of Section 2 (14th-17th). I think New York tended to have less departure delays than arrival delays for the first 10 days, and when 9/11 happened, security concerns probably caused that to flip (more departure delays than arrival) since the attacks happened in New York.

4. Strangely, the two days with the most total delays (in minutes) were the 10th (68,430 minutes) and the 4th (60,936 minutes). Total delays were highest for patches of Section 1 and that middle patch of Section 2. Later in the month saw fewer delays partially because there were less flights.

In conclusion, it seems like 9/11 had a dramatic effect on air travel coming to and leaving from New York. It doesn't even take into account how much longer it took passengers to go through the newly imposed security measures (how long did it take passengers from the time of arrival at the airport to actually boarding the plane?). It must have been quite dramatic to go from 1400 to 1500-ish non cancelled flights to no flights at all (the rest of 9/11 and 9/12).
By the end of the month, things were not completely back to normal yet, but it seemed to settle into a "new normal" level in terms of flights, delays and cancellations. Obviously, traveling by plane was never the same after 9/11...but by the end of September it seemed that levels were at least at about 75% in terms of flights and airtime.
