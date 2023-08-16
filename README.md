# Open-book-question-answering

This project implements open book question answering system. This system has two components namely retreiver and generator. 

Given the query, the retriever will retrive the relevant documents for the query. These documents are feds as context to the generator model for answer generation.
In this work, dense passage based retriver is used by longformer BART model for question answering. The architecture is used for question - answering for Pharma applications. 
For this purpose, all the patents from 2000 was extracted from google patents using request and beautiful soup. Further text cleaning was done to extract only english contents as many patents are in other languages. Further tables, equation and figure data is removed from the text.
