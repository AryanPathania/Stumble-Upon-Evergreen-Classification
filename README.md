# Stumble-Upon-Evergreen-Classification<br>
StumbleUpon is a user-curated web content discovery engine that recommends relevant, high quality pages and media to its users, based on their interests. While some pages we recommend, such as news articles or seasonal recipes, are only relevant for a short period of time, others maintain a timeless quality and can be recommended to users long after they are discovered. In other words, pages can either be classified as "ephemeral" or "evergreen". The ratings we get from our community give us strong signals that a page may no longer be relevant - but what if we could make this distinction ahead of time? A high quality prediction of "ephemeral" or "evergreen" would greatly improve a recommendation system like ours.

Many people know evergreen content when they see it, but can an algorithm make the same determination without human intuition? Your mission is to build a classifier which will evaluate a large set of URLs and label them as either evergreen or ephemeral. Can you out-class(ify) StumbleUpon? As an added incentive to the prize, a strong performance in this competition may lead to a career-launching internship at one of the best places to work in San Francisco.

### Dataset<br>
This is the link for the [dataset](https://www.kaggle.com/c/stumbleupon/data). 

### Approach!!! <br>

- First I extracted the main information from the dataset to process it further.
- Then, I used **BertTokenizer** to tokenize the words so that these words can be processed by our network.
- After that I have used pre trained **BERT Transformer** specifically **BertSequenceClassification** to classify the text input as "evergreen" and "ephemeral".

### Result!! <br>
I got 78% score on the test set on Kaggle 
