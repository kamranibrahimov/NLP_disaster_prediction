# Natural Language Processing with Disaster Tweets
## Predict which Tweets are about real disasters and which ones are not
![alt text](https://storage.googleapis.com/kaggle-media/competitions/nlp1-cover.jpg)

### What we're going to cover
* Downloading a text dataset
* Visualizing text data
* Converting text into numbers using tokenization
* Turning our tokenized text into an embedding
* Modelling a text dataset
* Starting with a baseline (TF-IDF)
* Building several deep learning text models
* Dense, LSTM, GRU, Conv1D, Transfer learning


**Dataset**

We'll be using the dataset from Kaggle which contains text-based Tweets about natural disasters.
The Real Tweets are actually about diasters, for example:

`Jetstar and Virgin forced to cancel Bali flights again because of ash from Mount Raung volcano`

The Not Real Tweets are Tweets not about diasters (they can be on anything), for example:

`'Education is the most powerful weapon which you can use to change the world.' Nelson #Mandela #quote`

For convenience, [the dataset has been downloaded from Kaggle](https://www.kaggle.com/c/nlp-getting-started/data) (doing this requires a Kaggle account) and uploaded as a downloadable zip file.
