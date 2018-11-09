# Executive Summary

When I receive real estate listing notification from my realtor, there is some basic information such as price, house images, bedrooms, bathrooms..., etc. Except for price, the first impression of a listing is the house image. When I look at a house image and I don't like it, it doesn't matter many bedrooms, bathrooms...etc, this house has.

My realtor’s strategy is to recommend me the houses which price is under a set threshold. When I check the house images, I don’t like most houses. Can I use machine learning algorithm to classify the house images into binary categories, namely like and unlike. I so, it is not only a great system to recommend listing but also save me a lot of time on checking listings.

However, there are two main challenges. The first one will be insufficient data. The like/unlike of house images are based on how many houses the client checks. The second one is the image quality.     

The purpose of this project is to: (1) build a classification system to classify house images into binary categories, (2) test the limitations of CNN technology.

House images are collected from recently sold houses in six cities, namely city of El Cerrito, El Sobrante, Hercules, Pinole and San Pablo. Based on the smallest size of images and the majority of the image width/height ratio, all images are resized into 150 pixels times 100 pixels. Six classification models and the convolutional neural network (CNN) model are applied to classify house images. 

The highest test accuracy 82.7% is obtained by the CNN model with 74.1% baseline accuracy in the city of Pinole. The confusion matrix reports 57 true positives, 11 false positives, 10 true negatives, and 3 false negatives. 

If the listings are recommended by the 68 positive predictions(TP+NP), it will save 16% (1 - positive predictions/all) time on checking listings. The 83.8% precision shows the FP less than 17 %. The 95% sensitivity means only 5% FN is misclassified.  

In the future, increasing the precision and control the sensitivity will make this system more robust.