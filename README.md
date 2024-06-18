**Churning bank customers**

link to Jupyter Notebook - http://localhost:8888/notebooks/Bank%20Customer%20Churn.ipynb

• Every bank wants to hold their customers accountable for sustaining their business, and so is this Anonymous Multinational bank. We have customer data of account holders at Anonymous Multinational Bank to understand the customer churn

• Exploring the correlation between variables such as credit score, age, tenure, balance, and geography with customer churn.

• Assess the impact of demographic factors like gender and the presence of credit cards on churn rates.

• Additionally, analyze customer satisfaction scores and complaint resolutions to identify areas for service improvement.

• Utilize your analytical skills to find factors contributing to potential customer churn.

• This project provides an opportunity to enhance customer retention strategies by uncovering patterns and insights within the dataset.

**DATA DESCRIPTION:**

RowNumber — corresponds to the record (row) number and does not affect the output.

CustomerId — contains random values and has no effect on customers leaving the bank.

Surname — the surname of a customer has no impact on their decision to leave the bank.

CreditScore — can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank.

Geography — a customer’s location can affect their decision to leave the bank.

Gender — it’s interesting to explore whether gender plays a role in a customer leaving the bank.

Age — this is certainly relevant, since older customers are less likely to leave their bank than younger ones.

Tenure — refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.

Balance — also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.

NumOfProducts — refers to the number of products that a customer has purchased through the bank.

HasCrCard — denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank.

IsActiveMember — active customers are less likely to leave the bank.

EstimatedSalary — as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.

Exited — whether or not the customer left the bank.

Complain — customer has complaint or not.

Satisfaction Score — Score provided by the customer for their complaint resolution.

Card Type — type of card hold by the customer.

Points Earned — the points earned by the customer for using a credit card.


**Observations:**
Based on the above observation, it is clear that there is not much difference in the customers who churned across geography except for the bank account balance.
Unfortunately, customers who did not exit and who exited both have similar profiles except for the past complaints, indicating a high risk of customer churn in the future if any complaints arise.
Germany has the highest churn rate.
The churned customer profile is the same for all regions except the balance.
Customers are aged between 38 - 50 years.
The majority of customers are female and have only 1 product.
Credit score is between 600 - 700.
The majority of customers are inactive.
All the customers had complaints but their satisfaction score had no impact
Customers in Spain & France had 0 balance.
Customers in Germany had no 0 balance account but very high balance account of 1 lac to 1.40 lacs
Churned Customer Profile

Female customers aged between 38 - 50 years with credit scores of 600-700 who had only 1 product and were not Active members with past complaints and 0 balance in their account tend to churn from the bank in France & Spain.

Female customers aged between 38 - 50 years with credit scores of 600-700 who had only 1 product and were not Active members with past complaints and balance between 1lac to 1.40 lac in their account tend to churn from the bank in Germany.

**Recommendations:**
Targeted promotions and offers for Female customers.
Cross-sell more products to the exiting customers as people with just 1 product tend to churn the most.
Customers who did not churn (loyal customers) have ages between 30-40. Focus on providing more services and credit card benefits to these customers so they continue to stay with the bank.
Incentivise customers having a credit score of 600-700 and age between 38-50 by offering more points or offers.
Focus on customers with 0 Balance in their account as they might also have accounts in competitor's banks. Run a campaign to retain them or to transact with this bank more which will keep the customer Active with the Bank.
In Germany, customer service needs to be improved as the majority of the customers who exited had no 0 balance account indicating a possible lack of or poor customer service. Collect feedback from these customers which is essential to understand the reason for churn here.
Focus on improving the product offering in Germany.
Further, analyse the type or category of customer complaints to identify common complaints and fix the issue at the source.
This will help identify the concern even before it occurs and reduce customer complaints and customer touch points.
 
