# Market-Basket-Analysis-Report
Objective 
The purpose of this analysis is to examine customer purchasing behavior by identifying combinations of products that are frequently bought together. These insights help businesses improve decision making regarding promotions, store layout, and inventory control.
2.	Methodology

a.	Data Collection 
Collected transactional data from a retail store. Each transaction contains a list of items purchased together by a customer.
Example Transaction Data :
Transaction ID  Items Purchased 
001	Bread, Milk, Butter
002	Shampoo, Conditioner
003	Bread, Butter
004	Milk, Eggs, Bread

b.	Data Processing 
Converted transaction data into a format suitable for analysis (basket format).
 Applied Apriori Algorithm (or FPP-Growth) to find frequent itemsets. Generated association rules with metrics :
-	Support – frequency of item combinations.
-	Confidence – likelihood of purchasing item B if item Ais bought 
-	Lift – strength of the association.
3.	Key Findings 

a.	Frequent Purchase Patterns
Itemset	Support
Bread &Butter	30%
Milk & Bread  25%
Shampoo & Conditioner	18%

b.	Association Rules (Hidden Relationships)
Rule   Confidence  Lift 
If Bread – then Butter  75%	1.5
If Shampoo – then Conditioner  85%	2.1
If Milk – then Bread  70%	1.3
Insights : 
-	Customers buying Shampoo are very likely to buy Conditioner.
-	Milk and Bread show moderate cross-affinity, suggesting joint promotion.

c.	Customer Segments & Preferences 
Segmenting data by customer type or demographics showed :
-	Students tend to buy ready-to-eat meals, snacks, and drinks.
-	Families purchase household staples together (e.g., Rice, Oil, Detergent)
-	Health – conscious customers buy combinations like Yogurt, Muesli, and  Fruit.
4.	Business Strategy Recommendations

a.	Product Plcement 
-	Place Butter near Bread and Conditioner near Shampoo to encourage cross – selling.
-	Create combo zones in- store (e.g., Milk + Bread + Eggs).

b.	Promotions
-	Launch “ Buy 1 Shampoo, Get 50% Off Conditioner” campaign.
-	Bundle Snacks + Soft Drinks for student discounts.

c.	Inventory Management 
-	Monitor stock levels of frequently bought – together products to avoid out-of-stock issues.
-	Stock high-lift products in more accessible locations.

d.	Targeted Marketing 
-	Send personalized offers based on previous purchases (e.g., offer Yogurt to customers who frequently buy healthy products).

5.	Conclusion
Market Basket Analysis provides valuable insights into consumer behavior. By identifying frequently bought-together items and customer buying patterns, businesses can make smarter decisions in promotion, product placement, and stock management, ultimately boosting sales and customer satisfaction
