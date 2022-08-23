# P6_DUCHEMIN_Marin

In this project, we will study the feasability of an automatic goods classifier for a fictive e-shop. 

The classification will be based on one image and one short description of the product. 

For the text part, we will pre-process the text (tokenisation, lemmatisation, stop words suppression, etc) thanks to nltk and gensim. We will then visualize the groups with clouds of words, and vectorize them with several NLP techniques (tf-idf, continuous bags of words, Skip-Gram method). The classification will then be tried with supervized techniques (Naive Bayes, Random Forest, Recurrent Neural Network).

For the images, we will pre-process them (greyscaling, contrast and brightness optimization, noise canceling) with OpenCV. Thanks to the ORB method, we will vectorize the images and use K-means clustering to make some kind of ID card of each images. The classification will then be tried sur supervized techniques again (Linear SVC and Convolutional Neural Network).
