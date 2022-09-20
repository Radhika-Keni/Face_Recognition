# Face Recognition 
Build a Face Recognition Model


## Objective of this notebook
- The purpose of this notebook is to build a Face Recognition model 
- The objective is to recognise whether two given faces are of the same person or not.
- Details of the **problem statement**  , **data set** ,  **summary of the code/solution**  , **sample output/Prediction** from the program and **final result** of the project are listed in the sections to follow.

## Problem Statement 
Computer Vision can be used to "Recognise" faces and this is used to establish a person's identity.It is useful in multiple domains right from a "Face ID" security in smart phones to policing & national Security.


## Data Description:
-The dataset comprises of images and its mask where there is a human face
-Face Aligned Face Dataset from Pinterest. This dataset contains 10,770 images for 100 people. All images are taken from 'Pinterest' and aligned using dlib library. 

## Domain:
  Entertainment

## Summary of the Solution/Code:
The code aims at building a  CNN model and obtaining embedding vectors from the same.
- We begin by doing an Exploratory Data analyses and Visualisation on the images 
- We then do the required pre-processing for the data to make it compatible with the model to be built.
- We then move on to Model building where we build the VGGFace model pretrained specifically for face recognition and generate embedding vectors from the same by running the images over it.
-Distance between the embedding vectors is used to idetify whether the two images belong to the same person or a different person and this is the main ask for the face recognition model.
-As an  "additional ask ", we also perform a "classification" on the faces to label them with names using SVM.
-Refer **python worksheet  Project_P2_FaceRecognition.pynb for the solution **

## Sample Ouput/Prediction :
Here is a sample result/output from the program/model 


![image](https://user-images.githubusercontent.com/68383273/191279777-2953d8aa-59b8-409d-b142-ce4997aff025.png)



![image](https://user-images.githubusercontent.com/68383273/191280099-12d497cf-ac65-4b5c-a9b2-5f28a130613a.png)


![image](https://user-images.githubusercontent.com/68383273/191280230-fa89ac88-e84b-4029-829e-2cdd0a05f9af.png)



## Result
- This model was able to accurately recognize faces(Celebrity faces in this case)

