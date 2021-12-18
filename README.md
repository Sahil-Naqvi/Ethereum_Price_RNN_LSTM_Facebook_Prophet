# Ethereum_Price_RNN_LSTM_Facebook_Prophet

Ethereum is the reason for the recent drop in bitcoin prices. The price of Ethereum is currently very cheap compared to bitcoin, but some financial experts, including Tesla’s CEO Elon Musk, claiming that we will see a rise in the price of Ethereum soon. So, the question is how to predict the future prices of Ethereum, this small project throws some light on how to predict the price of Ethereum with the help of RNN and LSTM. In this small project report, I will walk you through the task of Ethereum Price Prediction with Deep Learning using Python.

**ETHEREUM PRICE PREDICTION**

Predicting the price of a cryptocurrency is a regression problem. Bitcoin is one of the most successful examples of cryptocurrency, but we recently saw a major drop in bitcoin prices due to Ethereum. Unlike bitcoin, Ethereum is very cheap right now, but financial experts are predicting that we may see a major increase in Ethereum prices.
There are many machine learning approaches that we can use for the task of Ethereum price prediction. You can train a machine learning model, or you can also use an already available powerful model like the Facebook Prophet Model. But in the section below, I will be using the Deep Learning approach using RNN and LSTM  for the task of Ethereum price prediction and, I try experimenting one machine learning approach that is a powerful model named as Facebook Prophet Model.

Dataset that we collected is from 01/01/2018 till 31/12/2019. Contains 730 Entries in total.
In this dataset, the “Open” column contains the values whose future values that we want to predict, so let’s have a closer look at the historical values of Open prices of Ethereum:

![image](https://user-images.githubusercontent.com/87114918/146646615-71e00551-41d5-4b60-a07d-e33290579d7a.png)

Similarly, we can plot for “Close” Column of Ethereum and see how it is behaving for better understanding.

![image](https://user-images.githubusercontent.com/87114918/146646620-7920b10a-22cd-4791-a945-46a011ceeb8c.png)

**RESULT OF RNN MODEL**

**TESTING ON TEST DATA 1 (FROM 01/01/2020 TILL 31/03/2020)**

![image](https://user-images.githubusercontent.com/87114918/146646632-5ac221aa-9980-49e1-907a-fb6a78655bb3.png)

**TESTING ON TEST DATA 2 (FROM 01/04/2020 TILL 31/06/2020)**

![image](https://user-images.githubusercontent.com/87114918/146646641-e5da00ec-6bc6-4199-b41a-16fc0198d5a4.png)

**RESULT OF LSTM MODEL **

**TESTING ON TEST DATA 1 (FROM 01/01/2020 TILL 31/03/2020)**

![image](https://user-images.githubusercontent.com/87114918/146646674-4d91783c-f776-4719-98bc-620b5cda519b.png)

**TESTING ON TEST DATA 2 (FROM 01/04/2020 TILL 31/06/2020)**

![image](https://user-images.githubusercontent.com/87114918/146646682-026c73b8-f2ec-431d-99b6-72251789acd5.png)

**RESULT FACEBOOK PROPHET MODEL **

![image](https://user-images.githubusercontent.com/87114918/146646709-279d91ed-6561-4fb9-8fc6-6cb3f1280abf.png)

**SUMMARY**

There are many machine learning approaches that we can use for the task of predicting the future prices of Ethereum. In this Project, I introduced you to how you can predict the future prices of Ethereum by using the RNN and LSTM in Python. And I did try Facebook Prophet Model but unable to get anything out of it. I hope you liked this project on how to predict the future prices of Ethereum with RNN and LSTM using Python. 
Here, I found that the Root mean squared error of LSTM is slightly lower than that of RNN and on the other hand the predicted price value of Ethereum almost converges to that of Real price of Ethereum. As per the evidence we can conclude that LSTM performs better than RNN.
The Root mean square error of RNN was found to be 18 and LSTM was approx. 16.
For justifying the predicted price of Ethereum I concluded that due to covid financial condition become worse and this is the reason for irregularities in the graph.

