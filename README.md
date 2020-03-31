# Mining Claims in UNHCR reports / A2

This is the code for our project for the class Opinion and Argument Mining.

Nico Manthey
Liubov Karpova
Luise Strietzel

The task we set ourselves was to build a model that predicts claims in unlabelled data. We chose to implement the system described in the paper "Joint RNN Model for Argument Component Boundary Detection" https://arxiv.org/abs/1705.02131, though we made some adjustments.

The general computation graph of the system is to train a classifier to classify sentences with and without argument components (e.g. claims), and feed the sentences that were categorized as claims to a BIO-tagger (see image at the bottom of page). 

# Instructions to run the code

Since the files are too large, we uploaded our complete work to the following link:

www.test-page.de

The linked folder looks like this:



![](img/computation_diagram.png)







