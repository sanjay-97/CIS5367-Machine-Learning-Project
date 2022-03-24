# CIS5367-Machine-Learning-Project

 Group Members: Sanjay Krishna Moorthy , Viswashanthi Bonala , Mitchell Moreno , Sneha Dudyala , Susmitha Haripriya Varanasi
 
 Reviews Data: https://drive.google.com/file/d/1F0-ASQ7DJagtpugLqvQhDPggbQkwwjRm/view?usp=sharing
 Recipe Data: https://drive.google.com/file/d/1-1VAw_qINDSeV_PBD-ylF0DnkDwL_wGt/view?usp=sharing

In this project we have created a business scenario where we are running a recipe subscription service. That is, we are delivering ingriedients to our customers every week in exchange for a subscription fee. The problem we would like to solve is figuring out how to recommend new recipies that our customers would like so that our customers extend their subscriptions, if they enjoy the recipies they are more likely to renew their subscription.

For this project we will be using two CSV files that contain data from Kaggle (https://www.kaggle.com/datasets/irkaal/foodcom-recipes-and-reviews). The first data file is the recipes dataset that contains information about the available recipes, and the second data file is the  reviews data set which contains data about user reviews for the recipes from the recipes dataset. All of our visualizations and explorations of this data are done by first joining the reviews and recipes data set and analyzing the resulting joined data.

In our code we first start off with providing the total number of reviews we are working with as well as the number of reviewers, the values are 798,270 and 157,500 respectively. Also there are 229,665 different recipes from 285 categories in the data sets we are working with. We then look at the top rated categories on average, followed by the top 25 recipes with five star reviews.

We then have a pie chart which displays the distributuions of the ratings. Following is a table which displays the number of reviews left by each customer, with number of reviews in desending order. We also made a scatter plot where each dot on the graph is the length of review text for a given review. 

The most common ingrients are also found, and we display the top 15 most common ingrdients. Finaly we have a plot of ratings from a single customer, this is used to show how difficult it would be to properly select a recommendation for a customer manually, especially if they have rated thousands of recipes.

In project presentation II we will be implementing a recommendation engine that uses implicit/explicit variables provided by our users.

