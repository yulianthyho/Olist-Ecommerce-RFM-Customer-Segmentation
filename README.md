# 🛒🛒 Olist Ecommerce: Customer Segmentation with RFM Analysis and K-Means Clustering 
End to end process from Data Cleaning, Exploratory Data Analysis then do Customer Segmentation with RFM Analysis and K-Means Clustering and giving insight and recommendation for each cluster.

Tools : Python (Pandas, Matplotlib, Scikit-Learn, Numpy, Seaborn, Scipy, Silhoutte Analysis) using Google Collab

Check the code [here](https://github.com/yulianthyho/Olist-Ecommerce-RFM-Customer-Segmentation/blob/main/W6W7W8_Yulianthy_Ho_Intermediate_%26Advanced.ipynb)

## Overview
Olist just started an e-commerce startup based in Portugal that recently opened an online website to sell their product. Fortunately, Olist is launching their website when the covid-19 hits and making them grow faster than ever. However, Olist is still not using targeted marketing which hurts their marketing budget as only a fraction of their user comes back to their website.

## Objective
Help Olist to increase their marketing conversion rate by doing targeted marketing using customer segmentation so that it will not hurt their budget.

## Analysis
Customer segmentation is one of the most important marketing tools, because it can help a business to better understand its target audience. Segmenting customer helps in better understanding the customers and thus personalizing marketing and communication for each segment.

We will segment our customer using RFM analysis
- **Recency (R)** : Difference between days since last purchase and observed days.
- **Frequency (F)** : How many of transcaction each customer made?
- **Monetary (M)** : How much each customer spend ?

## Insight and Recommendation

There are 3 cluster of our customer, then we can naming them as :
1. **The Loyal One** 🧡🧡: customer with high spending and low recency

No need to doubt they are our favorite customers that we need to take good care of.
- Recommendation: Actually there is no need to overwhelmed them with vouchers/ promotions (this could saves us our money or marketing budget), but we can optimize or leverage some kind of loyalty point to keep them around. Loyalty programs can offers rewards, extra discount, or other special incentives.

2. **The Probably Churned** ❗❗: moderate spend, high recency

Our top priority is to get them transacting with us again after they have been churned for a while.
- Recommendations : To encourage them to transaction with us again, we could offer one or two large-benefit vouchers, while give them push notifications on email, etc.

3. **The Casual One** 😀 : low spend, moderate recency

We need to increase the monetary value or total spending of the customers in this category.
- Recommendations : We can increase total spending of customers by providing vouchers in the form of cashback (to enable repeat purchases), with a high eligibility threshold (e.g. the voucher is only valid for transactions amount at least 100).

