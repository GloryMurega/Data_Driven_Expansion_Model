# Eniac-Expansion-to-Brazil
---
## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Sources](#data-sources)
3. [Tools Used](#tools-used)
4. [ Data Exploration and Analysis (EDA)](#data-exploration-and-analysis-eda)
5. [Data Insights](#data-insights)
6. [Recommendations](#recommendations)
7. [References](#references)
   
## Project Overview
Eniac, a well-established e-commerce platform focusing on Apple-compatible accessories, is eyeing expansion into Brazil. Despite promising revenue data, Eniac lacks local market insights and infrastructure. To bridge this gap, they're considering a partnership with Magist, a Brazilian SaaS company specializing in order management. This collaboration aims to test the market, enhance supply chain efficiency, and build brand awareness. Eniac's primary concerns revolve around Magist's compatibility with high-end tech products and ensuring swift deliveries to uphold customer satisfaction.

## Data Sources
This project utilizes data from the WBSCoding School in CSV format, comprising nine distinct datasets:

- **Products:** Contains data on available products for sale.
- **Product_category_name_translation:** Provides translations of product categories from Portuguese to English.
- **Sellers:** Information on registered sellers in Magist's marketplace.
- **Customers:** Information on customers who made purchases.
- **Geo:** Contains data on zip codes, coordinates, and states.
- **Orders:** Information on orders placed, including multiple products under one order ID.
- **Order_items:** Contains data on individual products within an order.
- **Order_payments:** Information on customer payments, including multiple payments per order.
- **Order_reviews:** Contains customer reviews of orders placed.

## Tools Used
- **SQL:** For data exploration and analysis.
- **Tableau:** For data visualization and insights.
- **PowerPoint:** For presenting findings.
  
## Data Exploration and Analysis (EDA)
#### SQL
- **EDA Questions**
1. **Data base**: What time frame does the Magist sales database cover?
2. **Products**: What kind of tech products does Magist sell? What percentage of its portfolio is tech products? How do their sales perform?
3. **Sellers**: How many sellers does Magist have, and what percentage of them sell tech products?
4. **Prices**: What is the average price of tech products being sold? How do the high_end_products perform in terms of sales?
5. **Delivery timelines**: What’s the average time between the order being placed and the product being delivered? How many orders are delivered on time versus those delivered with a delay?
#### Tableau 
- **EDA Questions**
1. Check non-tech but related products such as accessories, including price range, delivery timelines, customer satisfaction rates, and sales.
2. Analyze phone sales where price > $500 to determine if the customer base is suitable for high-end phones.
3. Explore patterns for delayed orders and possible causes, such as product weight, size and geolocation.
4. Examine delivery times for small products (<2 kg) to compare with expected timelines for Apple products.

## Data Insights
- Segmentation of tech products - tech products accounting for approximately 10% of total sales
- Prices - the average price of tech products sold is €120.65 with approximately 1.10% being high_end_products (Eniac's average item price is €540.)
- Magist Tech sellers - tech sellers make up about 14.67% of all sellers
- Geolocation analysis - Analysis revealed that the majority of sales were concentrated along the coast of Brazil, with São Paulo being the largest market with 60% of total sales
- Magist delivery timelines - Magist has a delivery rate of 8.6% within a 3-day timeframe and 37% after extending the timeframe to 7 days. In São Paulo, however the delivery rate is 87% within a 3-day timeframe. (Eniac's timeline is 2-3 days)
  
## Recommendations
- Forge a strategic market entry partnership with Magist for tech companion products and accessories in São Paulo as a pivotal test market to acquire Brazilian market knowledge.
- Informed by the insights gathered from São Paulo, consider extending to Paraná, a region noted as the second-largest market by sales.
- Evaluate and optimizate the Magist Contract after an year to ensure alignment with Eniac's evolving business objectives and enable the refinement of contractual terms to optimize operational efficiency and mitigate risks.
  
## References
- Tableau knowledge base
- SQL documentation
- Stack Overflow
- WBS Coding School
