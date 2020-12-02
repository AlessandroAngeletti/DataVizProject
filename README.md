# Anyone Can Become a Sommelier

***

*by Study Group 13*

_Grüner Veltliner, Rioja, Bourgeuil, or Cabernet Sauvignon?_

On average, six out of ten Brits wish they knew more about wine, with over half so overwhelmed by their lack of knowledge that they leave wine-related decisions to someone else. However, this doesn't have to be the case especially when you're out on a date. 

The [data Set](https://www.kaggle.com/zynicide/wine-reviews) we are investigating was originally scraped from [WineEnthusiast](https://www.winemag.com/?s=&drink_type=wine) in November, 2017. We analyse information on 129,971 reviews (score points) on 708 varieties of wine as well as their prices and origin (country and winery) to answer the following questions - 
(1) What makes a wine good? 
(2) What makes a wine pricey?
(3) Is a more expensive wine necessarily a better wine? 
Therefore, this data offers some great opportunities to improve our understanding of wines, or at least give us enough "knowledge" to order one which is good-quality and a bang for the buck. 

To achieve the aforementioned objectives and make further visualizations more meaningful we first inspect, clean and explore (ICE) the data. This includes getting rid of unnecessary columns, checking for errors and outliers through boxplots, and duplicate values. Further, we resolve the `country` missing values by matching wines to the same wineries and extracting the countries from wherever possible.   
 
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
