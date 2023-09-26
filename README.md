This repository contains a pre-work of generating adversarial samples of network traffic.

Adversarial samples in this repository are in feature space,this means adversarial samples are feature vectors.

I use JSMA method, CICIDS2017 dataset and pre trained MLP model(implemented in Keras) to generate adversarial samples.

These samples are generated to cause the model to misclassify.Further,adversarial examples should be expanded into traffic space，which means that samples shoud be real network traffic rather than
feature vectors.
