# -Online-Retail-Customer-Segmentation
Unsupervised Machine Learning Algorithm
###**Bussiness Problem -**

In this project, your task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

**Data Description -**
* InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
* StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
* Description: Product (item) name.
* Quantity: The quantities of each product (item) per transaction. Numeric.
* InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
* UnitPrice: Unit price. Numeric, Product price per unit.
* CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
* Country: Country name. Nominal, the name of the country where each customer resides.

###**Steps performed -**
*Importing the libraries
* Exploratory Data Analysis - EDA
* splitting of the data :-
* RFM (Recency, Frequency, and Monetary) dataframe helps in solving problems in a particular order, making it easy to recommend and display new products to selected customers.
###**Modelling -**

* K-Means with Silhouette_score

* K-Means with Elbow Method

* Hierarchical Clustering

* DBSCAN

###**Conclusion**
* The majority of customers, at 88.92%, are from the United Kingdom. Other significant customer groups include Germany (2.30%), France (2.12%), Eire (1.84%), and Spain (0.63%). The remaining customers come from countries such as the Netherlands, Belgium, Switzerland, Portugal, and Australia.


* The top five products purchased based on frequency were White Hanging Heart, T-Light Holder, Regency Cakestand 3 Tier, Jumbo Bag Red Retrospot, Party Bunting, and Assorted Colour Bird Ornament.


* A large number of orders, 35.86%, were cancelled.If we analyze these cancelled orders it could help us to prevent cancellations in the future and most number of cancellation has been done from UK
 
* On average, each customer places 5 orders.
 
* We can see that most number orders placed by United Kingdom(349227) which is one sided as compared to other countries.


* We can conclude that not only does the UK generate the highest sales revenues, but it also has the most customers. By exploring this further, we can gain insight into what products customers purchase together, as well as potential future opportunities in the UK market.

* The majority of purchases are made on Thursday and Wednesday, indicating customers prefer shopping during the weekdays

* The majority of purchases are made in November and October, indicating customers prefer shopping during the fall months.

* The majority of transactions are made between 11AM to 3PM, indicating customers prefer to shop during the afternoon.

* The majority of transactions are done during the afternoon, followed by the morning, indicating customers prefer to shop during the afternoon.
