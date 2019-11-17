---
layout: post
title:      "Data Housing Cleaning "
date:       2019-11-17 21:24:02 +0000
permalink:  data_housing_cleaning
---


In analyzing my first big data set, I was overwhelmed with all the technical aspects that I needed to do to clean up the data, analyze it, visualize it, and then present all the information.  I had a hard time with the coding aspect because I literally had no experience going into this bootcamp.  I then realized that keeping it simple was the best way to approach this project.  Intuition is always a good start when it comes to solving complex problems.  In this situation, I was dealing with data sets regarding housing variables.  Intuitively, I can make some basic assumptions on different variables that could potentially predict house prices.  Here are some of the variables that I thought would be very important:

Location
Location
Location

Ok, so that’s only 1 variable, but it’s a good start.  Digging deeper, comparing location with the size of the house, and quantity of bedrooms, and even variables like if a house has a basement or not, would add more color in our algorithm.  

Now, to actually clean up the data and test whether our initial intuitive hypothesis follows suit.  With the world becoming more data-driven, we also need to step back a little and use our analytical skills instead of just plugging in numbers in a black box and relying on that answer.  As Data Scientists, towing the line of using our own skills vs. putting too much emphasis on programming is always key in creating actionable insights. 

The most common frustration I had when I did my initial data cleaning are errors.  I think this is the most common problem for beginners not only in Data Science, but programming in general.  My first realization came after dropping columns, but getting error afterwards, only to learn that I needed to use axis = 1, inplace = TRUE to make sure that it was transferred over to my data frame.  These kinds of small goals and wins are essential in getting over the hurdles of programming.  

The next part I had to learn was understanding that there is no correct answer/method to go about exploring your data.  As long as you can properly explain your methods (and maybe learn from your mistakes), that will make you a better Data Scientist.  I wanted so much to get the highest possible R^2 value that I became too obsessed with finding that number.  In reality, the most important part is making sure that you are able to properly clean and scrub the data.  With this first project, my head teacher explaining to me that this is the first project out of many, so you will have a chance in the future to go back and revise some of the things that you have done.  The best way to to do is do your best and get that r^.  

The last part that I believe is very important in data cleaning is being organized.  Have a top to bottom approach of how to handle data:

Importing Data and making an initial analysis using .head() & .tail() goes a long way
Identifying columns that are not relevant to the analysis will help make the process easier. 
Knowing how to deal with categorical values 
Understanding how to Standardized, Normalized, Scale, and deal with outliers 
Interpreting Data to see which variables could be used. 

By the time I finish writing this blog, I am still trying to fix my scalling errors in my jupyter notebook.  I got my initial r sqaure analysis but way too low of .5.  Check back on my to see if I am able to at least pass the threshold of .65 to make sure my project is done well.  




