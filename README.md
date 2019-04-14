# Deep Learning Udacity Nanodegree - SageMaker Deployment Project


This is the final solution of the project 'Sagemaker Deployment' which consists in deploying a Sentiment Analysis model using RNN in the Amazon AWS SageMaker tool. The notebook and Python files provided here result in a simple web app which interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews.

In the final architecture AWS API Gateway and AWS Lambda functions is used as well. The application architecture diagram is:

![Web app Diagram](./Web&#32;App&#32;Diagram.svg) 

You can find the original code without solutions in the original [Udacity SageMaker Deployment repository](https://github.com/udacity/sagemaker-deployment).

 This project assumes some familiarity with SageMaker, the IMDB Sentiment Analysis using XGBoost mini-project (which can be found in the original repository) should provide enough background.


## Setup instructions
Please see the [original README](https://github.com/udacity/sagemaker-deployment/tree/master/README.md) in the root directory for instructions on setting up a SageMaker notebook and downloading the project files (as well as the other notebooks). For the solutions only clone this repository:

```
cd SageMaker
git clone https://github.com/hjlopes/sagemaker-sentiment-analysis
exit
```

## Web app final result

The final project will be executed in a simple html page which can be deployed anywhere. 

You will see the following:

![Web app example](./webapp.gif) 
