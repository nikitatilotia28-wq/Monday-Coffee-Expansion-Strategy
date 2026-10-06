# Monday-Coffee-Expansion-Strategy : Data-Driven Store Location Analysis


### Project Overview
Monday Coffee has operated as an online-first D2C brand since January 2023. To accelerate brick-and-mortar D2C retail expansion, this project leverages relational database analytics (PostgreSQL/MySQL) to evaluate consumer demand, revenue density, overhead exposure, and customer acquisition efficiency across major Indian metropolitan areas.

### Executive Summary & Strategic Objectives
1) Primary Objective: Identify top 3 expansion target markets for high-ROI brick-and-mortar store launches using multi-variable SQL analytics.

2) Key Performance Indicators (KPIs): Market Penetration Rate, Average Revenue Per User (ARPU), Estimated Rent-to-Customer Overhead Ratio, Month-over-Month (MoM) Sales Growth Rate, and Total Addressable Market (TAM).

3) Data Infrastructure: Relational schema comprising city, customers, products, and sales relational entities with relational join optimizations, window functions, CTEs, and aggregated subqueries.

### Technical Problem Statement
Retail expansion presents capital allocation risks regarding real estate overhead vs. local market traction. This analysis addresses key strategic questions:

1) Total Addressable Market (TAM): What is the estimated coffee-consuming population per city based on a 25% regional penetration benchmark?

2) Revenue Distribution & Quarterly Performance: Which cities generated peak revenue during Q4 2023?

3) Product Mix & Volume Drivers: What are the top-performing SKUs by sales volume across urban clusters?

4) Unit Economics & ARPU: What is the average spend per unique active customer across target locations?

5) Overhead Efficiency Analysis: How does estimated commercial real estate rent compare to customer volume on a per-capita basis?

6) Growth Velocity: What is the Month-over-Month (MoM) revenue trajectory across core regional markets?

### High-Impact Key Findings & Recommendations
Strategic Expansion Priority Matrix
       High ARPU / Low Rent Overhead  ──►  [ PUNE ] (Top Priority)
       High Volume / High TAM Benchmark ──► [ DELHI ] (Volume Engine)
       Low Rent / High Penetration    ──►  [ JAIPUR ] (Cost-Efficient Scale)
       
### Top 3 Recommended Cities for Store Launch
1. Pune — Core Profitability Leader
Highest Revenue Generation: Peak total revenue driven by high Average Revenue Per User (ARPU).

Favorable Overhead Efficiency: Low estimated rent per customer, maximizing store-level EBITDA margins.

Strategic Fit: High readiness for premium D2C physical storefront locations.

2. Delhi — Scalable Market Volume Engine
Massive Addressable Market: Largest regional TAM at 7.7M estimated coffee consumers.

Broad Customer Base: Active customer count reached 68 unique buyers.

Manageable Overhead: Estimated rent per customer capped at ₹330 (well below the ₹500 risk threshold).

3. Jaipur — Low-Cost Acquisition Scaler
Peak Customer Penetration: Highest overall active buyer volume at 69 unique customers.

Exceptional Overhead Margin: Lowest rent per customer at ₹156.

Solid Monetization: Strong unit economics with ARPU at ₹11.6k.
