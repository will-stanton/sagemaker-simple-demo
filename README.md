# sagemaker-simple-demo
Simple demo of using a Sagemaker Studio notebook to train a model and deploy an API endpoint. This is based on the great [AWS Sagemaker Jumpstart notebook](https://github.com/aws/amazon-sagemaker-examples/blob/main/introduction_to_amazon_algorithms/linear_learner_mnist/linear_learner_mnist.ipynb) but uses the `iris` dataset instead of `mnist`. I also removed some steps to make it as minimal of an example as possible for learning purposes. If you are trying to learn Sagemaker, this notebook demonstrates a few critical pieces that are specific to Sagemaker:

1. The usage of a Sagemaker "Session" and a Sagemaker execution role
2. Converting training data to recordIO-wrapped protobuf format
3. Deploying an endpoint
