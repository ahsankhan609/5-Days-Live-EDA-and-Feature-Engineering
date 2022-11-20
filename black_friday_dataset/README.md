# Black Friday - EDA And Feature Engineering

1. [Black Friday - Dataset]('https://www.kaggle.com/datasets/sdolezel/black-friday')
2. [Youtube Lecture]('https://www.youtube.com/watch?v=cGez1q4iOFU&list=PLZoTAELRMXVPzj1D0i_6ajJ6gyD22b3jh&index=3')

> In this Lecture we will do following tasks:

1. EDA and Feature Engineering
2. Cleaning and Preparing Data for ML Model Training

## Problem Statement
A retail company “ABC Private Limited” wants to understand the customer purchase behaviour (specifically, purchase amount) against various products of different categories. They have shared purchase summary of various customers for selected high volume products from last month.
The data set also contains customer demographics (age, gender, marital status, city_type, stay_in_current_city), product details (product_id and product category) and Total purchase_amount from last month.

Now, they want to build a model to predict the purchase amount of customer against various products which will help them to create personalized offer for customers against different products.

### Feature Encoding

1. Gender -----> Male = 1, Female = 0
2. Age --------> '0-17'  = 1, '18-25' = 2, '26-35' = 3, '36-45'= 4, '46-50'= 5, '51-55' = 6, '55+' = 7
3. City Category -------> = 'A'  = 1, 'B' = 2, 'C' = 3
4. Stay in Current City Years ---------> = '1'  = 1, '2' = 2, '3' = 3, '4+' = 4