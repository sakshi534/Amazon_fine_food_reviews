# Amazon_fine_food_reviews
This dataset consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. Reviews include product and user information, ratings, and a plain text review. It also includes reviews from all other Amazon categories. The goal is to correctly label the amazon fine food reviews as either positive or negative. This is a supervised learning task so I will be employing various supervised learning techniques.

# Data Statistics
●	568,454 - Reviews
●	256,059 - Users
●	74,258 - Products
●	260 users with > 50 reviews
●	10 Columns

# Each review has the following 10 features:
•	Id
•	ProductId - unique identifier for the product
•	UserId - unique identifier for the user
•	ProfileName
•	HelpfulnessNumerator - number of users who found the review helpful
•	HelpfulnessDenominator - number of users who indicated whether they found the review helpful
•	Score - rating between 1 and 5
•	Time - timestamp for the review
•	Summary - brief summary of the review
•	Text - text of the review

# PLATFORM USED

PySpark on Databricks
Motivation behind the project was to apply the academic knowledge to solve the big data challenge, which in this case was the volume of data. Python on spark via databricks platform, which gives the freedom to run the entire dataset on the cluster.


