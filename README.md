# News-Classification
This is an implementation of news classification program, which has been trained with headlines and short description of 37 categories of news.
The program uses the fastAi library for training and further classification. 
First, a language model is created (out of AWD LSTM trained on Wiki-103 dataset) and then after fine tuning and creating a vocabulary, classifier is implemented.
