# Flight Delays and Cancellations

The following report discusses some insights about the effectiveness of US domestic flights run by major airlines in 2015. I created data visualizations to reveal insights, tell a story, or highlight patterns within the dataset using Tableau. The following steps outline my approach.

This data comes from a Kaggle dataset, it tracks the on-time performance of US domestic flights operated by large air carriers in 2015.
The file you must use in creating your data visualizations is the [flight.csv](https://github.com/hadywk/Flight-Delays-and-Cancellations/blob/1548eefe544befc0258ccbbe46cb5aa9d30e2a5b/flights.csv) file.

## Visualization A: Which Airlines Have the Worst Airline Delays?

**See on Tableau Public:**
[Dashboard](https://public.tableau.com/shared/4K2PM6ZNC?:display_count=n&:origin=viz_share_link)

**Summary:**
The following insight describes the number of delays for every airline company per month. Southwest Airlines Co. consistently had the most delays each month, with a peak of 1,505 delays in July. In contrast, Hawaiian Airlines Inc. had the least number of delays in July, with only 44 delays.

**Design:**
- Each airline company is represented by a unique color.
- The number of airline delays is plotted over each month from January to December using an area chart.

![alt text](https://github.com/hadywk/Flight-Delays-and-Cancellations/blob/bdfc6380eea3d5e58aabebf991ed72bbc6c3aced/Air%20Delays.png)

---

## Visualization B: States Affected by Weather Delays on Air Flights

**See on Tableau Public:**
[Dashboard](https://public.tableau.com/shared/QWFFJCWC7?:display_count=n&:origin=viz_share_link)

**Summary:**
The following insight describes the number of weather delays that affected air flights in every state. Texas experienced the highest number of weather delays, with 450 incidents, while West Virginia had the fewest, with only 1 weather delay.

**Design:**
- The map uses shades of blue to teal to illustrate the differences in the number of weather delays for each state.

![alt text](https://github.com/hadywk/Flight-Delays-and-Cancellations/blob/2eb872cc953db9c5a4688b6b68e4d5d31c8306de/Weather%20Delays%20for%20each%20state.png)

---

## Visualization C: Flight Cancellations per Month

**See on Tableau Public:**
[Dashboard](https://public.tableau.com/views/Noofflightcancellationpermonth/noofflightscancelledpermonth?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

**Summary:**
The following insight describes the number of flights cancelled per each month. February had the most flight cancellations, with 1,508 cancelled flights, while September had the least, with 108 cancelled flights.

**Design:**
- The line chart compares several months, with each month represented by a unique color to distinguish it.

![alt text](https://github.com/hadywk/Flight-Delays-and-Cancellations/blob/7be73fcfd43693d641796f91533b091e41bc14f3/no%20of%20flights%20cancelled%20per%20month.png)
