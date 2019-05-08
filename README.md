# NLP-Boba-Tea-Shop-Reviews

Project Goal

Focusing on starting a boba shop in the US, in order to meet our customers' preferences:
- We want to create the best product portfolio and identify important features for each product
- We want to find out what kind of environments and services we can provide for our customers 


Dataset
 
The dataset is from Yelp’s 2019 Data Challenge. Source: https://www.yelp.com/dataset/download 
In this project, we focus on boba shops across the US. This data includes the reviews and the ratings that various boba shops got from this platform.


Methodologies

We separate the reviews into good and bad reviews based on ratings.
- The reviews with more than 4 stars are good reviews.
- The reviews with less than 2 stars are bad reviews.

We calculate TF-IDF scores for those reviews to build up the product portfolio:
- Calculate TF-IDF scores and find out the important phrases for both good and bad reviews separately.
- But the results turn out to be very similar, we assume that the product names with high TF-IDF scores are the popular products among customers (because those products are highly mentioned and also important in both good and bad reviews).
 
Next, we calculate TF-IDF for each product's reviews to identify important features for each product:
- Calculate TF-IDF scores for both good and bad reviews of each product in order to find out what features make people like or dislike this product.

We also find out the environments and services which can meet customers' expectations:
- Calculate TF-IDF for reviews (without the product names in our product portfolio) by adding stopwords such as "Boba" or "Tea" etc.

Therefore, we can not only know how to serve our products in the best way for our customers but also know what environments and services our customers prefer.


Project Insights

According to our analysis, we include eight items in our product portfolio. For each product, we also find out what features we can add to make our product more attractive.
Regarding the non-product features, we also find out some insights for our boba shop.
Those results are all included in our presentation slides.
