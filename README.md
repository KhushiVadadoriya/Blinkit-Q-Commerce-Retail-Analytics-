# Blinkit Q-Commerce Retail Analytics — Data-Driven Business Insights

## Executive Summary
Blinkit aims to optimize its quick-commerce operations but lacks clarity on which outlets, products, and regions actually drive performance. The key business problem is inefficient inventory and outlet strategy across locations.

Using transactional and outlet data, this project identifies high-value purchase behavior (average sale: $141), strong customer tilt toward low-fat/health-focused items, and surprising dominance of Tier 3 outlets in total revenue. Essentials-fruits, vegetables, snacks, dairy, and household products-form the backbone of sales.

The solution involves building a structured analytics dashboard to uncover hidden patterns, guide operational decisions, and propose strategic recommendations around outlet optimization, SKU strategy, bundling, and regional expansion.

Next steps include building forecasting models, customer segmentation, and automated reporting pipelines.

**Impact:**

A clarity-focused dashboard and analytics workflow that highlights high-value opportunities, outlet-level inefficiencies, and category-wise revenue levers - enabling smarter business decisions for Blinkit and similar Q-Commerce models.



## Business Problem

Blinkit operates across multiple outlet types, sizes, and regions, but does not have a clear understanding of:

* Which outlet tiers generate the most revenue

* Which product categories contribute most to sales

* Whether customer preferences differ by fat content, outlet type, or region

* How outlet size impacts revenue

* Whether older or newer outlets perform better

* Where operational inefficiencies may be causing revenue leakage

The challenge was to convert raw transactional data into actionable insights that inform strategic decision-making.


## Methodology

A unified, multi-tool analytics workflow was used to extract insights from the Blinkit dataset:

**1. Data Cleaning & Preparation (SQL)**

* Cleaned raw dataset (missing values, inconsistent categories)

* Standardized column formats

* Applied SQL queries to compute basic KPIs such as total sales, item counts, and ratings

* Prepared reliable, analysis-ready tables for Python and Power BI

**2. Exploratory Data Analysis (Python)**

* Performed summary statistics using Pandas

* Conducted detailed EDA with Matplotlib/Seaborn

* Identified category patterns, outlet behavior, and initial sales trends

* Validated SQL findings with Python visual checks

**3. BI Dashboard Development (Power BI)**

* Imported the cleaned and analyzed dataset

* Built visual KPIs (Total Sales, Avg Sale, Ratings, Item Count)

* Created visual comparisons for fat content, outlet type, outlet size, and location tiers

* Designed interactive filters for user-driven exploration

* Translated SQL + Python insights into a single dashboard story

**4. Insight Consolidation**

* Cross-validated insights across all three tools

* Compared outlet segments, category contributions, and customer tendencies

* Extracted business implications from the unified analytics pipeline

**5. Recommendation Framework**

* Formulated recommendations rooted in data findings

* Focused on inventory strategy, outlet performance optimization, and regional expansion

## Skills Demonstrated

**Tools Used Together in a Unified Workflow**
* SQL: Data cleaning, preprocessing, KPI extraction
* Python: Exploratory data analysis, statistical summaries, visual insights
* Power BI: Dashboarding, DAX KPIs, business storytelling

**Analytical Skills**
* Data Cleaning & Harmonization
* Exploratory Data Analysis (EDA)
* KPI Construction & Validation
* Category & Outlet Segmentation
* Q-Commerce Domain Understanding
* Insight Derivation & Business Strategy

## Results & Business Recommendations
**Key Results**

* Total Sales: $1.20M

* Average Sale: $141

* Total Items Sold: 8,523

* Average Rating: 3.92

**Low-Fat vs Regular:**

* Low-Fat items sold: significantly higher

* Low-Fat revenue nearly 2× Regular

**Major Insights**
1. Tier 3 Outlets Lead Revenue

* Tier 3 generates the highest revenue, outperforming Tier 1 & Tier 2.
Reason: Limited offline retail competition → higher dependency on quick commerce.
<img width="197" height="157" alt="image" src="https://github.com/user-attachments/assets/9c73a17b-a0fc-43bd-b774-006a0912df59" />


2. Essentials Drive Sales

Top categories:

* Fruits & Vegetables

* Snacks

* Household

* Frozen

* Dairy

These items replenish frequently → driving high-value baskets.

3. Medium-Sized Outlets Perform Best

* Medium outlets outperform both small and large stores.
Reason: Balanced SKU variety + lower operational overhead.
<img width="178" height="159" alt="image" src="https://github.com/user-attachments/assets/c55e10f0-ed32-4828-975c-59c70c2f77d3" />


4. Supermarket Type 1 Converts Best

* Despite low visibility, these outlets have the highest sales.
Grocery stores have high visibility but lower conversion.
<img width="386" height="142" alt="image" src="https://github.com/user-attachments/assets/e63749e7-1dae-4e2f-80ac-cd811b73dcf6" />


5. Customer Preference for Low-Fat

* Low-fat items dominate revenue and item count.
Reason: Health-conscious shift in consumer behavior.
<img width="144" height="143" alt="image" src="https://github.com/user-attachments/assets/a21da226-40a6-4d95-bc8f-ff18ff556d29" />


## Business Recommendations

**Bundle Strategy:**
Launch weekly/monthly grocery bundles for high-frequency categories.

**Tier 3 Expansion:**
Increase dark-store density and hyperlocal promotions in Tier 3.

**SKU Optimization:**
Expand low-fat, frozen, snacks, and daily essentials inventory.

**Outlet Optimization:**
Scale medium outlets as the default operating model.

**Subscriptions:**
Introduce auto-replenishment for dairy, fruits, and household goods.

**Visibility Improvement:**
Promote Supermarket Type 1 outlets within the app.

## Next Steps

* Build forecasting models for demand prediction

* Create customer segmentation based on basket value

* Add RFM analysis for retention insights

* Automate monthly performance dashboards

* Integrate real-time inventory alerts

* Explore seasonality patterns for category optimization


## Repository Structure

├── SQL/

│   └── blinkit_queries.sql

│

├── Python/

│   └── EDA.ipynb

│

├── PowerBI/

│   └── Blinkit_Dashboard.pbix

│

├── Data/

│   └── Blinkit_Raw.csv

│

└── README.md

## Dashboard Preview

<img width="912" height="513" alt="Dashboard" src="https://github.com/user-attachments/assets/063bf8f4-1df9-45d8-bd42-f874d3e3f101" />

## Contact 

Khushi Vadadoriya

📧 Email: vadadoriyakhushi18@gmail.com

🔗 LinkedIn: www.linkedin.com/in/khushi-vadadoriya-0977ba249
