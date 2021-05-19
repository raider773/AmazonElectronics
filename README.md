# AmazonElectronics
Sentiment analysis with Amazon electronics reviews

This project is a simple prediction on whether a review is positive or negative one. \
In the first notebook i analyse a little bit the reviews. Just the reviews as this is an NPL problem. \ 
I also binarize the problem to two classes, good or bad, instead of 1 to 5 rating as in the original data. \
The data is in json format so i transform it into csv format.


In the second notebook i used Multinomial Naive Bayes models to do the predictions as well as transforming the data as needed. \
Finally i deployed the model to flask and test the model with self-made comments \


![image](https://user-images.githubusercontent.com/70241561/118748976-07490180-b833-11eb-9730-08406d0e227a.png)

The data was quite unbalanced. I used undersampling for the training of the model.


![image](https://user-images.githubusercontent.com/70241561/118749059-2b0c4780-b833-11eb-9c5c-9d803083878f.png)

I transform the problem into a binary classification. Ratings 4 and 5 are consireder good, while 3, 2 and 1 are considered bad. \



![image](https://user-images.githubusercontent.com/70241561/118749131-4a0ad980-b833-11eb-8dbb-6dcd702b02cf.png)

This is the shapes of the data used in both training and validation after undersampling. \
I used a multinomial Naive Bayes. \

-------------------------

Finally i deploy the model with flask.

![image](https://user-images.githubusercontent.com/70241561/118749233-7b83a500-b833-11eb-8e35-e2a02cc1a97e.png)

