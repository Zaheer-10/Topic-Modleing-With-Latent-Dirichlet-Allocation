# Topic Modeling with Latent Dirichlet Allocation in Python

![alt text](https://github.com/Zaheer-10/Topic-Modleing-With-Latent-Dirichlet-Allocation/blob/main/Images/Topic_modeling_image.png?raw=true)
# Installation/Prerequisites
To run this project, you will need to install the following Python packages:

- numpy
- pandas
- spacy
- gensim
- sklearn

You can install them using pip or conda commands. For example:

`pip install numpy`
`pip install -U spacy`
`python -m spacy download en`
`import nltk`
`nltk.download('stopwords')`

# References
This project is based on the following resources:
 - A friendly introduction to LDA by Edwin Chen: `https://blog.echen.me/2011/08/22/introduction-to-latent-dirichlet-allocation`
 - A tutorial on LDA by David Blei: `http://www.cs.columbia.edu/~blei/papers/Blei2012.pdf`
 - A Python library for LDA by Radim Rehurek: `https://radimrehurek.com/gensim/models/ldamodel.html`
 - Vedio Ref - `https://youtu.be/T05t-SqKArY`
 - Vedio-Ref : `https://youtu.be/BaM1uiCpj_E`
    
 # LDA Workflow
 ![alt text](https://github.com/Zaheer-10/Topic-Modleing-With-Latent-Dirichlet-Allocation/blob/main/Images/lda-workflow.png?raw=true)

# FAQ
Some frequently asked questions about this project are:

- What is topic modeling?
Topic modeling is a technique to extract hidden topics from large volumes of text. It is an unsupervised machine learning algorithm that assumes that each document is a mixture of topics and each topic contains a set of words with certain probabilities.

- What is latent dirichlet allocation?
Latent dirichlet allocation (LDA) is one of the most popular methods for topic modeling. It uses a probabilistic model to capture the information in a given collection of documents. It assigns each word in a document to a topic based on two factors: how prevalent is that word in that document, and how prevalent is that word in that topic.

# How to run this project?
To run this project, you will need to follow these steps:

1. Download or clone this repository.
2. Install the required packages.
3. Load and preprocess the data using spacy.
4. Train the LDA model using gensim or sklearn.
5. Evaluate the model using perplexity and coherence scores.
6. Visualize the topics and their keywords using pyLDAvis.

# Link to My Blog : 
`https://medium.com/@soulofmercara10/topic-modeling-with-lda-505151fdffec`

