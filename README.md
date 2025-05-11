# NEW DELHI FOOD DELIVERY SERVICE DATA ANALYSIS

# TABLE OF CONTENT
- NEW DELHI FOOD DELIVERY SERVICE DATA ANALYSIS - OVERVIEW
- OBJECTIVES OF THE ANALYSIS
- TOOLS
- DATA SOURCE
- DESCRIPTION OF DATA
- DATA PREPROCESSING
- EXPLORATORY DATA ANALYSIS (EDA)
- DATA VISUALIZATION
- INSIGHTS
- RECOMMENDATIONS
- EXPECTED OUTCOMES

# NEW DELHI FOOD DELIVERY SERVICE DATA ANALYSIS - OVERVIEW
Food delivery has become an essential part of daily life in cities like New Delhi, where convenience and quick service are highly valued. However, despite growing demand, not all delivery businesses manage to stay profitable. This project focuses on a New Delhi-based food delivery service that has completed around 1,000 orders but is currently operating at a loss.
As the data analyst for this business, my role is to identify the key factors contributing to these losses. Through a detailed cost analysis including total revenue, commission, and operational cost, I aim to identify key problem areas and recommend data-driven strategies to restore profitability. The goal is to help the company make more informed decisions and take steps toward achieving profitability.

# OBJECTIVES OF THE ANALYSIS
The main purpose of the analysis are to:
- Conduct a detailed cost analysis using exploratory data analysis (EDA) of the New Delhi food delivery service.
- Evaluate the profitability of the business
- Propose strategic recommendations for improvement
- Simulate the potential impact of the proposed strategies

# TOOLS
Microsoft Excel- Data cleaning & preprocessing.

