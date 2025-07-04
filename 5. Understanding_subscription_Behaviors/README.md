Project Description
A SaaS company seeks to uncover what drives its clients to renew their subscriptions. Combine and analyze the company's data to provide insights into its customer behavior and trends.



<div style="text-align: center; padding: 20px;">
    <img src="austin-distel-744oGeqpxPQ-unsplash.jpeg" alt="​​Subscription Renewal Insights for a SaaS Company" width="450"/>
</div>


<!-- Image source - https://unsplash.com/photos/person-using-macbook-pro-744oGeqpxPQ
-->

    
A SaaS company seeks to uncover what drives its clients to renew subscriptions. They’ve collected data on client details, subscription records, and economic indicators and would like to connect them to better understand its clients’ behavior. 

They’ve tasked you with analyzing these datasets to identify the key factors influencing clients’ decisions to renew their subscriptions. 

Your analysis will provide them with insights into which customers are renewing their products and the reasons behind their renewals. The company can leverage these insights to make informed decisions to increase renewal rates and improve customer loyalty, helping them stay competitive and ensure long-term growth.


## The Data

The company have provided you with three datasets for your analysis. A summary of each data is provided below.

## `client_details.csv`

| Column         | Description|
|----------------|---------------------------------------------------------------|
| `client_id`    | Unique identifier for each client. |
| `company_size` | Size of the company (Small, Medium, Large).|
| `industry`     | Industry to which the client belongs (Fintech, Gaming, Crypto, AI, E-commerce).|
| `location`     | Location of the client (New York, New Jersey, Pennsylvania, Massachusetts, Connecticut).|

## `subscription_records.csv`

| Column             | Description   |
|--------------------|---------------|
| `client_id`        | Unique identifier for each client.|
| `subscription_type`| Type of subscription (Yearly, Monthly).|
| `start_date`       | Start date of the subscription - YYYY-MM-DD.|
| `end_date`         | End date of the subscription - YYYY-MM-DD.|
| `renewed`          | Indicates whether the subscription was renewed (True, False).|

## `economic_indicators.csv`

| Column           | Description                                       |
|------------------|---------------------------------------------------|
| `start_date`     | Start date of the economic indicator (Quarterly) - YYYY-MM-DD.|
| `end_date`       | End date of the economic indicator (Quarterly) - YYYY-MM-DD.|
| `inflation_rate` | Inflation rate in the period.|
| `gdp_growth_rate`| Gross Domestic Product (GDP) growth rate in the period.|