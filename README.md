# ArtificialIntelligence

Project: Plagiarism Checker

This project aims to build a simple plagiarism checker based on vector space model. 
In vector space model, The documents are pre-processed to generate terms. 
The documents are represented as vectors containing weights of these terms using tf-idf weighting schemes . 
When an input file is given to the checker, a vector is made from its terms and similarity between all the documents is found. 
The percentage of similarity is calculated using cosine similarity.
