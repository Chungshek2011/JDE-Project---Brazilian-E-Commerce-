# Brazilian E-Commerce Project in JDE by olist 
 Chung Shek 
 
# Dataset
This is a well known dataset available from [Kaggle](https://www.kaggle.com/olistbr/brazilian-ecommerce). The dataset has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allows viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers. The dataset was generously provided [Olist](https://olist.com/), the largest department store in Brazilian marketplaces. Olist connects small businesses from all over Brazil to channels without hassle and with a single contract. Those merchants are able to sell their products through the Olist Store and ship them directly to the customers using Olist logistics partners.

### Important notes about the data

- An order might have multiple items.
- Each item might be fulfilled by a distinct seller.
- All text identifying stores and partners where replaced by the names of Game of Thrones great houses.

### Schema

The full dataset is divided in 8 files: orders, *payments, reviews, items, products, sellers, customers, geolocation*. Descriptions of the columns can be found on the the Kaggle link above, or on the main script.

<img src="https://github.com/Chungshek2011/JDE-Project---Brazilian-E-Commerce-/blob/main/figure/dataset%20furgure.png" width="700" />

### KPI
1. Special Date Demand Analysis
Data Segmentation: Analyze sales data around key dates like Black Friday, Christmas, etc.
2. Intention to Pay in Installments
3. Lead Customers (Offline, Online, Industry)
4. Delivery Bottleneck Identification
5. Regional Purchasing Power Analysis

### General Overview 
For information, we have count total order haves 99,441 orders and it have 96,096 customers using olist in this 3 years.
<img src="https://github.com/Chungshek2011/JDE-Project---Brazilian-E-Commerce-/blob/main/figure/overview%2001.png" width="800" />

#### Speical Day 
The orders show a consistent rise throughout the years, however, a sharp increase in the 47th week in 2017 can be attributed to Black Friday, which coincides with the Nov 24th date and falls within that week. Customers are expected to have taken advantage of the discount sales which showed that orders were more than double the previous week and other weeks during 2017 and 19th week in 2018 is mother's day in barzil  mother's day is very important to celebrate beside that 31st  in 2018 is Independence day  its only barzil public holiday . 
<img src="https://github.com/Chungshek2011/JDE-Project---Brazilian-E-Commerce-/blob/main/figure/speical%20day.png" width="800" />

#### User Grow 
Olist  started 2017 with a bang - they saw an incredible 303% growth in users from Q1 2017 to Q1 2018. That's like a small café suddenly becoming the most popular spot in town! The monthly active users chart shows this  upward trend (marked with the red arrow I notice in the graph).

But then things took a rough turn. From Q1 to Q3 2018, they lost 39% of their users, followed by another 8% drop.

Currently, they're sitting at 12,645 total active  users, which is down by 8,122 users from their peak. The quarter-over-quarter change is showing that -39% decline, which is pretty significant.

What's particularly interesting is the pattern in the bar chart showing monthly active users. You can see those light blue bars climbing steadily through 2017, reaching a peak, and then gradually declining through 2018. The darker blue bars at the end represent repeat users, which seems to be holding somewhat steady despite the overall decline.
<img src="https://github.com/Chungshek2011/JDE-Project---Brazilian-E-Commerce-/blob/main/figure/user%20grow%20.png" width="800" />
