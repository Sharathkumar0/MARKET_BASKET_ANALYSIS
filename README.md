# MARKET_BASKET_ANALYSIS / ASSOCIATION RULES: 
It allows retailers to identify the relationship between items which are more  frequently bought together.

**Association Rule Mining:**

It is used when you want to find an association between different objects in a set, find frequent patterns in a transaction database. The most common approach to find these patterns are **Market Basket Analysis.**

**Strategies may include:**

1 Changing the store layout according to trends

2 Customer behaviour analysis

3 Catalog design

**Difference between Association and Recommendation:**

Association rule do not extract the individual preferences rather find relationship between sets of elements of every distinct transaction. This is what makes them different than collaborative filtering which is use in recommendation systems.

**Key metrics for association rules:**

1 Support: Percentage of order that contains the item set

2 Confidence: Antecedent and consequent, Confidence measure the percentage of times that item 'Consequent' is purchased given that item 'Antecedent' was purchased.

3 Lift: Unlike the confidence metric whose value may vary depending on direction (Eg: Confidence (A -> C) may be differennt from confidence (C -> A). Lift has no direction. This means that the lift (A,C) is always equal to the lift(C,A).


**Association rule based algorithm are viewed as two step approach:**

1 Frequent Itemset Generation: Find all frequent item sets with support >= Pre determined min_support count.

2 Rule Generation: List of all association rule from frequent item-set calculate support and confidence for all rules.










