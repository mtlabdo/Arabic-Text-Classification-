# Arabic-Text-Classification-
Arabic Text Classification Using Cnn and Rnn 
> System Architecture:
In this project, we try to elaborate the state of the art of text classification in Arabic using language models and deep learning. The use of language models is due to simplicity of intergration in a neural network and its intuition of representiong words in a vectorial space which helps calculating dependencies between words.
6.1. Data Preparation:
In this step we need to prepare our dataset:
6.1.1. Split Data into Train and Test Sets:
We will be developing a system that can predict the sentiment of a textual as either positive or negative and that require to develop a system to be performed on those new reviews as is performed on the training data for the model.
We will split our data into a 90% train, 10% test of the data, that’s means we will take last 10% of dataset for test and the rest of data will be used to train our model.
We can split data easily by create filename contain data for training and other contain data for test.
￼￼
￼6.1.2. Loadingandcleaningthedata:
The processing steps for cleaning and normalizing the corpus are as follows: 1) Removepunctuation,non-Arabicletters,
2) removingsymbollike(?!,..)
6.2. Modeling our system of sentiment analysis:
This model contains two part: Word Embedding and Convolutional neural network method (CNN).
6.2.1. Word Embedding layer:
A word embedding is a way of representing text where each word in the vocabulary is represented by a real valued vector in a high-dimensional space, this is a more expressive representation for text than more classical methods like bag-of-words (BOW).
Such a vector comes to represent in some abstract way the ‘meaning’ of a word. We can also use the vectors as inputs to our neural network.
Word embedding give the similarity between words and represent it as a vector signify the similarity, that can help in separate our data in categorical data (Positive/negative/neutral). Example:
￼￼￼￼￼Word representation is a major change in NLP research due to its great help in late advances
￼in different problems related to text analysis for specific topic : Text classification, Topic
￼modeling, intention recognition etc
