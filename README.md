

# Project Background

## Project Background — PizzaMia Pizza Sales Analysis

PizzaMia Pizza, established in recent years, is a fast-casual pizza restaurant that serves a wide variety of pizzas across multiple categories through dine-in, takeout, and online ordering channels.

The restaurant has accumulated a substantial amount of transactional data capturing customer orders, pizza types, sizes, pricing, and order timing. However, this data has been largely underutilized beyond basic reporting. This project analyzes and synthesizes the available pizza sales dataset to uncover actionable insights that can improve operational efficiency, menu strategy, and overall revenue performance.

Using detailed order-level and product-level data; including order dates and times, pizza categories, sizes, quantities, and prices  the analysis aims to better understand customer purchasing behavior and sales patterns.

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

<img width="713" height="238" alt="Screenshot 2026-02-19 at 11 03 38 AM" src="https://github.com/user-attachments/assets/f1076712-424e-4353-878d-aa7d5daa0200" />


Weekly sales patterns show that Fridays are the busiest day, generating the highest number of orders (3,538), followed closely by Thursdays and Saturdays, while Sundays are the slowest day (2,624 orders). Hourly analysis reveals clear demand spikes during lunch (12–1 PM) and dinner hours (5–7 PM), while traffic remains consistently low between 9–11 AM and declines after 9 PM, suggesting opportunities to optimize staffing and operating hours.  

<img width="718" height="299" alt="Screenshot 2026-02-19 at 11 01 14 AM" src="https://github.com/user-attachments/assets/d5901e33-bcee-404e-8a97-11cb82d02df9" />

### Menu & Pizza Performance  
Sales are strongly driven by the Chicken category, which contains the top revenue-generating pizzas. The Thai Chicken Pizza ($43,434), Barbecue Chicken Pizza ($42,768), and California Chicken Pizza ($41,410) lead in revenue contribution, making chicken-based pizzas the most valuable segment of the menu.  

In terms of order volume, the Classic Deluxe Pizza is the most frequently ordered item (2,416 orders), showing that it is a strong volume driver, even if it does not generate the highest revenue overall. On the other hand, the Brie Carre Pizza is the weakest performer, contributing only $11,588 in revenue and 480 orders, making it the poorest-performing menu item and a potential candidate for menu optimization or removal.  

<img width="667" height="379" alt="Screenshot 2026-02-19 at 10 56 11 AM" src="https://github.com/user-attachments/assets/c5ac1d78-d32f-4dc6-a1f1-b389ab79b1b0" />


### Quantity & Size Distribution  
Customers typically order more than one pizza per transaction, averaging 2.3 pizzas per order, indicating that purchases are often made for families or groups. The Large (L) size is the most preferred, with 18,956 pizzas sold, followed by Medium (15,635) and Small (14,403).  

In contrast, XL (552 sales) and XXL (28 sales) sizes show extremely low demand. Notably, XXL is only available for the Greek pizza, which may limit its performance. The sharp drop-off in demand beyond Large size suggests customers perceive Large as offering the best value for money.  

### Revenue Analysis  
Revenue contribution is concentrated among a small group of high-performing pizzas, particularly premium chicken varieties. While the Classic Deluxe leads in quantity sold, higher-priced pizzas like Thai Chicken generate greater revenue, indicating that pricing plays a significant role in total revenue contribution.  



The business appears more volume-driven than price-driven, as stable average order value suggests revenue growth is largely influenced by order frequency rather than significant price changes. Small increases in average order value—through bundles, add-ons, or upsizing strategies—could significantly increase annual revenue without requiring additional customer traffic.  



### Recommendations

Based on the insights and findings above, we would recommend the stakeholder team to consider the following:

Fridays and peak meal hours (12–1 PM and 5–7 PM) generate the highest order volume, while mornings (9–11 AM) and late evenings show consistently low traffic. The team should optimize staffing schedules around peak demand periods and consider introducing targeted promotions or limited-time offers during slow hours to better balance daily sales performance.

Chicken-based pizzas contribute the highest share of revenue, with Thai Chicken, Barbecue Chicken, and California Chicken leading performance. The team should prioritize marketing and promotional campaigns around high-performing chicken varieties and consider expanding similar flavor profiles to capitalize on strong customer preference.

The Classic Deluxe Pizza drives the highest order volume but does not generate the highest revenue, while premium pizzas generate stronger revenue per order. The team should implement upselling strategies, such as combo deals or premium topping add-ons, to increase the average order value of high-volume items.

XL and XXL sizes show extremely low demand, with XXL limited to only one pizza type and generating minimal sales. The team should reassess the pricing structure and size availability strategy, either by adjusting the price gap between Large and XL sizes or simplifying the menu by removing underperforming size options.

Revenue is concentrated among a small group of top-performing pizzas, while items like Brie Carre contribute minimal revenue and order volume. The team should evaluate underperforming menu items for repositioning, repricing, or removal to streamline operations and focus on high-margin, high-demand products.
  

# Assumptions and Caveats:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

Assumption 1: This analysis is based on a fictional company and dataset, so the results are intended for analytical demonstration rather than real-world business forecasting.

Assumption 2: Historical comparison is limited because prior-year data is unavailable, so trends and seasonality are interpreted only within the single year provided.

Assumption 3: Revenue figures are assumed to reflect final sales values; if discounts, promotions, coupons, taxes, delivery fees, or refunds are not captured in the dataset, total revenue and average order value may be overstated or understated.

Assumption 4: Time-based insights (hourly peaks and day-of-week trends) assume timestamps are accurate and consistently recorded; if orders span multiple time zones, or if timestamps reflect entry time rather than purchase time, peak-hour conclusions may be skewed.

Assumption 5: Menu performance conclusions assume pizzas were consistently categorized (e.g., “Chicken,” “Classic,” etc.); if product names or categories changed over time or were entered inconsistently, some items may be misclassified.

Assumption 6: Size distribution analysis assumes each “pizza sold” is one unit and that units are comparable across sizes; this does not account for differences in serving size, margins, or ingredient cost, so profitability may differ from sales volume patterns.

Assumption 7: The dataset does not include customer-level attributes (e.g., new vs returning customers, location, delivery vs dine-in), so the analysis cannot explain why certain trends occur—only what patterns exist.

Assumption 8: The analysis focuses on sales and revenue, but does not account for cost or margin; therefore, “top revenue” pizzas may not be the most profitable items.