# DATA SOURCE
The data used in this analysis was obtained from Statso.io. [Download Here](https://statso.io/optimizing-cost-and-profitability-case-study/)

# DESCRIPTION OF DATA
This dataset contains columns such as:
- ORDER ID: A unique identifier assigned to each food order.
- CUSTOMER ID: A unique identifier for each customer who places an order.
- RESTAURANT ID: A unique identifier for each restaurant within the platform.
- ORDER DATA AND TIME: The date and time when the order was placed by the customer.
- DELIVERY DATE AND TIME: The date and time when the order was delivered to the customer.
- ORDER VALUE: The total monetary value of the order, including food, drinks, or any other items ordered.
- DELIVERY FEE: The amount charged to the customer for delivery services.
- PAYMENT METHOD: The method used by the customer to pay for the order.
- DISCOUNTS AND OFFERS: The promotional deals or percentage discounts applied to the order.
- COMMISSION FEE: The fee charged by the service or company for facilitating the order.
- PAYMENT PROCESSING FEE: The fee charged by the payment gateway for processing the transaction.
- REFUNDS/CHARGEBACKS: The amount refunded or reversed due to customer complaints, order issues, or disputes

# DATA PREPROCESSING
To ensure the dataset was accurate and ready for analysis, the following data cleaning steps were carried out:
- Unmerging Columns - Used the Text to Columns function to separate combined data in key fields:
  * Discount and Orders were unmerged to create two distinct columns.
  * Delivery Date and Time were split into separate columns for better analysis and formatting.
- Handling Missing Values
  * Checked for missing data across all key columns.
  * For orders without a specified discount type, applied a “standard” placeholder to maintain consistency.
- Removing Duplicates
  * Ensured there were no duplicate records by checking for repeated entries, especially in the Order ID and Timestamp columns.
- Formatting Dates
  * Standardized the Date column to ensure all entries followed a uniform format (e.g., DD-MM-YYYY), enabling accurate time-based analysis

# EXPLORATORY DATA ANALYSIS (EDA)
The first objective of this project was to carry out a detailed total cost analysis, which was accomplished through exploratory data analysis (EDA). This involved examining key financial metrics, revenue streams, and associated costs to understand the current financial position of the business. Below is a summary of the findings:
- Key Metrics Identified Through EDA:
  * Total Orders: 1,000
  * Total Revenue: ₹126,990

- Cost Breakdown:
  * Delivery Cost: ₹28,620
  * Discounts Given: ₹174,257
  * Payment Processing Fees: ₹29,832
  * Refunds/Chargebacks: ₹28,300
  * Total Cost:₹261,009

**Insights:** Through EDA, it was discovered that commissions are the main sources of revenue, while significant costs are being incurred through discounts, delivery cost, payment processing fees, and refunds. This imbalance between revenue and cost is a major contributor to the current financial losses.
This analysis fulfills the first goal of the project, to understand and break down the total cost structure of the business using the available data

# PROFITAILITY EVALUATION
Following the total cost analysis conducted through exploratory data analysis (EDA), a profitability evaluation was performed to assess the financial performance of the food delivery business.
- Summary of Financials:
  * Total Revenue: ₹126,990.00
  * Total Cost: ₹261,009.85
- Profit/Loss Calculation:
  * Profit/loss = Total Revenue – Total Cost = ₹126,990 - ₹261,009.85 = -₹134,019.85
- Profit Margin:
  * Profit Margin = (Profit/loss/Total Revenue )  * 100 = -105.54%

**Conclusion:** With a negative profit margin of –105.54%, the business is currently highly unprofitable. This means the company is spending more than double what it earns in revenue, a clear sign of unsustainable operations.
The key cost drivers contributing to this loss include:
- Discounts Offered: ₹174,257
- Payment Processing Fees: ₹29,832
- Refunds and Chargebacks: ₹28,300
- Delivery Costs: ₹28,620

Despite completing 1,000 orders, the revenue generated is not nearly enough to cover operating expenses. Immediate cost-cutting measures and strategic revenue improvements are essential for moving toward profitability.

# STRATEGIC RECOMMENDATIONS FOR IMPROVEMENT
To address the significant losses identified through profitability evaluation, the following targeted strategies are recommended to improve revenue, reduce unnecessary costs, and strengthen operational efficiency. 
1. Increase Commission Rate to 20%
   - Current Situation: Revenue from commissions is not sufficient to cover overall operational costs.
   - Recommendation: Increase the commission rate to 20% across all orders. This will directly boost revenue without affecting customer experience. Ensure transparency with restaurant partners, highlighting the platform’s marketing reach and delivery support to justify the increase.
2. Eliminate 50% Promo Discounts and Affected Orders
   - Current Situation: Promo discounts account for a major portion of the total cost (₹127,727.), and were applied to 201 orders, significantly reducing profit margins.
   - Recommendation:
     * Scrap all 50% promotional discounts moving forward.
     * Discontinue any ongoing campaigns or codes linked to this discount model.
     * Focus instead on smaller, targeted offers for new customers or during off-peak hours.
3. Implement Strict Refund & Chargeback Policies
   - Current Situation: Refunds and chargebacks total ₹28,300, heavily impacting net profitability.
   - Recommendation:
     * Introduce a clear refund policy that limits full refunds to only verified service failures.
     * Require evidence (e.g., photo proof, delivery time logs) for refund claims.
     * Penalize repeated misuse of the refund system by users and enforce quality checks with vendors.
     * Offer partial credits or in-app wallet refunds instead of cash reimbursements where possible.

# IMPACT SIMULATION OF PROPOSED STRATEGIES
To evaluate the potential effect of the recommended strategies, a simulation was conducted using revised assumptions and updated financial projections. The goal was to estimate the new financial standing of the business after implementing key changes, including increasing commission rates, eliminating high-discount orders, and enforcing stricter refund policies.

**Key Improvements:**
- Increased Commission Revenue: By raising the commission rate to 20%, revenue rose from ₹126,990 to ₹166,786.60.
- Reduced Discounts: Eliminating 201 high-discount orders (worth ₹110,018) significantly lowered overall discount costs.
- Positive Profit Margin: The business shifted from a –105.54% loss margin to a 20.09% profit margin, indicating the company is now very profitable.
