# SentimentAnalysisUsingTensorflowEstimatorAPI
Model for identification of Positive/Negative Sentiments in texts using TensorFlow's Estimator API.

Explanation:

1. The tweets and their corresponding sentiments are read from 'Sentiment Analysis Dataset.csv'.
2. The tweets are tokenized and text embeddings are created using TF Hub's Universal Serial Encoder.
3. Text embeddings provide a way to represent pieces of text in vector space, so that similar words or sentences are closer together in the embedding space.
4. The program trains a Deep Neural Network classifier model having 2 hidden layers.
5. The 1st hidden layer contains 128 nodes whereas the 2nd hidden layer contains 24 nodes.
6. Once trained, this model can be used to predict the sentiment behind any text entered by the user.

Files:

1. SentimentModel.ipynb is the file where we train the model test it against the training data.
2. SentimentEstimator.ipynb is the files where the user can enter any text and the model predicts the sentiment behind it.

