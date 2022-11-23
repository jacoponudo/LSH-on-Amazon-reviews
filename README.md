# LSH on Amazon reviews
Project of Big Data Computing to handle the task of find similar pairs of documents in a massive dataset.
This project is about apply a dimentionality reduction, using Local Sensitive Hashing on Amazon reviews. 
Give the size of data we are pushed to spply a sort of reduction to evaluate is there are similar (or cluster os documents) so staring from the enteir text I've performe a preprocessing and a Tf-IDf to reppresent them as vectors in a multidimentional space. 
To reach a good signature matrix I've transformed the Tf-IDf matrid using the Hypoerplanes method with size of 900 that could lead to a defenely better usage of this vector. Then with hash functions for each ban we produce a bucket key, that will open a bucket in which we will find all the similar (due to the approximation) documents.
