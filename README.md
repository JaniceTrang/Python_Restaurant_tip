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

<img width="1095" height="614" alt="image" src="https://github.com/user-attachments/assets/14ba30f5-f009-4833-8c61-640e95f103af" />

Skewed Distribution: all histograms are right-skewed, most tips fall in the lower range (2–4), with only a few very high tips (outliers).

Smokers vs. Non-smokers
- Smokers show more high-value tips (up to 10) → stronger outliers.
- Non-smokers cluster more tightly around 2–4, with fewer extreme tips → tipping behavior is more stable.

Males vs. Female:
- Male tips have a wider spread, with more occurrences of larger tips (6–10).
- Female tips distribution is narrower, mostly concentrated between 1–4, with fewer high-value tips beyond 5. 

Weekdays vs. Weekends
- Weekends have a wider spread with more higher tips.
- Weekdays concentrate mostly in the low range (1–3) with very few high tips → suggesting large tips mostly happen on weekends.

Lunch vs. Dinner
- Lunch tips are tightly concentrated around 2–3 and rarely exceed 5 → lunch tipping is modest.
- Dinner tips are spread wider, with more cases reaching 8–10 → dinners are more likely to generate higher tips
