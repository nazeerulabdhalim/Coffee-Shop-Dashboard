# Coffee-Shop-Dashboard (Jan - Jun 2023)
An interactive dashboard to explore and analyze coffee shop sales in New York using **Excel**

### Table of Contents
[Project Background](#project-background) | 
[Data Structure](#data-structure-overview) | 
[Executive Summary](#executive-summary) | 
[Insights](#deep-dive-insights) | 
[Recommendations](#recommendations)]

## **Project Background**
A coffe shop chain with three locations in New York; Astoria, Hell's Kitchen, and Lower Manhattan. The data is a transactional from Jan-Jun 2023 of the shop. The goal is to transform the data into an interactive dashboard _to identify patterns, trends and opportunities for the business_ using Microsoft Excel.

## **Data Structure Overview**

- **transaction_id:** Unique identifier for each transaction.
- **transaction_date:** Date of the transaction (MM/DD/YYYY format).
- **transaction_time:** Time of the transaction (HH:MM:SS format).
- **transaction_qty:** Quantity of items in the transaction.
- **store_id:** Unique identifier for each store.
- **store_location:** Store location name.
- **product_id:** Unique identifier for each product.
- **unit_price:** Price of a single unit of the product
- **product_category:** Broad category of the product
- **product_type:** Specific product type within the category
- **product_detail:** Detailed product description

Then we add a few extra columns covering the;
- **revenue:** the sales amount of each transactions.
- **month:** the month of the transaction happened in numeric (1, 2, etc.).
- **month name:** Text representation of the month (Jan, Feb, etc.).
- **day:** the day of the transaction happened in numeric (1, 2, etc.).
- **day of week:** Text abbreviation of the weekday (Mon, Tue, etc.).
- **hour:** the hour of the day of the transaction happened in 24-hours format.
  
## **Executive Summary**
![Overall](/Overall.png)
This dashboard provides dynamic insights into the coffee shop sales performance:<br/>
📦 Total Transactions: 149,116 <br/>
💰 Total Revenue: $699K <br/>
👥 Average Order Quantity per Customer: 1.44 <br/>
💵 Revenue per Customer: $4.69 <br/>

#### Additional key findings:
- Coffee (58,416), Tea (45,449), and Bakery (22,796) are the top three product categories, accounting for most transactions.
- Revenue growth is consistent month-over-month, with January starting at $81,678 and rising to $166,486 by June.
- Peak sales hours are 8am–11am, confirming strong morning demand.
- Monday through Friday transactions are relatively stable (~21K each), with a slight dip on weekends.
- Top products include Brewed Chai Tea ($77K), Gourmet Brewed Coffee ($70K), and Barista Espresso ($91K).

## **Deep Dive Insights**

### 📈 **Revenue & Trends**
- Strong upward trend in revenue from Feb to Jun (+118% increase).
- Growth suggests increasing customer engagement or expanded product adoption.

### 🏪 **Store Performance**
- Filters allow comparison, but combined insights show all stores share similar category dominance (Coffee, Tea, Bakery).
- Hell’s Kitchen likely benefits more from morning rush hour (offices & commuters).

### 🕒 **Time of Day Analysis**
- Peak transactions between 8am–11am reflect morning commuter and office worker routines.
- After 11am, sales decline significantly, indicating reliance on morning routines.

### 🥐 Product Category & Product-Level Insights
- Coffee dominates with ~39% of all transactions, followed by Tea and Bakery.
- Flavours, Coffee Beans, Loose Tea, Branded Items, and Packaged Chocolate are niche categories (<5% combined).
- Top 3 products (Brewed Chai Tea, Barista Espresso, Gourmet Brewed Coffee) generate nearly 35% of total revenue.
- Items like Sugar-Free Syrup ($2.3K) and Packaged Chocolate (487 transactions) underperform, raising questions of whether to discontinue or reposition.

## **Recommendations**

### 1. Strengthen Morning Rush Strategy
- Enhance promotions, bundle deals (e.g., coffee + pastry), and quick-service options between 7am–11am to maximize peak demand.

### 2. Expand Coffee & Tea Offerings
- Invest more in coffee innovation (seasonal brews, specialty lattes) since it drives majority revenue.
- Introduce premium tea blends to expand the already strong tea category.

### 3. Reposition or Rationalize Low-Performing Items
- Reassess niche categories like packaged chocolate and syrups. Consider discontinuing or repackaging them as add-ons in bundles.

### 4. Leverage Data-Driven Promotions
- Use weekday stability to run loyalty programs targeting repeat office-goers.
- Weekends show slightly lower engagement; targeted campaigns (family bundles, brunch promos) could lift weekend sales.

### 5. Inventory & Supply Chain Optimization
- Ensure sufficient stock of top 5 products (Brewed Chai Tea, Barista Espresso, Gourmet Brewed Coffee, Hot Chocolate, Brewed Black Tea).
- Reduce overstock on low-turnover items to cut holding costs.

### 6. Store-Specific Strategy
- Customize offerings per location: e.g., quick “grab-and-go” options in Hell’s Kitchen (commuters) vs. premium sit-down beverages in Lower Manhattan.
- Revise operating hours for each stores to tailor based on demands.

## Sanpshots
![Astoria](/Astoria.png)
![Hell's Kitchen](/Hells_Kitchen.png)
![Lower Manhattan](/Lower_Manhattan.png)
