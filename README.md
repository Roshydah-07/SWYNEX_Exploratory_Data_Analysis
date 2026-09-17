## Task 2: Exploratory Data Analysis & Key Insights

### 1. High-Level Performance Metrics (KPIs)
To establish an operational baseline, key performance indicators were calculated across the sanitized dataset:
* **Total Revenue:** Sum of all transactional spending across processed orders.
* **Order Volume:** Total count of unique customer transactions post-deduplication.
* **Average Order Value (AOV):** Mean monetary spend per transaction.
* **Total Units Sold:** Cumulative sum of items sold across all product lines.
* **Items Per Order:** Average basket size per customer transaction.

### 2. Key Business Insights
* **Insight 1 (Product Revenue Contribution):** High-margin food items generate the highest overall revenue share, outperforming standalone beverage items.
* **Insight 2 (Channel Performance):** In-store transactions generate higher overall order volume and larger basket sizes compared to takeaway orders.
* **Insight 3 (Payment Spend Behavior):** Customers using cashless methods (Credit Card or Digital Wallet) average higher order values than cash users.
* **Insight 4 (Basket Size Concentration):** Most customer purchases concentrate between 2 and 4 items per order, highlighting an opportunity for food-beverage combo bundling.
* **Insight 5 (POS Attribution Gaps):** A notable share of sales attribution sits under unrecorded category flags for payment or location, signaling a need for improved point-of-sale logging.

### 3. Visualizations & Visual Evidence
The following visual artifacts have been generated from Excel Pivot Tables and added to the repository:
* `images/kpi_summary.png`: Summary view of high-level KPIs and qualitative insights.
* `images/revenue_by_item.png`: Bar chart breakdown of sales volume and item distribution.
* `images/location_distribution.png`: Donut chart illustrating channel breakdown between In-Store and Takeaway orders.
* `images/aov_by_payment.png`: Column chart displaying average order value per payment method.
