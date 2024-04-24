# Customer-Churn-Analysis_PowerBI
![image](https://github.com/monika-czulak/Customer-Churn-Analysis_PowerBI/assets/109820128/b660f9f5-209d-4c76-940a-b397865d822e)

## Goal
The goal of this analysis is to investigate a dataset from a fictional telecom company called Databel and analyze their churn rates. The stakeholders would like to understand why customers are churning at the rate they are, and how to reduce churn. I'll start with an exploratory data analysis to gain some general insights about churn rate for different customer location, age, contract plans, and other factors. Then, based on the findings, I'll share recommendations for the company to increasy customer satisfaction and loyalty. Finally, I'll create dashboard-style pages and arrange them into stories, so that the results can be shared with stakeholders. The full analysis is made in PowerBI Desktop, using DAX and visualizations.
## EDA
- Number of customers, churned customers and churn rate <br>
![image](https://github.com/monika-czulak/Customer-Churn-Analysis_PowerBI/assets/109820128/f482b1d1-514f-41c8-b1d8-621a114cd306)
- Churn reasons </br>
![image](https://github.com/monika-czulak/Customer-Churn-Analysis_PowerBI/assets/109820128/6d51f0f4-00cf-4137-ba06-b3aea2d9b14c)
![image](https://github.com/monika-czulak/Customer-Churn-Analysis_PowerBI/assets/109820128/027bf9e2-1ee2-44e7-9adc-649a0bfe05d9)
- Churned customers location </br>
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
- Prioritize retention efforts towards senior customers, despite their smaller population, due to their higher churn rate. Implement targeted loyalty programs or discounts to incentivize their continued loyalty.
- Focus on customers aged 30-60, the majority of Databel's customer base, by offering personalized deals and tailored customer service experiences.
- Address the main churn reason related to "Competitor" by reviewing and potentially adjusting pricing strategies and device offers to remain competitive in the market.
- Train support personnel to be more empathetic and attentive to customer needs, reducing dissatisfaction and churn related to support interactions.
- Encourage customers with month-to-month plans to switch to longer-term contracts by offering incentives such as discounted rates or free device upgrades.
- Promote group plans with discounts for households to capitalize on the lower churn rates observed in this segment.
- Review data plans to ensure they align with customers' actual usage patterns. Consider offering tiered data plans or personalized data recommendations to better match customers' needs.
- Educate customers on the benefits of their data plans and encourage upgrades or downgrades as necessary to reduce churn among customers with unlimited plans but low data usage.
- Enhance the overall customer experience to increase loyalty, particularly among long-term customers. Offer exclusive perks, rewards, or personalized communications to show appreciation for their loyalty.
- Proactively reach out to customers who own international plans but don't make international calls to understand their needs and potentially offer alternative solutions or incentives to retain them.
- Implement proactive customer service strategies to address issues before they escalate, reducing the likelihood of churn among customers who make service calls.
- Analyze service call data to identify recurring issues or pain points and take proactive measures to resolve them.
- Continuously monitor churn trends and customer feedback to identify emerging issues and opportunities for improvement.

## Summary
Definitely there is an area for improvement for Databel in terms of customer churn. By considering the above findings and recommendations Databel should be able to improve on their services, leading to increased overall customer satisfaction and loyalty.
