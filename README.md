Model 1 Outcome
•	Primary Drivers:
o	Key features influencing the outcome include DURATION (call duration), PDAYS (days since last contact), NR.EMPLOYEES (number of employees), month_numeric (month of the year), EURIBOR3m (three-month Euro Interbank Offered Rate), and CONS_PRICE_IDX (consumer price index).
o	Longer call durations, more recent contact, and certain months lead to more "Yes" classifications. On the other hand, higher economic indicators such as NR.EMPLOYEES and EURIBOR3m tend to correlate with "No" outcomes.
•	Outcome Summary:
o	The model classifies clients as likely to respond "Yes" if recent contact (PDAYS) and longer call durations are present.
o	Economic conditions and certain months (seasonality) play a significant role in determining the likelihood of a positive response.
Model 2 Outcome
•	Primary Drivers:
o	Key features in this model are AGE, DURATION (call duration), PDAYS, POUTCOME (previous campaign outcome), HOUSING (housing loan status), and DAY OF WEEK.
o	Clients are more likely to respond "Yes" if they have longer call durations, favorable previous outcomes (POUTCOME), recent contact (PDAYS), and specific days of the week.
o	Factors such as AGE and housing loan status influence the likelihood of a "No" outcome, indicating demographic and financial stability considerations.
•	Outcome Summary:
o	This model classifies clients with recent contact and positive outcomes in previous campaigns as more likely to respond positively.
o	Certain demographic factors like age and loan status contribute to a "No" outcome, indicating these clients may be less receptive.
