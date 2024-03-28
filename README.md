# Analysis of Offer Effectiveness at Starbucks

Explore the blog article [here](https://medium.com/@julian.berg/forecasting-success-of-starbucks-promotions-and-identifying-key-factors-for-promotion-success-6dfaed6f191a)

### Index of Contents

1. [Required Software and Libraries](#Libraries)
2. [Insights from the Project](#motivation)
3. [Principal Findings](#summary)
4. [Structure of This Repository](#files)
5. [Acknowledgements and Sources](#licensing)

## Required Software and Libraries <a name="Libraries"></a>
To execute this analysis, the following software and libraries are necessary:
- python==3.6.3 (suggested)
- seaborn==0.8.1
- pandas==0.23.3
- numpy==1.12.1
- matplotlib==2.1.0
- sklearn==0.19.1

## Insights from the Project<a name="motivation"></a>

This project forms the culmination of the Udacity Data Science Nanodegree. The analysis leverages simulated data that mirrors user engagement with the Starbucks reward app. Starbucks periodically dispatches offers to app users, which could range from simple advertisements to actual value deals like discounts or BOGO (buy one get one free). The data encompasses details on the offers, demographic information of the customers, and logs of transactions and offer interactions.

The core aim is to:

Determine if we can predict the success of an offer using demographic and offer-specific data.
- Develop a model that can forecast the success of offers using available demographic information and details about the offer.

Additionally, it seeks to answer:
- Which type of offer has the most success?
- Who is more likely to spend more, males or females?

## Structure of This Repository <a name="files"></a>

This GitHub repository contains:
- \data
    - info_about_data.md : Information on the dataset used (details provided as the dataset is larger than 20Mb and not uploaded).
- Starbucks_Capstone_notebook.ipynb: The notebook for the project.
- Starbucks_Capstone_notebook.html: A HTML version of the project notebook.
- README.md : An overview of the project.
- Blog.md : The blog post in markdown format.

## Principal Findings <a name="summary"></a>

The main insights of the study are discussed in the blog post available [here](https://medium.com/@julian.berg/forecasting-success-of-starbucks-promotions-and-identifying-key-factors-for-promotion-success-6dfaed6f191a).

To summarize, the highlights are:
- The AdaBoost classification model was applied to anticipate the completion of offers by examining customer profiles and offer parameters, reaching a 67% accuracy.
  - Crucial elements for predicting offer success included:
    - The length of membership, the level of income, age, and the duration of the offer.
- It was observed from the data that females generally outspend males, which could guide Starbucks in fine-tuning their marketing strategies.
- Discounted offers were found to be more effective than BOGO offers, not only in the quantity of completed offers but also in achieving a notably higher rate of completion relative to reception by about 7%. While BOGO offers have a higher visibility among customers, discounts are more successful in converting an offer from received to completed.

## Acknowledgements and Sources<a name="licensing"></a>

- Credit must be given to Starbucks for providing the dataset.
- This project is a component of the Data Scientist Nanodegree from Udacity.