# Emotion-Classifier
The aim of the project is to detect the user emotions from the sentence gave by the user.

## Domain
![an-introduction-to-natural-language-processing-with-python-for-seos-5f3519eeb8368](https://user-images.githubusercontent.com/61903698/177008045-2652ce27-8eea-42e0-a2cd-b6207304bb28.png)



## NLP PipeLine:
![1 CbzCcP3XFtYVJmWowZLugQ](https://user-images.githubusercontent.com/61903698/134461144-5f71a441-5b74-4d83-a3ce-8d12823aea25.png)

## Tokenization:
![maxresdefault](https://user-images.githubusercontent.com/61903698/134461654-73f03562-ec9f-4164-9be1-cd1f37bbd9d2.jpg)

Tokenization is a way of separating a piece of text into smaller units called tokens.

                 
## Stopwords:
![stop-word](https://user-images.githubusercontent.com/61903698/134461738-aa31ae44-c394-43cc-8123-935b9f20cf57.jpg)

Stop words are irrelevant words that won’t help in identifying a text as real or fake. We will use “nltk” library for stop-words and some of the stop words in this library are :

                               stopword = nltk.corpus.stopwords.words('english'


##  Stemming or Lemmatization:

Stemming and Lemmatizing is the process of reducing a word to its root form. The main purpose is to reduce variations of the same word, thereby reducing the corpus of words we include in the model. The difference between stemming and lemmatizing is that, stemming chops off the end of the word without taking into consideration the context of the word. Whereas, Lemmatizing considers the context of the word and shortens the word into its root form based on the dictionary definition. Stemming is a faster process compared to Lemmantizing. Hence, it a trade-off between speed and accuracy.

![maxresdefa](https://user-images.githubusercontent.com/61903698/134461955-1a877f69-f60d-42b0-b652-70b2bd892bfa.jpg)

## Model Buillding 
![1 dWY7adQ62NDn_w_sc4lAKw](https://user-images.githubusercontent.com/61903698/134462100-eb766cb0-d6af-40bc-b065-e929778304fc.png)

* After text preprocessing we have to convert the sentences into vectors because the machine only understand the vectors.
* After convertion we can split the dataset into train and test. for this project i took 75% for my training set and 25% for my test set
* Then we can use any machine learning algorithms for building the model. 


## Evaluation:
* Confusion matrix and accuracy scores are helps to find the performace of the model 
![1_3yGLac6F4mTENnj5dBNvNQ](https://user-images.githubusercontent.com/61903698/177008768-d9a3c6a5-c2cc-48c8-952c-d6059b563927.jpeg)


## Deployment:
![images](https://user-images.githubusercontent.com/61903698/134462616-dbb8e3b4-ab26-45a8-9b66-5fe4e0d66630.png)
