# personal_project_1
This project contains 3 parts. 

1. Using various data files from USDA website to predict the price group of fruit products.
2. Examine the difference of pricing between fresh and processed fruit by year.
3. Examine the difference of fruit pricing between different fruit types by year. 

Part I is a complete project by itself. In part I, we gathered pricing data for various fruit products from USDA website, cleaned it, and combined all the data into the final dataset. We then explored the data and obtained some insights by using data visualization. In the other, we performed data prediction using machine learning algorithms including multinomial regression, SVM, Naive Bayes, K-nearest neighbors, and decision tree. 

Part II and III are derived from Part I. The price for part I is an overall averaged market price across United States. We were wondering about the pricing differences between fresh and processed fruit, as well as the differences between different fruits. Therefore, additional data were found on the USDA website for these two parts. Unlike Part I where each file contains data for one particular fruit, the data for part II and III are grouped by fruit categories: melons, citrus, noncitrus, and berries. Instead of market price, the price in these two parts are grower prices. Each of the files contain many worksheets for different fruits, and some contain information that we do not consider in this project. Therefore, data cleaning is even more troublesome than Part I. On top of that, some fruits contain data from multiple states, so the average of the averages were calculated. 
