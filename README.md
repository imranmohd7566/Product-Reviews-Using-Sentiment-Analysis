# Product-Reviews-Using-Sentiment-Analysis

This is a dataset of amazon reviews of watches collected from amazon with the official rights.
A repository of 1.8 million reviews, with relevant features such as customer_id, category, product_id, product_title, review_body, review_headline, star_rating, and more.
After cleaning the data and extracting some imporatant info and EDA we reduce the dataset size.

As we try the deep learning models the results are exceptional but the run time is very high as shown in the table below.

![image](https://user-images.githubusercontent.com/50734928/189010930-1e5f3601-8fc9-4874-9e97-5e32f81bd789.png)

What else could we do?
I haven't tried a lot of things here. Other fields from the original Amazon data, I believe, could be added to the model. Furthermore, we did not include any global features from the samples, such as length, character level features, and so on. We could even try character-level deep learning models to see if they can reduce sensitivity to misspellings. Character level characteristics may be important in online reviews because users may misspell things to avoid moderation. However, because these models are already performing near-perfectly, any gains will be minimal at this point.
