# telecom-churn
# Business Problem Overview

In the highly competitive telecom industry, customer retention is a significant challenge due to the ease with which customers can switch between multiple service providers. The industry sees an annual churn rate of 15-25%, and with the cost of acquiring new customers being 5-10 times more than retaining existing ones, focusing on customer retention has become crucial, especially for incumbent operators aiming to retain high-value customers.

To combat customer churn, telecom companies need to predict which customers are at high risk of churn and identify the main indicators contributing to it. This project involves analyzing customer-level data from a leading telecom firm to build predictive models for this purpose.

## Understanding and Defining Churn

Churn prediction varies significantly between the two main payment models in the telecom industry: postpaid (monthly/annual billing after service usage) and prepaid (advance payment for services). In postpaid, churn is more straightforward as customers usually inform the operator when switching. However, in prepaid, which is prevalent in India and Southeast Asia, churn prediction is challenging as customers can stop using services without notice, making it difficult to distinguish between temporary non-usage and actual churn.

### Definitions of Churn

Churn can be defined in several ways:

- **Revenue-based churn**: Identifying customers who have not used any revenue-generating services like mobile internet, outgoing calls, or SMS over a certain period. This could be measured through metrics like monthly revenue generation below a specific threshold.

- **Usage-based churn**: Focusing on customers with no activity, whether incoming or outgoing, over a defined period. This project will utilize the usage-based definition to define churn.

### High-Value Churn

In markets like India and Southeast Asia, around 80% of revenue comes from the top 20% of customers, termed as high-value customers. Targeting the churn among these customers can significantly impact revenue retention. This project aims to identify and predict churn among these high-value customers using a specific metric to define them.
