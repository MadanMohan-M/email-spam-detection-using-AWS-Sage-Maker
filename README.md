# email-spam-detection-using-AWS-Sage-Maker
This project demonstrates how to build an NLP-based email spam classifier using traditional machine learning techniques and deploy it using Amazon SageMaker. The model uses TF-IDF vectorization and Logistic Regression, and it is deployed for real-time inference using a SageMaker endpoint.
Importing Libraries
pandas, numpy, sklearn, re, boto3, sagemaker, etc.

Data Loading & Preprocessing

Read email dataset

Clean and normalize text (lowercasing, removing special characters, etc.)

Apply TF-IDF Vectorization

Model Building

Train a Logistic Regression model

Evaluate using F1 Score, Precision, and Recall

Train-Test Split

Split data for training and validation using train_test_split


Model Deployment (AWS SageMaker)

Upload model artifacts to Amazon S3

Create a SageMaker estimator

Deploy the model as an endpoint

Real-time Inference

Pass sample email strings

Get predictions from the deployed endpoint

 Technologies Used
 
Python

scikit-learn

Amazon SageMaker

Amazon S3

TF-IDF Vectorizer

Logistic Regression
Boto3
