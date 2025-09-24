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
- Examine tipping behavior across different groups.
- Compare tip sizes between smokers and non-smokers.
- Analyze how gender, day, and party size influence tip amounts.

#### Insights:
A. Smokers vs. Non-Smokers
<img width="1100" height="411" alt="image" src="https://github.com/user-attachments/assets/9007b5d8-46b7-4937-9737-066dab7e1b99" />

<img width="295" height="151" alt="image" src="https://github.com/user-attachments/assets/013aee1e-3b7a-4022-ad3f-665326cc607f" />
Mean tips are nearly identical (~3.0).
Median: smokers = 3.00, non-smokers = 2.74 → smokers might tip slightly more.
Max tip: smokers (10.00) > non-smokers (9.00), suggesting smokers have more extreme high tips.

Based on the table of central tendency measures above, there are some insights about tipping behavior across different customer groups:

- Smokers vs. Non-Smokers: Mean tips are almost the same (Smokers: $3.01, Non-Smokers: $2.99). The median is slightly higher for smokers ($3.00 vs. $2.74), suggesting smokers may tip a bit more typically.

- Gender: Men leave slightly higher tips (Mean: $3.09, Median: $3.00) than women (Mean: $2.83, Median: $2.75).

- Weekdays vs. Weekends: Tips are higher on weekends (Mean: $3.12, Median: $3.00) than on weekdays (Mean: $2.76, Median: $2.50).

- Lunch vs. Dinner: Dinner tips are higher (Mean: $3.10, Median: $3.00) compared to lunch (Mean: $2.73, Median: $2.25).

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
