# WEEK-4-INDEPENDENT-PROJECT-HYPOTHESIS-TESTING
#BUSINESS UNDERSTANDING
Autolib car-sharing service would like to get some insight on the usage of Blue cars and determine the most popular Postal Code for picking up Blue cars between Postal Code 75015 and Postal Code 75017.

#Postal code 75015
The 15th arrondissement of Paris is one of the 20 of the Capital city of France. In spoken French, this arrondissement is referred to as quinzieme
The land area of this arrondissement is 8.502 km2
 This is the most populous arrondissement of Paris, with 225,362 inhabitants at the last census in 1999. With 144,667 jobs at the same census, the 15th is also very dense in business activities. This arrondissement is home to many families and is known in Paris as one of the quietest sections in Paris. The majority of the arrondissement is relatively unfrequented by tourists, a rarity for one of the world's most visited cities.
 
#Postal code 75017
The land area of this arrondissement is 5.669 km2
Today, the arrondissement remains dense in population and business activity, with 160,860 inhabitants and 92,267 jobs as of the most recent census (1999).

#PROBLEM STATEMENT
In France,postal codes are used to identify the location of a place. First two digits represent the district, and the last three are for subdivisions (town or neighborhood). The dataset provided has 104 distinct postal codes.
Considering Postal code 75015 and 75017, identify whether the rate at which Bluecars are picked from the two stations is the same

#HYPOTHESIS
Is the number of Blue cars taken in postal code equal to the number of Blue cars taken in Postal Code 75017 ?
 
#NULL HYPOTHESIS
 The average number of Blue cars taken from Postal code 75015 Paris over weekend is same as those taken in Postal Code 75015.
#ALTERNATE HYPOTHESIS
The average number of Blue cars taken from Postal code 75015 Paris over the weekend is not the same  as those taken in Postal Code 75017.
Ho :  μ of 75015 = μ of 75017
Ha :  μ of 75015 ≠ μ of 75017

#METRIC FOR SUCCESS
This project will be successful when we identify whether the Blue cars taken in postal code 75015 are the same as Blue Cars taken in  Postal Code 75017

#Test used
T-test since the size of the sampeles is less than 30

#Significance Level
5%, Alpha = 0.05

#Results
Test statistic = 1.1384199576606167
P-Value = 0.3729402871375441

#Conclusions
Failed to reject the Null Hypothesis
