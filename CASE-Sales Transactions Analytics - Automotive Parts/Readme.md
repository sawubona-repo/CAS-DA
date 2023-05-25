# Sales Transactions Analytics  
### Automotive Parts
---  
#### 25.05.20234 v1 dbe - initial version for CAS DA6
---  
> “Give a girl the right shoes, and she can conquer the world.” — Marilyn Monroe  

Using Pricing Data to Uncover Brand Value. The data set contains information on **10,000 shoes** spread across **110 brands** and is provided originally as product information by [Datafiniti's Product Database](https://www.datafiniti.co/data/product-data#explore-use-cases).  

### File Descriptions  
+ Womens_Shoes_062019 - Datafiniti product data extract  

### Data Fields   
The dataset includes shoe name, brand, price, and more.  
Each shoe will have an entry for each price found for it and some shoes may have multiple entries.

+ id
+ dateAdded
+ dateUpdated
+ asins
+ brand
+ categories
+ primaryCategories
+ colors,dimension
+ ean / upc
+ imageURLs
+ keys
+ manufacturer
+ manufacturerNumber
+ name
+ prices.amountMax
+ prices.amountMin
+ prices.availability
+ prices.color
+ prices.condition
+ prices.currency
+ prices.dateAdded
+ prices.dateSeen
+ prices.isSale
+ prices.merchant
+ prices.offer
+ prices.returnPolicy
+ prices.shipping
+ prices.size
+ prices.sourceURLs
+ sizes
+ sourceURLs


---   
### Mögliche Aufgaben/Fragestellungen für die QS3 Fall Studie    
+ Explorative Analyse des Dataset 
+ Clustering/Segmentierung von Produkten nach allen Merkmalen oder eine spezifischen Gruppe von Merkmalen
+ weitere explorative und visuelle Analysen mit Blick auf mögliche Erkenntnisse/Insights 

Hinweis: Um die Stabilität von Ergebnissen zu gewährleisten, sollten Sie bspw. nur Marken mit mindestens 15 aufgelisteten Produkten berücksichtigen, was ausreichen sollte, um eine faire Vorstellung von deren allgemeinen Preisen zu erhalten.
Für jeden Schuh gibt es bspw. zwei Spalten in den Daten, die Aufschluss über den Preis geben: den **Mindestpreis** und den **Höchstpreis** des Schuhs. In einem ersten Schritt könnten Sie sich z.Bsp. auf diese beiden Preisspalten konzentrieren, zusammen mit zwei anderen Hauptmerkmalen, wie etwa **Marke** und **Farbe**. Das bedeutet, dass Sie sehen werden, wie etwa die Preise zwischen den verschiedenen Marken und den verschiedenen Farben variieren.

*WORK IN PROGRESS*    
You can use this data to determine brand markups, pricing strategies, and trends for luxury shoes. E.g.:

What is the average price of each distinct brand listed?
Which brands have the highest prices?
Which ones have the widest distribution of prices?
Is there a typical price distribution (e.g., normal) across brands or within specific brands?
Correlate specific product features with changes in price.
