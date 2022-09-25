# sagemaker-simple-demo
Simple demo of using a Sagemaker Studio notebook to train a model and deploy an API endpoint. This is based on the great [AWS Sagemaker Jumpstart notebook](https://github.com/aws/amazon-sagemaker-examples/blob/main/introduction_to_amazon_algorithms/linear_learner_mnist/linear_learner_mnist.ipynb) but uses the `iris` dataset instead of `mnist`. I also removed some steps and made the code *less sophisticated* in a couple places to make it as minimal of an example as possible. If you are trying to learn Sagemaker, this notebook demonstrates a few critical pieces that are specific to Sagemaker:

1. The usage of a Sagemaker "Session" and a Sagemaker execution role
2. Converting training data to recordIO-wrapped protobuf format
3. Defining an input S3 data location and an output S3 location
4. Deploying an endpoint

These steps can be a bit confusing when you're just starting, but they do help Sagemaker be tightly integrated with other AWS services and also help with scalability.