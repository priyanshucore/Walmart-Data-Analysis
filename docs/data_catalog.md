# Data Catalog for Walmart Data

## Overview
This dataset, sourced from **[Kaggle](https://www.kaggle.com/datasets/ankitrajmishra/walmart/data)**, contains sales data for Walmart stores across various locations. The data includes key metrics that help analyze sales performance, seasonal trends, and other influential factors.

---

### **walmart_data**
- **Purpose:** The dataset is intended to analyze sales performance, seasonality & trends, store performance, etc.
- **Columns:**

| Column Name            | Data Type     | Description                                                                                   |
|------------------------|---------------|-----------------------------------------------------------------------------------------------|
| transaction_id         | INT           | Surrogate key uniquely identifying each sales transaction.                                    |
| customer_id            | INT           | Unique numerical identifier assigned to each customer.                                        |
| product_id             | INT           | Unique identifier representing each product for tracking and referencing.                     |
| product_name           | OBJECT        | Name of the product sold.                                                                     |
| category               | OBJECT        | Category or classification of the product.                                                    |
| quantity_sold          | INT           | Number of units of the product sold in the transaction.                                       |
| unit_price             | FLOAT         | Price per unit of the product.                                                                |
| transaction_date       | OBJECT        | Date when the sales transaction occurred.                                                     |
| store_id               | INT           | Unique identifier for the store where the transaction took place                              |
| store_location         | OBJECT        | Geographical location of the store.                                                           |
| inventory_level        | INT           | Current inventory level for the product.                                                      |
| reorder_point          | INT           | Stock level that triggers a reorder for the product.                                          |
| reorder_quantity       | INT           | Quantity of product to reorder once the reorder point is reached.                             |
| supplier_id            | INT           | Unique identifier for the product’s supplier.                                                 |
| supplier_lead_time     | INT           | Time in days for the supplier to deliver the product.                                         |
| customer_age           | INT           | Age of the customer at the time of the transaction.                                           |
| customer_gender        | OBJECT        | Gender of the customer.                                                                       |
| customer_income        | FLOAT         | Estimated annual income of the customer.                                                      |
| customer_loyalty_level | OBJECT        | Loyalty tier or level assigned to the customer.                                               |
| payment_method         | OBJECT        | Payment method used in the transaction.                                                       |
| promotion_applied      | BOOL          | Indicator of whether a promotion or discount was applied.                                     |
| promotion_type         | OBJECT        | Type or category of promotion applied.                                                        |
| weather_condition      | OBJECT        | Weather conditions at the time of the transaction.                                            |
| holiday_indicator      | BOOL          | Indicator of whether the transaction occurred during a holiday period.                        |
| weekday                | OBJECT        | The day of the week on which the transaction occurred.                                        |
| stockout_indicator     | BOOL          | Indicator of whether the product was out of stock.                                            |
| forecasted_demand      | INT           | Predicted demand for the product.                                                             |
| actual_demand          | INT           | Actual demand for the product.                                                                |
