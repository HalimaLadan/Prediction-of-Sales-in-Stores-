# **Grocery_Sales_Prediction**
![grocery-1232944__480](https://user-images.githubusercontent.com/95732821/175866422-c6ba097d-fadb-4adc-a77e-9140cd3dd8aa.jpg)


## Overview

A Client wants to open a grocery store and has requested for a descriptive analyses on the trends on sales and the factors that affect sales returns. An also requested for the production a predictive model using existing data and training the model to give predictions on sales returns. 
***

## Description of the Data

Observations
The dataset contained 12 columns of features: 5 numeric and 7 object categories. Some of these features were not relevant to the prediction of sales and hence were not used.

***
## **Data Cleaning Process**
+ Missing values were located and imputed+
+  Duplicates were identified and dropped+
+ Odd values explored and fixed+
+ Column datatypes were checked and changed as needed+


***
## Data Analysis
***
Graphical display of Numeric Columns

A quick glance at the various features reveals the distribution of each feature in the dataset.


![image](https://user-images.githubusercontent.com/95732821/157936117-a1d6a398-fc75-4623-98b5-37341abcafd1.png)

***
The distribution of the types of fat content in products revealed that items containing low fat content sell more than those with the regular type of fat content.

![image](https://user-images.githubusercontent.com/95732821/157936499-cba99ce2-00da-4acb-96c8-0c238454aac8.png)
***
It was observed that the items with lower visibility distribution have the highest sale returns. So in order to maximise sales of items, the item visibility across has to have a low figure

![image](https://user-images.githubusercontent.com/95732821/157937281-6a7596bb-1828-4acd-8890-edfd92c42cb5.png)
***
The top Three Items that were observed to have high sales are the fruits and vegetables, Snack Foods and Household Items with breakfast and seafood items have the least sales return.

![image](https://user-images.githubusercontent.com/95732821/157936676-28c723f7-5a94-4641-8366-508c027b8455.png)
***
The sales outlet distribution in regards to sales revealed that medium sized outlets makes the highest number of sales as compared to other types of outlets.

![image](https://user-images.githubusercontent.com/95732821/157936743-d3298c44-f1d1-41fe-80e8-0b352cb940a1.png)
***
It was observed that out of all the outlet types,  Supermarket type 3 has the highest sales returns than any other type of outlet, while grocery stores makes the least sales

![image](https://user-images.githubusercontent.com/95732821/157936791-cc3fd879-0a87-41d0-acba-2496aac4cc75.png)

***
It was also observed that sales outlets located at the tier 3 and 2 type of location have higher sales than that of tier1
![image](https://user-images.githubusercontent.com/95732821/157936840-9872629b-d2f1-48b5-a6da-53ab57fbad1e.png)

**Recommendation:**
Based on the findings of this data analyses, the following factors should be considered in order to increase or maximise sales in or store outlet.

>- The store should be a medium sized.
>- It should be located in a Tier 3 type of location.
>- There shoud be a concentration on Fruits, vegetables and household items.
>- Concentrate more on products with low fat content than those with regular fat contents.
>- Maintain a very low percent of Item Visibility.

**Prediction**
The Random Forest regression model was the best performing model with a r2 score of : The Random forest will predict the sales of a store with almost accurate precision.



