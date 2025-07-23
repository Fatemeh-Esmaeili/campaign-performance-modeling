## 🧾 Dataset Dictionary

| Column Name              | Description                                             |
|--------------------------|---------------------------------------------------------|
| customer_id              | Unique customer identifier                              |
| age                      | Customer's age in years                                 |
| gender                   | Customer gender (Male, Female, Other)                   |
| income                   | Annual income (in NZD, synthetic values)                |
| region                   | Customer's regional location                            |
| tenure_years             | Years since becoming a customer                         |
| received_campaign        | Whether the customer received a marketing campaign (1/0)|
| responded                | Whether the customer responded to the campaign (1/0)    |
| spend_last_month         | Total spend in the previous month                       |
| spend_this_month         | Total spend in the current month (post-campaign)        |
| channel                  | Campaign delivery channel (e.g., Email, SMS)            |
| product_category         | Product offered in the campaign                         |
| is_high_value            | High-value customer flag (based on income & tenure)     |
| credit_score             | Synthetic credit score (300–850)                        |
| days_since_last_purchase | Number of days since last transaction                   |
| customer_segment         | Cluster label (KMeans, based on age & income)           |
