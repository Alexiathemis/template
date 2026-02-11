

# Project Background

## Project Background — PizzaMia Pizza Sales Analysis

PizzaMia Pizza, established in recent years, is a fast-casual pizza restaurant that serves a wide variety of pizzas across multiple categories through dine-in, takeout, and online ordering channels.

The restaurant has accumulated a substantial amount of transactional data capturing customer orders, pizza types, sizes, pricing, and order timing. However, this data has been largely underutilized beyond basic reporting. This project analyzes and synthesizes the available pizza sales dataset to uncover actionable insights that can improve operational efficiency, menu strategy, and overall revenue performance.

Using detailed order-level and product-level data — including order dates and times, pizza categories, sizes, quantities, and prices — the analysis aims to better understand customer purchasing behavior and sales patterns.

---

##  My Key Focus Areas

### Sales Trends Analysis
Evaluation of sales patterns over a year, examining weekly and daily trends with a focus on total revenue, number of orders, and average order value per day, as well as identifying which times of the day generate the highest-value orders. This analysis helps highlight peak periods and seasonal trends in customer demand.

### Menu & Pizza Performance
An analysis of pizza performance across categories, sizes, and individual pizza types to understand how each product impacts total sales and revenue. This section highlights top-performing pizzas, identifies underperforming menu items, and surfaces opportunities for menu optimization through pricing, promotions, or product selection.

### Quantity & Size Distribution:
This section summarizes order composition by calculating the average number of pizzas per order and analyzing the distribution of pizza sizes purchased. The goal is to understand typical basket size and how customer preferences vary by size.

### Revenue Analysis:
This section breaks down revenue contribution by pizza type to show which items drive the largest share of sales. It identifies the top revenue-generating pizza and the lowest revenue-generating pizza to support menu optimization decisions.
---

The tableau Dashboard can be found here. [VIEW DASHBOARD HERE] (https://public.tableau.com/app/profile/alexia.themistocleous/viz/PizzaBusinessinsights/DashboardVc)

The SQL queries used to inspect and clean the data for this analysis can be found here [link].


# Data Structure & Initial Checks

## Database Diagram




# Executive Summary

### Overview of Findings

Pizza Mia generated strong performance with $817.9K in revenue from 21.3K orders, driven primarily by chicken-based pizzas and large sizes, which dominate both sales volume and revenue. July was the peak month, while October lagged, indicating clear seasonality that can be leveraged for targeted promotions. Conversely, XL/XXL sizes and niche pizzas (e.g., Brie Carre) underperformed, suggesting an opportunity to streamline the menu or rethink pricing and positioning for low-demand items.

[Visualization, including a graph of overall trends or snapshot of a dashboard]



# Pizza Sales Insights

### Sales Trends  
The company generated a total revenue of $817,860 from 21,350 orders, selling 49,574 pizzas during the year, with an average order value of $38.31 and an average of 2.3 pizzas per order. Revenue peaked in July at $72,558, while October recorded the lowest revenue at $64,028, indicating moderate seasonality with stronger performance during mid-year months.  

Weekly sales patterns show that Fridays are the busiest day, generating the highest number of orders (3,538), followed closely by Thursdays and Saturdays, while Sundays are the slowest day (2,624 orders). Hourly analysis reveals clear demand spikes during lunch (12–1 PM) and dinner hours (5–7 PM), while traffic remains consistently low between 9–11 AM and declines after 9 PM, suggesting opportunities to optimize staffing and operating hours.  

### Menu & Pizza Performance  
Sales are strongly driven by the Chicken category, which contains the top revenue-generating pizzas. The Thai Chicken Pizza ($43,434), Barbecue Chicken Pizza ($42,768), and California Chicken Pizza ($41,410) lead in revenue contribution, making chicken-based pizzas the most valuable segment of the menu.  

In terms of order volume, the Classic Deluxe Pizza is the most frequently ordered item (2,416 orders), showing that it is a strong volume driver, even if it does not generate the highest revenue overall. On the other hand, the Brie Carre Pizza is the weakest performer, contributing only $11,588 in revenue and 480 orders, making it the poorest-performing menu item and a potential candidate for menu optimization or removal.  

### Quantity & Size Distribution  
Customers typically order more than one pizza per transaction, averaging 2.3 pizzas per order, indicating that purchases are often made for families or groups. The Large (L) size is the most preferred, with 18,956 pizzas sold, followed by Medium (15,635) and Small (14,403).  

In contrast, XL (552 sales) and XXL (28 sales) sizes show extremely low demand. Notably, XXL is only available for the Greek pizza, which may limit its performance. The sharp drop-off in demand beyond Large size suggests customers perceive Large as offering the best value for money.  

### Revenue Analysis  
Revenue contribution is concentrated among a small group of high-performing pizzas, particularly premium chicken varieties. While the Classic Deluxe leads in quantity sold, higher-priced pizzas like Thai Chicken generate greater revenue, indicating that pricing plays a significant role in total revenue contribution.  

The business appears more volume-driven than price-driven, as stable average order value suggests revenue growth is largely influenced by order frequency rather than significant price changes. Small increases in average order value—through bundles, add-ons, or upsizing strategies—could significantly increase annual revenue without requiring additional customer traffic.  




# Recommendations:

Based on the insights and findings above, we would recommend the [stakeholder team] to consider the following: 

* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  


# Assumptions and Caveats:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

* Assumption 1 (ex: missing country records were for customers based in the US, and were re-coded to be US citizens)
  
* Assumption 1 (ex: data for December 2021 was missing - this was imputed using a combination of historical trends and December 2020 data)
  
* Assumption 1 (ex: because 3% of the refund date column contained non-sensical dates, these were excluded from the analysis)
