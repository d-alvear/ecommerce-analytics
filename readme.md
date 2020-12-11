# E-Commerce Analysis
![img](reports\images\zui-hoang-unsplash.jpg)

## Questions/Tasks

### 1. Define Metrics

The three major company-wide metrics:

* Growth/Retention

    - Monthly New Customers
    - Monthly Retention Rate: (retained customers from prev. month/total customers)

* Engagement/Transactions

    - Monthly Active Customers
    - Daily Active Customers
    - Total Monthly Orders
    - Total Daily Orders

* Monetization

Product Level Metrics:
* Daily views per product/category
* Rates for each action: 
    - `view`
    - `add to cart`
    - `remove from cart`
    - `purchase`

### 2. Customer Segmentation

Use Recency-Frequency-Monetary Value (RFM) segmentation methods. Will have segments resembling the following:

* Low Value

    - Less active customers (fewer purchases, less engagement)
    - Very low revenue

* Mid Value

    - Using the site fairly frequently
    - Moderate revenue

* High Value

    - High revenue and engagement

RFM Metrics:

* Recency

    - How many days since last purchase as score
    - How does this compare to the mean score?

* Frequency

    - Total number of orders per customer

* Revenue

    - Total revenue per customer

### 3. Customer Lifetime Value Prediction

CLV = (avg. purchase value * avg. purchase frequency rate) * customer lifespan

* Median acquisition cost per customer for an ecommerce company is $12

Steps:

1. Define the time frame

    - I have 5 months of data

2. Identify features to predict future lifetime value

    - Use the RFM metrics

3. Calculate LTV for training the model


4. Run the model
5. Evaluation

### 4. Churn Prediction

Here I'll label a customer as churned if they haven't engaged with the site in 90+ days.

### 5. Predict Next Purchase Date

### 6. Predict Sales

### 7. 