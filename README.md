# Customer-Churn-Analysis_PowerBI
## Goal
The goal of this case study is to investigate a dataset from an example telecom company called Databel and analyze their churn rates. The stakeholders need to understand why customers are churning at the rate they are, and how to reduce churn. I'll start with an exploratory data analysis to gain some general insights about churn rate for different customer location, age, contract plans, and other factors. Then, based on the findings, I'll share recommendations for the company to reduce the churn. Finally, I'll create dashboard-style pages and arrange them into stories, so that the results can be shared with stakeholders. The full analysis and visualization is made in PowerBI Desktop, with a creation of additional measures and calculated columns to support the analysis.
## EDA
- Number of customers, churned customers and churn rate <br>
![image](https://github.com/monika-czulak/Customer-Churn-Analysis_PowerBI/assets/109820128/f482b1d1-514f-41c8-b1d8-621a114cd306)
- Churn reasons </br>
![image](https://github.com/monika-czulak/Customer-Churn-Analysis_PowerBI/assets/109820128/6d51f0f4-00cf-4137-ba06-b3aea2d9b14c)
![image](https://github.com/monika-czulak/Customer-Churn-Analysis_PowerBI/assets/109820128/027bf9e2-1ee2-44e7-9adc-649a0bfe05d9)
- Customer location </br>
![image](https://github.com/monika-czulak/Customer-Churn-Analysis_PowerBI/assets/109820128/db3238c8-10fc-4f35-af13-1494883cb787)
- Demographics </br>
![image](https://github.com/monika-czulak/Customer-Churn-Analysis_PowerBI/assets/109820128/b6897f9e-d2d7-48aa-8b8a-73dccc57a63e)
![image](https://github.com/monika-czulak/Customer-Churn-Analysis_PowerBI/assets/109820128/3be6261f-29ca-47dc-9698-b3fffa2f2321)
- Inspecting groups </br>
![image](https://github.com/monika-czulak/Customer-Churn-Analysis_PowerBI/assets/109820128/ad186028-b8cd-4cfc-b7f3-b65684ddbfb6)
- Contract plans </br>
![image](https://github.com/monika-czulak/Customer-Churn-Analysis_PowerBI/assets/109820128/c3f7d767-f3d6-4546-bf06-76035d5713f5)
![image](https://github.com/monika-czulak/Customer-Churn-Analysis_PowerBI/assets/109820128/7c4174a0-c274-4a4e-9f75-2f34432237e6)
- Unlimited vs. limited data plan vs. data consumption </br>
![image](https://github.com/monika-czulak/Customer-Churn-Analysis_PowerBI/assets/109820128/bdf3561f-d095-4c6f-995e-1403d2530cee)
![image](https://github.com/monika-czulak/Customer-Churn-Analysis_PowerBI/assets/109820128/3725336b-dd91-49f9-84e5-4fa09ef056ed)
- International plans and customer activity </br>
![image](https://github.com/monika-czulak/Customer-Churn-Analysis_PowerBI/assets/109820128/16c8d6a4-1fe1-4cdf-b657-0a3a9ac02893)
- Churn rate over time </br>
![image](https://github.com/monika-czulak/Customer-Churn-Analysis_PowerBI/assets/109820128/efc8f727-e318-4e2a-88dc-411e2965e389)
- Service calls vs. State and churn label </br>
![image](https://github.com/monika-czulak/Customer-Churn-Analysis_PowerBI/assets/109820128/fac5f0e7-f31c-41c4-a976-63481c617e82)

## Findings
- Avg churn rate of 26.86%, above avg churn rate for senior (60+) customers. However, senior customers are the smallest population of customers. Majority of customers are between 30-60 years old.
- The main churn reason related to category "Competitor", which means that the customers are looking for better offers in terms of devices or pricing. In top 3 reasons there is also an attitude of support person, with 11.3% of unhappy customers.
- For the contract types, the majority of customers have month-to-month plans (51%), but in this group the biggest churn is observed vast above the average (45% for male and 47% for female customers). 
- Company offers group plans with discounts for customers from the same household. In the group of 2 or more customers the churn is significantly lower (up to 8%), while for the individual plans the churn is almost 33%.
- Higher churn observed for customers who consume less than 5 GB of data but own an unlimited data plan.
- Long term customers are more loyal than the ones with short account length. General churn trend is decreasing over time.
- The sky-high churn is among users who own international plan but don't make international calls (71%).
- Customers who are making service calls are more likely to churn. Currently the average number of service calls per customer is 0,92.

## Recommendations
