# AWS-AmazonSagemaker
### Sagemaker is very much popular used in many industries who are specifically using AWS cloud using this one you will be able to build, train and deploy your machine learning and even create end points and expose all those end points so that any application can probably use it

# Steps
## 1. Firstly create AWS account 
Building and training of machine learning models can be done through two things first one is notebook instance and the second one is amazon sagmaker studio

## 2. Login to your AWS account 
Search for sagmaker in the search bar
## 3. Create notebook instance
Give appropriate project name, select notebook instance type like m1.t2.medium, select elastic inference (means selecting the GPUs), create one IAM role where we have two options any s3 bucket and specific s3 bucket select the essential option as per your requirement then click on create notebook instance.
## 4 . Setting up jupyter notebook in the local machine
Then from created notebook instance click on jupyter notebook link then notebook will option automatically then from notebook itself select environment like conda_python3 for machine learning
## 5. Start executing the code written in the notebook given below
Source:- [Notebook](https://github.com/MANMEET75/AWS-AmazonSagemaker/blob/main/Notebook.ipynb)
Importing the essential libraries, creating the S3 bucket, mapping training and testing data in s3 bucket and mapping the path of the models in the s3 bucket

Enjoy Coding !!

