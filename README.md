# The-Data-Science-Process

## Subsets:
a- How read a file 

b- What info do we need from data at the first step

c- Creating a ML model

d- Handling nan values (nan)

e- Removing nan values (dropna)

f- Impuding nan values (lambda)

g- Handling categorical variables (dummy)

h- Handing overfitting and improving model


## The CRISP-DM Process (Cross Industry Process for Data Mining)


1. Business Understanding

These were the questions we decided to explore in our dataset:

How do I break into the field?

What are the placement and salaries of those who attended a coding bootcamp?

How well can we predict an individual's salary? What aspects correlate well to salary?

How well can we predict an individual's job satisfaction? What aspects correlate well to job satisfaction?


2. Data Understanding

Here we used the StackOverflow data to attempt to answer our questions of interest. We did 1. and 2. in tandem in this case, using the data to help us arrive at our questions of interest. This is one of two methods that is common in practice. The second method that is common is to have certain questions you are interested in answering, and then having to collect data related to those questions.


3. Prepare Data

This is commonly denoted as 80% of the process. You saw this especially when attempting to build a model to predict salary, and there was still much more you could have done. From working with missing data to finding a way to work with categorical variables, and we didn't even look for outliers or attempt to find points we were especially poor at predicting. There was ton more we could have done to wrangle the data, but you have to start somewhere, and then you can always iterate.


4. Model Data

We were finally able to model the data, but we had some back and forth with step 3. before we were able to build a model that had okay performance. There still may be changes that could be done to improve the model we have in place. From additional feature engineering to choosing a more advanced modeling technique, we did little to test that other approaches were better within this lesson.


5. Results

Results are the findings from our wrangling and modeling. They are the answers you found to each of the questions.


6. Deploy

Deploying can occur by moving your approach into production or by using your findings to persuade others within a company to act on the results. Communication is a very important part of the role of a data scientist.
