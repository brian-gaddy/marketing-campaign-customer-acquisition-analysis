# Project Report: Marketing Campaign Customer Acquisition Analysis

## Executive Summary

This project analyzes customer acquisition and campaign response behavior using a marketing campaign dataset organized around the Four Ps of Marketing: product, price, place, and promotion. The analysis evaluates spending patterns, channel behavior, campaign acceptance, family composition, and geography to identify business actions that could improve customer targeting and marketing return.

The strongest business insight is that high-value customers are not defined by one variable alone. Product category revenue, channel purchasing behavior, household composition, and geography all contribute to customer acquisition performance. Wine and meat products drive the highest revenue, customers without children spend substantially more on average, and Spain has the highest count of last-campaign acceptances in this dataset.

## Business Problem

Marketing teams need to understand which customer traits and shopping behaviors are associated with higher spending and campaign acceptance. The goal of this project is to convert raw customer and transaction data into insights that support segmentation, channel strategy, campaign targeting, and product prioritization.

## Data Preparation

Key preparation steps included validating the customer enrollment date and income fields, cleaning income formatting, reviewing categorical values for education and marital status, imputing missing income values, and engineering new variables for total children, customer age, total spending, and total purchases.

## Exploratory Analysis

The analysis reviewed distributions, outliers, product revenue, channel purchases, campaign response, country-level performance, and customer household characteristics. Correlation analysis was used to evaluate relationships among spending, purchases, shopping channels, children at home, and campaign response.

## Key Findings

1. **Wine is the top revenue product category.** Wine generated the highest revenue among product categories, followed by meat products. This suggests premium or high-frequency product categories should receive priority in campaign messaging.

2. **Customers with fewer children spend more.** Customers with no children at home had the highest average total spending. Average spending decreased substantially as the number of children increased, indicating household composition is an important segmentation variable.

3. **Store purchases remain important.** Store purchases show a strong positive relationship with total purchases. This suggests physical stores remain a meaningful customer acquisition and retention channel rather than being fully displaced by digital or catalog channels.

4. **Catalog and web purchases also matter.** Catalog and web purchase behavior both show positive relationships with total spending and total purchases, supporting an omnichannel strategy.

5. **Campaign response varies by geography.** Spain had the highest count of customers accepting the last campaign, making geography a useful lens for performance review and targeting.

6. **Age alone is not enough for segmentation.** Campaign acceptance rates are not separated cleanly by age group. Age may still be useful, but it should be combined with spending, channel, product, and household features.

## Executive Recommendations

1. **Prioritize high-revenue categories in campaign design.** Lead with wine and meat product offers where customer history supports interest in those categories.

2. **Build household-based customer segments.** Separate customers by number of children at home and tailor promotions based on likely time constraints, purchase frequency, and basket size.

3. **Use an omnichannel strategy rather than replacing stores.** Store, catalog, and web channels all contribute to total purchase behavior. Campaigns should reinforce cross-channel engagement instead of assuming that online channels fully replace physical stores.

4. **Target geography-specific campaign tests.** Use Spain as a benchmark market for campaign response and test whether similar messaging can improve response in lower-performing countries.

5. **Create a high-value customer segment.** Combine high total spending, high purchase frequency, product-category affinity, and campaign-response history into a priority segment for future campaigns.

## Limitations

This project is primarily exploratory and explanatory. It does not yet include predictive modeling, customer lifetime value forecasting, uplift modeling, or campaign ROI optimization. Future work could include classification models to predict campaign response and clustering models to identify customer segments.

## Next Steps

- Build a response prediction model using engineered customer and purchase features.
- Add customer segmentation using clustering.
- Evaluate campaign performance by product category and channel.
- Develop a Power BI or Tableau dashboard for executive reporting.
- Track campaign conversion rates over time if additional campaign history becomes available.
