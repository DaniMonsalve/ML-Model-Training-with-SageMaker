# Machine Learning Project Implementation Using AWS Sagemaker

This project demonstrates how to train a Machine Learning model using Amazon Sagemaker.
The objective is to generate a model capable of predicting the total weight of an airplane before takeoff ("PesoTotalTARGET"). To achieve this, I have a list of completed flights along with a series of relevant variables.

# CONFIGURACIÓN Y RESULTADOS OBTENIDOS:
1- Create an IAM User and Provide Administrator Access:

  <img width="942" alt="IAM USER (ADMINISTRATIVE ASCCESS)" src="https://github.com/user-attachments/assets/2cd7bf44-c06c-4329-bca0-9af7fb8d99e7">


2- Configure AWS CLI with Access Keys:

  <img width="557" alt="AWS CLI CONFIGURE" src="https://github.com/user-attachments/assets/fa2ca470-b99b-4370-a804-dadf68beeafd">

3- Create a work folder with a new Environment and Install requirements.txt:

  <img width="956" alt="install requirements txt" src="https://github.com/user-attachments/assets/1f17e59f-b2eb-4118-908d-7212312c2a9f">


4- Create an S3 Bucket (bucketsagemaker-ia):

  <img width="955" alt="create bucketsagemaker-ia" src="https://github.com/user-attachments/assets/8c86331c-ba55-4562-b1ae-95212af4f77d">


5- Connect to the S3 Bucket:

  <img width="710" alt="Conect to S3 bucket" src="https://github.com/user-attachments/assets/ce3d7bb5-c9ad-4d0f-8902-d7ec3e6684b2">


6- Load train and test data into the S3 Bucket:

  <img width="673" alt="Load data into S3 bucket" src="https://github.com/user-attachments/assets/f374b1d9-fe14-46e7-95ae-7069e9ae5953">


7- Start training:

  <img width="955" alt="Start training" src="https://github.com/user-attachments/assets/7c3220e1-7415-448e-93f2-2ccb1d004666">


8- New buckets generated:

  <img width="739" alt="Generated buckets" src="https://github.com/user-attachments/assets/1c3d0067-3ef5-4d13-bf96-f5e7fd79f68d">

9- Trained model generated with Testing Reports:

  <img width="960" alt="Trained model generated" src="https://github.com/user-attachments/assets/975521c3-4058-4dfc-ae29-a38731a30a91">

  
  !! Considerations:
  
  Overfitting: Perfect performance can be a sign of overfitting, especially if the training data is limited or if the model is complex. It is advisable to evaluate the model with an additional validation set or to perform cross-validation.
  
  <img width="578" alt="results" src="https://github.com/user-attachments/assets/55ffda30-c8b1-418f-8471-d280f301c5f4">



# Notes:
Train.csv contains the original dataset, before adapting the data to a normalized format.

test-V-1 and train-V-1 contain the normalized information used to train the ML model.

model.tar.gz contains the trained model, ready to be deployed.
