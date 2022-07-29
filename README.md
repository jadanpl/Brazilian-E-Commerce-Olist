## Problem Statement
E-commerce provides an easy way to sell products to a large customer base. To tailor marketing campaigns for the customers, e-commerce retailers need to know their customers well. One of the methods to know the customers is to perform customer segmentation. Customer segmentation could help the e-commerce retailers to know its customer base and find out which segment of customers it might be missing. Besides, customer segmentation could also help the e-commerce retailers to find out that the products that its customers are buying together. This may prompt the e-commerce retailers to bundle those product together as a combined offering, which may increase revenue for the retailer and make the buying process more streamlined for the customers.

## Objectives
* To determine customer satisfaction by creating wordclouds for the top & botttom 10 product categories (based on review scores).
* To determine a customer’s value by using the RFM model. It involves taking account of the recency, frequency, and the monetary value of the customers.
* To divide customer bases into different segments based on various customer attributes.
* To predict future sales with purchase date information.

## Dataset
Real-world datasets provided by <a href='https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?datasetId=55151&sortBy=voteCount&searchQuery=rfm'>Olist on Kaggle</a> that has information of orders from 2016 to 2018 made at multiple marketplaces in Brazil.
<img src='https://i.imgur.com/HRhd2Y0.png'>

## Findings
1. The customers and sellers of Olist are mainly distributed in the southeast and south of the Brazil.
2. More than 50% of the items is rated as 5. Based on the wordclouds that display the negative words, the reasons that led to low review scores could be low quality (wrong/ torn/ broken/ dirty/ missing) items, delayed delivery, and others.
3. Based on the visualization that displays the frequent locations (from the source city to destination city), the range for median of the freight values is between 2.32 and 3.29. From the heatmap plotted, the freight value is positively correlated with product weight and product volume.

## Recommendations
1.  Methods such as the Recurrent Neural Networks (LSTM) or Facebook's Prophet could be used to perform time series analysis on the sales data.
2.  Other unsupervised learing algorithm such as DBCAN or hierarchical clustering ould be used to perform customer segmentation.
