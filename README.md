# SnapIt
SnapIt is an online reselling platform where local sellers can list their products for sale and obtain the right amount of money from items they might not need anymore.

You are the new employee hired by SnapIt to solve their main issue- deciding the selling price of their products. Most sellers do not know how to reasonably price their products and would like to be able to choose an optimum selling point. The problem here is that a user can list any item for sale or even a group of items from various categories.

Based on data provided about each item by the seller, you must choose a selling price for the specified product.



Dataset Description
File descriptions
train.csv - the training set
test.csv - the test set
sample_submission.csv - a sample submission file in the correct format
Details about the data:

PRODUCT_ID - id of the product
PRODUCT_NAME - this is the name of the product provided by the seller
PRODUCT_CONDITION - a number signifying the condition of the product
CATEGORY - product category
PRODUCT_BRAND - brand the product belongs to
SHIPPING_AVAILABILITY - if the product is paid by the seller to be shipped or not (0 if not paid 1 otherwise)
PRODUCT_DESCRIPTION - the description of the product provided by the seller
PRODUCT_PRICE - this is the label; The value which is to be predicted
Note: Some of the data provided to the platform by the seller contained some prices. They have been removed and the space is filled using '[rm]'.

The sample_submission.csv contains:

#PRODUCT_ID - id of the product
#PRODUCT_PRICE - some dummy value
