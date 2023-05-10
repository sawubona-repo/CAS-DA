# Customer Segmentation I
### eCommerce Database Content
---  
#### 08.05.20234 v1 dbe - initial version for CAS DA6
---  

This notebook aims at analyzing the content of an E-commerce database that lists purchases made by **4000 customers**
over a period of one year (**from 2010/12/01 to 2011/12/09**). 

Based on this analysis, I develop a model that allows to anticipate the purchases that will be made by a new customer, during the following year and this, from its first purchase.

### File Descriptions  
+ eCommerce.csv - eCommerce database extract  



### Data Fields   
The data set contains 8 features  

+ InvoiceNo
+ StockCode
+ Description
+ Quantity
+ InvoiceDate
+ UnitPrice
+ CustomerID
+ Country



---   
### Mögliche Aufgaben/Fragestellungen für die M3 Fall Studie    
+ Explorative Analyse des Dataset (Top 10, Bottom 10, Median/Mittelwerte, Häufigkeiten, Korrelationen etc.)
+ Clustering/Segmentierung von Ländern nach Merkmalen
+ Zeitreihen - Entwicklungen zwischen 2015 und 2022
+ xxx  

1. Data Preparation

2. Exploring the content of variables

2.1 Countries
2.2 Customers and products
2.2.1 Cancelling orders
2.2.2 StockCode
2.2.3 Basket price
3. Insight on product categories

3.1 Product description
3.2 Defining product categories
3.2.1 Data encoding
3.2.2 Clusters of products
3.2.3 Characterizing the content of clusters
4. Customer categories

4.1 Formating data
4.1.1 Grouping products
4.1.2 Time spliting of the dataset
4.1.3 Grouping orders
4.2 Creating customer categories
4.2.1 Data enconding
4.2.2 Creating categories

