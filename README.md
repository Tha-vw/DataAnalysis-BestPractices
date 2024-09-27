In this project, I examined informative details on a fictitious superstore called MegaMart Hub. They are composed of operational data using various features, however, the focus was on observing whether certain Sub-categories influence profits at MegaMart Hub.

I have used Python to develop some descriptive statistics and visualizations in order to gather insightful information about the data and, thus, answer objective and some hypotheses related to profit.
Furthermore, I preprocessed and cleaned the data, managed outliers, applied Label encoding to the categorical features, separated the data into Training and Test sets and, finally, did Normalization and Standardization techniques for training a Machine Learning Model in the future.

Let us assemble the proposed hypotheses:

* Is the profit higher during the end of the year seasonal period (November - December / Christmas)? In session 3.2.1 I confirmed profits are highest during that period.

* Is the profit lower during January and February, after the end of the year seasonal period? Yes, there was a significant drop in orders during that period, as observed in session 3.2.1.

* Has the discount applied on products had a positive impact on the profits? Although high discounts did increase sales, the analysis concluded the highest the discount, the lowest the profits.

* Can we say that higher sales translate into higher profit for MegaMart Hub? This can be seen in few periods throughout the years but the majority of the time, the profit would not grow as the sales grew.
If so, does profit grow at the same scale as sales? No, those variables did not follow the same trend.

Going back to the objective, the goal was to reflect on ***determining whether MegaMart Hub's profitability, both gains and losses, is driven by specific Sub-categories of the dataset.***

The sub-categories with the highest profits were **Copiers and Phones** and the ones with the lowest profits were **Tables and Bookcases**.

**Tables and Bookcases** show strong sales figures, which raise the issue of operational inefficiencies, such as poor inventory or storage management, or unexpected events like natural disasters leading to inventory loss or shifts in suppliers / vendors, which could have affected pricing and profitability, amongst other factors.

**Copiers** are topping the list of most profitable Sub-categories, however, it is not ranked well in the top-sellers. This might be due to the nature of the products in this sub-categories, which usually have longer durability and less of a need for replacements.
