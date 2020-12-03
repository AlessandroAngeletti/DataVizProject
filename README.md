# Anyone Can Become a Sommelier
***
**AM10: Data Visualization and Story Telling | Group Project | Study Group 13**

_Grüner Veltliner, Rioja, Bourgeuil, or Cabernet Sauvignon?_

On average, six out of ten Brits wish they knew more about wine, with over half so overwhelmed by their lack of knowledge that they leave wine-related decisions to someone else. However, this doesn't have to be the case especially when you're out on a date. 

The [Data Set](https://www.kaggle.com/zynicide/wine-reviews) we are investigating was originally scraped from [WineEnthusiast](https://www.winemag.com/?s=&drink_type=wine) in November, 2017. We analyse information on 129,971 reviews (score points) on 708 varieties of wine as well as their prices and origin (country and winery) to answer the following questions:
**(1) What makes a wine good?** 
**(2) What makes a wine pricey?**
**(3) Is a more expensive wine necessarily a better wine?** 
Therefore, we attempt to identify the factors which contribute to a wine being good and/or expensive, assess whether there exists a strong correlation between the two, and if we can predict...??? 

> This data offers some great opportunities to improve our understanding of wines, or at least give us enough "knowledge" to order one which is good-quality and a bang for the buck. 

To achieve the aforementioned objectives and make further visualizations more meaningful we first inspect, clean and explore (ICE) the data. This includes getting rid of unnecessary columns, duplicate values, and checking for errors and outliers through boxplots. Further, we resolve the missing values in `country` and `variety` by matching information on wines from the same wineries and extracting information from the description wherever possible. In addition, the description gives a lot of insights on the region-specific characteristics of wines. For example, French wines are most frequently associated with words such as rich, crisp, acid, fruit, ripe, fresh, etc.

Next, we examine the distribution of prices and scores across parameters like geographical location and find out that:
- our dataset is majorly dominated by reviews of wines from the US
- wines from England have the highest average rating
- wines from Germany and Austria are the safest bet as their median scores are fairly high

**Regression Models**
For regression analysis, we decided to stick to the data pertaining to top 5 countries with wine reviews i.e. US, France, Italy, Spain and Portugal, and limit the price threshold to **$156.** 


## complex data cleaning phew - description, missing values 

## Objectives

* Visualize the geographic original of the wines available in the data set;
* Discover how price correlates with the rating of the wine;
* How the description of the wine correlates to its geographical location;
* If the price is impacted by the variety of grape used; and
* How price is influenced by its description, variety, location, etc.

## Visalusations

1) Map plots;
2) Scatter plots;
3) Cluster analyses;
4) Distributions; and
5) Word banks.

## Guidelines

DATAVIS GROUP  PROJECT 
1. load and inspect data (vroom, skim)
2. clean data - variable types, null values, missing values, outliers, categorical variables (cross column sense check)
3. look for trends and relations (histograms, scatter plots, correlation matrices) 
4. feature engineering? (like cumulative_14_day_cases in covid data) - look into new columns we can create
5. visualisations (at least 3 different types of charts - let's do a map as well hehe)
6. focus on a story throughout + conclusion

DELIVERABLES 
1. group presentation to be uploaded on canvas
2. github repo + public repo with readme file
3. one page description of project + questions we're trying to answer
4. rmd file