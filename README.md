## Spam email classification using NLP techniques
These 5 notebooks demonstrates the various steps in an ML pipeline for an email spam classification solution

### non_sagemaker_pipeline notebook

 * Performs data loading, pre-processing, training, prediction and performance measurement without using SageMaker services. Different NLP techniques such as BOW, TF-IDF and word embeddings are explored.

### data_loading notebook

 * Downloads the Enron Spam dataset from http://nlp.cs.aueb.gr/software_and_datasets/Enron-Spam/ and formats it for pre-processing.

### data_processing notebook

 * Performs - text cleanup, tokenization, lemmetization , formatting for BlazingText input, spliting the data set for training and testing.

### training_deploying notebook

 * Trains a model using SageMaker's BlazingText algorithm. Deploys the trained model to a SageMaker endpoint

### prediction notebook

 * Evaluates model performance using the test data set.
