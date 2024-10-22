# Customer-segmentation-on-online-retail
For this use case, the idea is to cluster customers together based upon their spending habits. Above we mentioned the idea that people who live in northern climates are more likely to buy warmer clothing. This is an example of customer segmentation. We could also segment based on age, gender, marital status, social class or a myriad other criteria. In doing so, advertisements can be targeted to a given demographic, personalised recommendations can be constructed and entirely new customers can be identified. A relatively recent example of this has been the resurgence in popularity for vinyl among younger generations.
There are roughly four types of segmentation we consider:

•	Demographic: Gender, age, marital status, occupation

•	Geographic: Location, region, urban/rural

•	Behavioural: Spending, consumption habits, product/service usage, purchase history

•	Psychographic: Social status, lifestyle, personality characteristics
________________________________________
A popular method for customer segmentation is to use RFM (Recency, Frequency, Monetary) analysis. This is a behaviour-based approach to grouping customers into segments which does so using information about previous purchase transactions. The idea is that we want to know how recently a customer purchased a given item, how frequently they purchase this item and, when they do purchase the item, how much did they buy.
Each of the three variables (recency, frequency and monetary) consist of four equal groups. This creates 43=64 different customer segments. The steps of RFM are therefore as follows:
1.	Calculate the recency, frequency and monetary values for each customer.
2.	Add segment bin values to the RFM table using quartiles.
3.	Sort the customer RFM score in ascending order.
To see this in action, we will perform customer segmentation on the Online_Retail dataset found at https://www.kaggle.com/datasets/vijayuv/onlineretail/.

There are several Python libraries that can be used for association rule mining:

•	apyorl

•	mlxtend

•	PyCaret

Second example based upon the grocery store dataset found at https://www.kaggle.com/datasets/shazadudwadia/supermarket.
