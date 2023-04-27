# Banglore Housing Price Prediction

As the fastest growing city in India according to BuisnessWorld, the supply of residential properties is struggling to catch up to the demand of the housing market.

This simple machine learning model is trained on a huge dataset of historical housing data from Kaggle inorder to predict the property value depending on factors such as the area of the property, number of bedrooms etc. Please do not consider the result as the face value of the property but rather as a reference value, as the markets fluctuate a lot.

Monthly rental rate is calculated using the standard yield of 2.5% of the market value. Can vary on the vendor and several other factors.

## Implementation

- The dataset is taken from Kaggle (https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data)
- I have used simple linear regression fro training, as it gave the highest accuracy.
- Implemented the server using flask.
- It was then exported and hosted in an AWS ec2 Ubuntu server uing nginx.

## Demo

![](https://github.com/yoonus47/Banglore-House-Price-Prediction/blob/master/Recording/scr.gif)

You can check out the site from the link: (http://ec2-3-104-110-39.ap-southeast-2.compute.amazonaws.com/)
