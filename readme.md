# Problem statement

When I receive real estate listing notification from my realtor, I probability look at some basic information such as price, house pictures, bedrooms, bathrooms..., etc. Except price, the first impression of a house is more important than other information. If I look at house pictures then I don't like it, it doesn't matter many bedrooms, bathrooms...etc, the house have. 

However, my realtor keeps sending me all the houses with price under some threshold. Then, he sometimes sends me message "there is a house you might be interested in, we can go checking it on sunday". How does my realtor know I probably like this house? It might because we do house hunting for two years together, so he learned.

![](assets/listings.png =250x)

**According to this situation, can I use mechine learning algorithm to build a classification system by classifing the house images which I like, then the system tells me some house I might be interested in, like my realtor do?**

If this system works, it can save me a lot of time in checking every house with price under setting threshold. Then I just need to check price of all the houses system tells me.

The main challenge of this problem would be:

1. Insufficient data: it doesn't make sense to ask someone watch house more than 300 images.
2. Image quailty: every home owner takes pictures in different angle, different layout. 

In this project, I need to go through several steps:
1. Obtain data: the features of data will contain house picture, bedroom, bathroom, house size, lot size, price, city. Please check `1 web-scraping.jpynb`

2. Data cleaning: Please check `2 data-cleaning.jpynb`

3. Image preprocessing: Please check `3 image-preprocessing.jpynb`

4. EDA: Please check `4 eda.jpynb`

5. Model: Logistic Six classification models which is regression, decision tree, random forest, KNN, SVM, and gradient boosting are used to classify this binary class like and unlike. Please check `5 model-classification`. A CNN model is built to classify this binary class like and unlike. Please check `5 model-cnn`

6. Evaluate model:

7. Answer the problem: 123

<span style="color:orange;">Word up</span>


