# ICO-Model
In this project, I have created a classification model to predict the success of a campaign based on Crowdfunding. Tools used in the project are Jupyter Notebook, Pandas, Numpy, Matplotlib, Sklearn and yfinance. 

Bitcoin, ever since its advent in 2009, has been the most widely used Cryptocurrency in the World. Recently, several other types of coins based on different blockchains have come into picture after being created. These coins are typically used by firms to raise funds for the development of a project or to conduct activities from a large crowd of people. These types of project fundings using Cryptocurrency are called Initial Coin Offering (ICO). Firms call for funding of the projects based on the issuence of coins to investors sitting online. Coins (Cryptocurrencies) are the valuable digital medium that is offered as the currency in order to service the product offered and is traded between investors.

The ICO crowdfundings use a method called the 'All-or-Nothing' model. In this model, a certain goal is set that communicates the idea of the success of the funding. A certain currency amount in a stipulated time is set, and if the desired money has been raised in the timeframe, it is considered a success. Else, it is a failure. These details are presented by the ICO on their campaign page.

In the given project, data has been collected from the campaign page. The project has been worked on using Python and Jupyter Notebook, where frameworks like Pandas, Numpy, Matplotlib and Scikit learn has been used for cleaning, visualizing and modelling the data. yfinance is used for extracting costs of the tokens used in the campaign. Our dataset, that is made into the a Pandas Dataframe, has the following attributes:

1. ID: The unique number of the ICO project
2. success: An indicator variable which is set as 1 if the ICO project raised funding successfully. Else, it is 0.
3. startdate: Start date of the campaign.
4. enddate: The end date of the campaign.
5. tokenNum: The number of tokens to be issued. Higher the tokens issued, lesser the cost.
6. teamSize: The number of team members
7. country: The country of the ICO project.
8. categories: The categories (sectors) of the ICO project.
9. overallrating: The overall rating score for the quality of the ICO project, given by investment experts (1-5 rating, bad-good)
10. offered_ownership: The ratio of tokens given to investors.
11. tokenName: Name of the token issued.
12. tokenPrice: Price of the token.
13. platform: Name of the blockchain platform the ICO project is based on.
14. acceptingCurrency: The currencies being accepted.
15. softcap: Set as 1 if the minimum fundraising amount has been mentioned, otherwise 0. This indicates that the team etimated the amount of moneyrequired to execute the project.
16. hardcap: Set as 1 if the maximum fundraising amount has been mentioned, otherwise 0. This indicates that the team etimated the amount of moneyrequired to execute the project.
17. whitepaper: Set as 1 if whitepaper was provided.
18. video: Set as 1 if a video was provided in the campaign
19. socialMedia: Activity level of social media usage in the campaign (0-3).

This dataset will be visualized based on attributes and modelled using the classification modelling algorithms.
