# E-commerce-project
Unveiling the Dynamics of Brazilian E-Commerce: A Comprehensive Analysis of Olist's Public Dataset

## Introduction:
The Brazilian E-Commerce Public Dataset by Olist, available on Kaggle, is a genuine and commercially published dataset provided by Olist, the largest department store in Brazilian marketplaces. Olist operates its own warehouses and has partnerships with small merchants for product shipping. They also offer logistics services to these merchants.

The dataset covers a period of 24 months, starting from September 2016 to October 2018. It consists of ten datasets, each containing 100,000 rows and 42 columns. These datasets provide valuable insights into various aspects of the e-commerce business, enabling researchers and analysts to delve into the dynamics of the Brazilian market.

For more comprehensive information about the dataset, you can refer to the Kaggle page: Brazilian E-Commerce Public Dataset by Olist | Kaggle Kaggle https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?select=olist_order_items_dataset.csv 

## Questions:
Mainly, the aim is to check the health and growth of the business. Therefore, the further questions have been asked.
1. How is the sales performance over the two years?
2. What are the best and worst sold product categories?
3. How is the delivery performance by the years?
4. Does product photo quantity and product description affect sales of that category?

## Methods:
### Used tools: Python, Pandas, jupyter notebook, visual studio code, Tableau, Github.
1. For EDA data cleaning was the first step. However, the data was super clean hence only droppping off some redundant columns and merging the datasets was the main task remained.
2. The datasets were merged as per the questions requirements. Then the created dataframes were converted into the new csv's to import into Tableau. One of the polots was created by pandas in Jupyter notebook.
3. The further visualizations were done in Tableau. For the better view of the results click on Link: https://public.tableau.com/views/q1_product_categories/q1_product_cate?:language=en-US&:display_count=n&:origin=viz_share_link 

## Results:
### Question1: Orders placed by customers within two years.
How the quarterly sales performance in the year 09/2016-10/2018
![q2_sell_quarterly](https://github.com/prache/E-commerce-project/assets/25516674/1b9bae8c-5e17-4cd7-ae29-d8d2a33130a2)
#### Inference:
1. The dataset showed that  in 2017, the business was blossoming until Christmas.
2. Then on from 2018 it started drooping heavily.


### Question2: Product category distribution. 
It shows the best sold categories of the products based on the sales.
![product category distribution](https://github.com/prache/E-commerce-project/assets/25516674/20a31717-5c8b-4296-9f16-c16f033242ff)

![q1_product_cate](https://github.com/prache/E-commerce-project/assets/25516674/9b4ed8a4-3e7e-4c6f-8f61-7c8bcc90c15a)
#### Inference: 
1. Best sold 3 product categories
Bed, Table, and Bath 
Health and Beauty
Sports and leisure
2. Worst sold 3 product categories:
Security and services
Diapers, Children fashion
CD’s,DVD’s, Music related things

### Question3: Delivery performance by sellers
Here are the average shipping days are calculated with the sellers code
![q3_delivery_performance](https://github.com/prache/E-commerce-project/assets/25516674/f5479755-ee89-4c6a-8bef-cce4bd32d4b8)

![q3_delivery_performance (2)](https://github.com/prache/E-commerce-project/assets/25516674/fd5c102e-c3ac-4ae9-a47b-f54aa6fc5d1b)

#### Inference:
1. More than 50% sellers have taken more than 10 days to deliver (Median is 11.2 days).
2. Average maximum days taken was up to 190 days. However, it was a single data point (an outlier).
3. Average minimum days taken to ship were 1.2 days.

### Question4: Comparing number of orders with prduct descriptopn length and photo quantity
Hereby, I am testing the attribution of product descrition length and photo quantity with the sales.
![q4_sells_photo_description](https://github.com/prache/E-commerce-project/assets/25516674/5b9a8545-0542-4fc4-a711-ca408bf09d93)

![q4_sells_photo_description (2)](https://github.com/prache/E-commerce-project/assets/25516674/828ef1b2-8c9e-4be4-b924-f16835325046)

#### Inference:
1. Purchase of the product by customers is in positive correlation with number of photos of that particular product category.
2. It is similar with product description.
3. When the product description is lengthy (in detail) then customers tend to  purchase the products more than the categories has less photos and description.

## Conclusion:
1. Olist has seen ups and downs in each quarter instead of steady growth. Sells has been reduced in 2018.
2. The product sell was higher in Christmas time in 2017. Customers have purchased more products which are house related. For example: bed, bath, tables, furniture, decore, housewares. Also, gifts, toys, perfumes, watches. 
3. The best selling categories are focused well and hence had success. Focus well meaning that multiple photos of the products and detailed description of it makes customers confident to buy.
4. On an average 11.2 days are needed for the delivery. 
5. Buyers has bought only once from the platform.

## Recommendations:
1. More focus is needed on the product categories which are not only seasonal but also needed on daily basis. For example: music, diapers, home appliances. Again focus meaning that publishing better quality and quantity product photos with detailed descriptions.
2. Monitor the sellers and investigate shipping delays. Ideally, tracking the shipping order aids clear the issues. Also, clear communication with sellers, couriers, and customers could resolve issues that may arise. Analysing geographic data will be insightful for route optimization.
3. Regular monitoring and analysing the customer reviews could be insightful. Building a trust and communication will bring performance up.  

