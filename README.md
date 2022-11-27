# Customer-Segmentation

# <b><u> Project Title : Extraction/identification of major topics & themes discussed in news articles. </u></b>

## <b> Problem Description </b>

### In this project, your task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

## <b> Data Description </b>

### <b>Attribute Information: </b>

* ### InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
* ### StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
* ### Description: Product (item) name. Nominal.
* ### Quantity: The quantities of each product (item) per transaction. Numeric.
* ### InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
* ### UnitPrice: Unit price. Numeric, Product price per unit in sterling.
* ### CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
* ### Country: Country name. Nominal, the name of the country where each customer resides.

![](https://miro.medium.com/max/720/1*NoFzCc5Piv9wP3QUbu71BA.webp)

# Conclusion

* This project mainly focused on developing customer segments for a UK based online store, selling unique all occasion gifts.

* Retention rate for all users is monotonically decreasing over time, while the retention rate for cohort dates from December 2010 to September 2011 is not monotonic in nature.

* Using a recency, frequency and monetary(RFM) analysis, the customers have been segmented into various clusters and got a silhoutte score of 0.39 for two clusters 

* By applying different clustering algorithm to our dataset, we get the optimal number of cluster is equal to 2.

* Since this is an unsupervised learning approach, there is no 100% correct answer, number of clusters will vary depending on the company's requirement.

* The business can focus on these different clusters and provide customer with services of each sector in a different way, which would not only benefit the customers but also the business at large. 
