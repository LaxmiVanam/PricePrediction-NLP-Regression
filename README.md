# PricePrediction-Regression

The Challenge
Build a model to suggest the price of product on Mercari, a company that sells products online. The model is required to train (including all the preprocessing, feature extraction and model training steps) and inference in the most effective way possible. Data include unstructured text (product title & description) and structured ones, e.g., product category and shipping flag etc.

## The following are the dataset features provided in the competition 
 - ID: the id of the listing
 - Name: the title of the listing
 - Item Condition: the condition of the items provided by the seller
 - Category Name: category of the listing
 - Brand Name: brand of the listing
 - Shipping: whether or not shipping cost was provided
 - Item Description: the full description of the item
 - Price: the price that the item was sold for. This is the target variable that you will predict. The unit is USD.
 
 ### Keywords
- Pricing recommendations 
- Regression
- NLP
- BagOfWords
- Keras etc.

I could not upload the datasets to github as the file sizes are large and data for this competitoin can be found @https://www.kaggle.com/c/mercari-price-suggestion-challenge/data. I have used Keras regressor to accomplish the task and have uploaded the code here.
