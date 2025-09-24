## Restaurant Tips Analysis
#### Project description
This project aims to use the restaurant tips dataset to practice creating composition plots and visualizations. We will examine the relationship between different variables and the tips given.
#### Data Description
The dataset consists of information from 244 restaurant bills, collected in the US in 1987, includes detail about:
- total_bill: total bill amount
- tip: tip amount given
- sex: gender of the payer
- smoker: whether the payer was a smoker or not
- day: day of the week
- time: lunch or dinner
- size: size of the party

Acess the data with this link:
https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv

#### Main goals:
This analysis is to explore tipping behavior in a restaurant setting, comparing groups (smokers vs. non-smokers, male vs. female) and dining contexts (weekday vs. weekend, lunch vs. dinner).

#### Results and Insights:
<img width="718" height="151" alt="image" src="https://github.com/user-attachments/assets/486f6fcc-819f-4545-a2eb-31a4328477ce" />

When comparing tipping behavior across groups, several patterns emerge:
- Smokers tend to leave slightly higher tips than non-smokers, both in terms of maximum ($10.00 vs. $9.00) and median values ($3.00 vs. $2.74), though their average tips are nearly identical.
- Male customers tip more generously than female customers, with higher maximum ($10.00 vs. $6.50), mean ($3.09 vs. $2.83), and median values ($3.00 vs. $2.75).
- Weekends also show stronger tipping behavior compared to weekdays, with higher maximum ($10.00 vs. $6.70), mean ($3.12 vs. $2.76), and median tips ($3.00 vs. $2.50).
- Finally, dinner service tends to receive larger tips than lunch, reflected in higher maximum ($10.00 vs. $6.70), mean ($3.10 vs. $2.73), and median values ($3.00 vs. $2.25).


1.Overall Distribution of Tips
* Most tips fall between 2 and 4 dollars, with fewer cases above 6.
* Distribution is right-skewed: a small number of very high tips raise the average above the median.

2.Smokers vs. Non-Smokers
* Mean tips are nearly identical (~3.0).
* Median: smokers = 3.00, non-smokers = 2.74 → smokers might tip slightly more.
* Max tip: smokers (10.00) > non-smokers (9.00).

3.Gender Differences
* Males tip more in absolute terms (mean = 3.09) than females (mean = 2.83).
* Medians are similar (3.00 vs. 2.75).
** This indicates men may leave larger tips, but the overall difference is not dramatic.

4.Weekdays vs. Weekends
* Weekends show higher mean (3.12) and median (3.00) compared to weekdays (2.76 and 2.50).
** Customers tend to tip more generously during weekends, likely due to larger social gatherings.

5.Lunch vs. Dinner
* Dinner tips are higher (mean = 3.10, median = 3.00) than lunch (mean = 2.73, median = 2.25).
** Suggests dinner occasions involve bigger bills and larger tips.
