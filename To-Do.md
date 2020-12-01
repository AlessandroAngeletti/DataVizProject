# Data Viz Group 13 Task List

***

</br>

## Step 1 - Data Cleaning

> All but one person should work on this section!
> 
> The last person whould go ahead and describe in words what has been done using the same format as the Data Cleaning assignment.

We have to clean the following variables:

* ~~`Country` - This one is a mess...~~
* `Description` - **One/two people should handle this**

Objective would be to extract key-words from here such that we have features for clusters analysis.

*Maybe the data can be saved in a list format?*

* `Designation` - Handle missing values
* `Price` - Handle missing values
* `Points` - Handle missing values
* `Province` - Handle missing values 
* `designation` - This one is a mess...
* `region_1` - Handle missing values
* `region_2` - Handle missing values

*Maybe we keep only one of the regions (?)*

* `taster_name` - Don't elim, we can see how different tasters give different scores! Aka build the tasters preferences!
* `taster_twitter_handle` - *We can probably elim this?*
* ~~`variety` - Handle the missing value~~
* `title` - Extract the year from the title

***

</br>

## Step 2 - Exploratory Data Analysis

> Do not attempt or even start until most of *Step 1* has been completed!

1) Map plots;

**Tableu**

* Plot where the wines are from and their sub-region.
* Show average score by region
* Show average price by region
* Show most common `variety`

2) Scatter plots;

**R**

*Pick only a few of these; no more than three!*

* Price v Points
* Price v Location
* Price v Variety
* Price v Winery
* Points v Winery
* Points v Location
etc...

Perhaps only do a few scatter plots of variables we want to predict - price and score.

Then develop a correlation plot that show the correlation between variables (?)

3) Cluster analyses;

Utilize the clean information extracted from `description` to attempt to develop clusters.

4) Distributions; and

See how `price` and `score` are distributed.

Make a judgment on the idea of using the `scale()` function on these variables.

*Any other fancy ideas are welcome!*

5) Word banks.

Use the python script to develop words banks of the most common attributes that we've cleaned up.

Maybe shape the word bank as a wine bottle / glass (?)

***

</br>

## Step 3 - Predicting Price and Score

Break out those fancy statistical modeling and ML techniques to attempt to predict the price based on the information that we've gained form *Step 2*.

Model to perhaps explore:

1) Simple OLS
1) Logistic
1) LASSO
1) Machine Learning Techniques Learnt

*More funky ideas are welcome!*

***

</br>

## Step 4 - Cluster Analysis

Follow the format of th PCA lecture!

***

</br>

## Step 5 - Recap Finding in Beautiful Graphs

*Too far ahead for me to thinking about...*

***

</br>

## Step 6 - Develop the Website