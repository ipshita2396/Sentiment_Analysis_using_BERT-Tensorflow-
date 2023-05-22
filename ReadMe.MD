**Objective**

To perform text classification on retail /movie review dataset and classifying the text as negative or positive  using bert and tensorflow machine learning algorithm .

The major operations that need to be performed are:

1. Tokenization using bert 
2. Generating word embedding / vectorization using bert 
3. Model building using tensorflow 

**Data Preparation**

Data Set : IMDB movie dataset from kaggle  

- The dataset contains 10000 rows and 2 columns namely [‘reviews’ ,’ sentiments’] 
- Value of sentiment columns: Positive and Negative 

**Data Preprocessing**

Following techniques were used to preprocess the data 

1.Removal of tags using regex
2.Removal of stop words using nltk library 
3.Removal extra spaces and special characters using regex
4.Converting the text to lower cases 

**Tokenization and Vectorization**

**Tokenization** : Tokenization is breaking the raw text into small chunks. Tokenization breaks the raw text into words, sentences called tokens.Tokenization with Bert To perform sentiment analysis on movie reviews , bert tokeizer from tensorflow was used 
1. Tokenization was performed 
2. Converting the tokens to id 

**Vectorization**: Word Embeddings or Word vectorization is a methodology in NLP to map words or phrases from vocabulary to a corresponding vector of real numbers which used to find word predictions, word similarities/semantics.

Vectorization with Bert: To perform sentiment analysis on movie reviews , bert  from simple transformer library was used  .

**Contextual Embedding**

Contextual embeddings assign each word a representation based on its context, thereby capturing uses of words across varied contexts and encoding knowledge that transfers across languages.
Contextual embedding methods are used to learn sequence-level semantics by considering the sequence of all words in the documents. Thus, such techniques learn different representations for polysemous words.
Eg "I left my phone on the left side of the table."


**Model Building**
Selected Model : bert_en_uncased using Tensorflow Hub

BERT, or Bidirectional Encoder Representations from Transformers, is a new method of pre-training language representations which obtains state-of-the-art results on a wide array of Natural Language Processing tasks.
BERT  Transformer uses encoder architectures .They compute vector-space representations of natural language that are suitable for use in deep learning models. The BERT family of models uses the Transformer encoder architecture to process each token of input text in the full context of all tokens before and after, hence the name: Bidirectional Encoder Representations from Transformers.

**Reason for selecting BERT** : BERT models are usually pre-trained on a large corpus of text ,fine tuning it can much easier , as they have initial pre trained weights .





