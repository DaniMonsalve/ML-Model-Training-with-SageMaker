# Machine Learning Project Implementation Using AWS Sagemaker

This project demonstrates how to train a Machine Learning model using Amazon Sagemaker.
The objective is to generate a model capable of predicting the total weight of an airplane before takeoff ("PesoTotalTARGET"). To achieve this, I have a list of completed flights along with a series of relevant variables.

# CONFIGURACIÓN Y RESULTADOS OBTENIDOS:
1- Create an IAM User and Provide Administrator Access:

.

2- Configure AWS CLI with Access Keys:

.

3- Create a work folder with a new Environment and Install requirements.txt:

.

4- Create an S3 Bucket (bucketsagemaker-ia):

.

5- Connect to the S3 Bucket:

.

6- Load train and test data into the S3 Bucket:

.

7- Start training:

.

8- New buckets generated:

.

9- Trained model generated with Testing Reports:

.


# Notes:
Train.csv contains the original dataset, before adapting the data to a normalized format.

test-V-1 and train-V-1 contain the normalized information used to train the ML model.

model.tar.gz contains the trained model, ready to be deployed.