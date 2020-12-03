# Anyone Can Become a Sommelier
***
**AM10: Data Visualization and Story Telling | Group Project | Study Group 13**

_Grüner Veltliner, Rioja, Bourgeuil, or Cabernet Sauvignon?_

On average, six out of ten Brits wish they knew more about wine, with over half so overwhelmed by their lack of knowledge that they leave wine-related decisions to someone else. However, this doesn't have to be the case especially when you're out on a date. 

The [Data Set](https://www.kaggle.com/zynicide/wine-reviews) we are investigating was originally scraped from [WineEnthusiast](https://www.winemag.com/?s=&drink_type=wine) in November, 2017. We analyse information on 129,971 reviews (score points) on 708 varieties of wine as well as their prices and origin (country and winery) to answer the following questions:
**(1) What makes a wine good?** 
**(2) What makes a wine pricey?**
**(3) Is a more expensive wine necessarily a better wine?** 
Therefore, we attempt to identify the factors which contribute to a wine being good and/or expensive, assess whether there exists a strong correlation between the two, and how we can predict either of price and points for a bottle of wine.

> This data offers some great opportunities to improve our understanding of wines, or at least give us enough "knowledge" to order one which is good-quality and a bang for the buck. 

To achieve the aforementioned objectives and make further visualizations more meaningful we first inspect, clean and explore (ICE) the data. This includes getting rid of unnecessary columns, duplicate values, and checking for errors and outliers through boxplots. Further, we resolve the missing values in `country` and `variety` by matching information on wines from the same wineries and extracting information from the corresponding `description` wherever possible. In addition, the description (though complex to clean) gives a lot of insights on the region-specific characteristics of wines. For example, French wines are most frequently associated with words such as rich, crisp, acid, fruit, ripe, fresh, etc.

Next, we examine the distribution of prices and scores across parameters like geographical location and find out that:
- Our dataset is majorly dominated by reviews of wines from the US
- Wines from England have the highest average rating
- Wines from Germany and Austria are the safest bet as their median scores are fairly high

**Regression Models:**
For regression analysis, we decided to stick to the data pertaining to top 5 countries with wine reviews i.e. US, France, Italy, Spain and Portugal, and limit the price threshold to **$156.** By comparing model performance in terms of adjusted R-squared across multiple models, we were able to identify the best-ones to predict `price` and `rating` -

> rating = a + b(1)log(price) + b(i)country(i) + year*province(i) + year*variety(i)

> price = a + b(1)points^2 + b(i)country(i) + year*province(i) + year*variety(i)

Finally, one of our ultimate objectives was to identify certain words, associated with different varieties of wines, that a person can use to appear knowledgeable on the subject. For instance, dry reds and roses are more fruity with hints of berry whereas sweet, dry or sparkling wines are more crisp with citrus notes. 

**Conclusion:**
Although we have devoted a significant portion of our time to cleaning the dataset and extracting insights on different varieties of wines and our analysis therefore provides a decent guide to different wines, it isn't completely exhaustive. Our dataset is not representative of world population of wines. Moreover, we derive our insights from reviews and points provided by different tasters all of whom are not professionals. Even if they were, these reviews and descriptions are subjective and open to bias.  
