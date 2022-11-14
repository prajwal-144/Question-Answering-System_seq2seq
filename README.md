# Question Answering System

Question answering is a critical NLP problem and a long-standing artificial intelligence milestone. QA systems allow a user to express a question in natural language and get an immediate and brief response. It is a computer science discipline within the fields of information retrieval and natural language processing, which is concerned with building systems that automatically answer questions posed by humans in a natural language.

![image](https://user-images.githubusercontent.com/86421205/201606759-e8f3ca35-6a4f-4e9e-a351-e0051456baf9.png)


## :hammer_and_wrench: Structure of Question Answering System
The design of a question answering system has specific vital components. There are three distinct modules used in a question-answering system:

* *Query Processing Module*: Classifies questions according to the context. This module identifies the context and focus, classifies the type of question, and sets the answer type’s expectations.
* *Document Processing Module*: Information retrieval module that focuses on gathering relevant documents.
* *Answer Processing Module*: Once the relevant documents are retrieved, they need to be parsed through to obtain an accurate and appropriate answer.

![image](https://user-images.githubusercontent.com/86421205/201607894-17939855-d72e-4052-a59f-d245972426c3.png)


## :dart: Objective
Our objective is to develop a Question Answering System using Seq2Seq approach.

![image](https://user-images.githubusercontent.com/86421205/201607055-8ff4a62d-6913-40e2-89bb-6d981d78d65c.png)


## :pencil2: Dataset
We use the SQuAD dataset for training and validating our model. Stanford Question Answering Dataset (SQuAD) is a reading comprehension dataset, consisting of questions posed by crowdworkers on a set of Wikipedia articles, where the answer to every question is a segment of text, or span, from the corresponding reading passage, or the question might be unanswerable.
_Link_ : https://rajpurkar.github.io/SQuAD-explorer/

## :pencil2: Overview of the Model
* Trained the model on a encoder-decoder architecture - Seq2Seq model using the LSTM Neural Network.
* Trained on 1500 epochs
![model](https://user-images.githubusercontent.com/86421205/201609411-64c2dae7-6a21-4a5b-ae4e-804228e647c3.png)


## :brain: Results
![Screenshot 2022-11-14 114457](https://user-images.githubusercontent.com/86421205/201609481-3a8a100e-1f52-42c5-bb1f-e5b94416c077.png)

![Screenshot 2022-11-14 114611](https://user-images.githubusercontent.com/86421205/201609531-1cacd705-7be4-421f-b09a-1e5128b83b2e.png)


## :pencil2: Future Work
* Increase the number of epochs to achieve an even greater accuracy.
* To leverage the power of GloVe to convert text into Word Embeddings and integrate the model and deploy it as a chatbot on a web host using Flask and Heroku.
