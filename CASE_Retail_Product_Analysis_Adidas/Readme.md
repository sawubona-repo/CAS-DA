# Retail Product Analysis - Adidas US  
A Dataset for those interested in Fashion, Style, and Retail

![image](https://github.com/sawubona-gmbh/CAS-DA/assets/52699611/9f4521a6-adb5-412e-80c2-2098c0dfadc0)

---  
#### 25.05.20234 v1 dbe - initial version for CAS DA6
---  

This Adidas fashion dataset provides rich product information for over 1500+ Adidas products available for purchase in the United States. 
It contains detailed information on product selling price, original price in multiple currencies ( USD / EUR / GBP ), product availability ( in stock / out of stock ), color , Category ( such as Apparel / Footwear ), source website , breadcrumbs , product description , brand name , link to product images , Country of origin and language . 
The average rating and reviews count are also included in the dataset so that researchers can study the correlation between them.

### File Descriptions  
+ adidas.csv  

### Data Fields   
+ url: The URL of the product page on the source website. (String)
+ url: The URL of the product page on the source website. (String)
+ name: The name of the product. (String)
+ sku: The SKU or unique identifier for the product. (String)
+ selling_price: The selling price of the product in USD or Euros. (Float)
+ original_price: The original price of the product in USD or Euros. (Float)
+ currency: The currency type for the selling price and original price. (String)
+ availability: The availability of the product. (String)
+ color: The color of the product. (String)
+ category: The category of the product. (String)
+ source_website: The source website from where the data was collected. (String)
+ breadcrumbs: The breadcrumbs or path to the product page on the source website. (String)
+ description: A brief description of the product provided by Adidas. (String)
+ brand: The brand of the product. (String)
+ images: Multiple product images provided by Adidas. (String)
+ country: The country of origin/destination for the product. (String)
+ language: The language in which the product page was displayed on the source website. (String)
+ average_rating: The average customer rating out of 5 stars. (Float)
+ reviews_count: The number of customer reviews for the product. (Integer)
+ crawled_at: The date and time when the data was collected. (String)


---   
### Mögliche Aufgaben/Fragestellungen für die QS3 Fall Studie    
+ Explorative Analyse des Dataset (Top 10, Bottom 10, Median/Mittelwerte, Häufigkeiten, Korrelationen etc.)
+ Clustering/Segmentierung der Produkte nach verschiedenen Faktoren   
+ weitere explorative und visuelle Analysen mit Blick auf mögliche Erkenntnisse/Insights


> *WORK IN PROGRESS - Research Ideas*   
> This dataset can be used to determine which colors are most popular among different age groups or genders   
> This dataset can be used to identify the most popular products among different countries or regions    
> This dataset can be used to analyze the correlation between product reviews and ratings to determine which factors are most important to customers
