# Sentiment Analysis on IMDB Movie Review Dataset

Our team has picked IMDB Dataset of 50K Movie Reviews as the dataset of this 
assignment. Our team got the dataset from the Kaggle platform, here is the link to the dataset: 
https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews.

The classes of the chosen dataset are either positive or negative, which means it is a binary 
classification problem. Other than that, the dataset is also balanced over classes, that is 25000 
movie reviews are labelled as positive, another 25000 are labelled as negative.

The dataset is cleaned by executing the following steps:
- Convert all uppercases to lowercases. 
- Expanding contractions.
- Remove HTML tags.
- Remove punctuation.
- Remove stop words.

After performing the cleaning and EDA on the IMDB dataset, 4 predictive models are 
suggested by our team. Two of the predictive models are from traditional machine learning field, 
while the other two are from the deep learning field. This is normally when it comes to solving 
machine learning tasks, the models to be experimented with should start from the least complicated 
to the most complicated. The following predictive models are proposed: 
- Naïve Bayes
- Support Vector Machine (SVM)
- Convolutional Neural Network (CNN)
- Long Short-Term Memory (LSTM)

The training results and interpretations are all in the documentation. Plus, the best-performing model was also picked with justifications in the documentation.
