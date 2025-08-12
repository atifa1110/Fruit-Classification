# Fruits Image Classification

![Fruits Image Classification](https://private-user-images.githubusercontent.com/49097275/477054193-f4ee346f-60df-41df-a227-4fa69d68797c.jpg?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTUwMDI4MzAsIm5iZiI6MTc1NTAwMjUzMCwicGF0aCI6Ii80OTA5NzI3NS80NzcwNTQxOTMtZjRlZTM0NmYtNjBkZi00MWRmLWEyMjctNGZhNjlkNjg3OTdjLmpwZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTA4MTIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwODEyVDEyNDIxMFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWMxYzIxY2U3M2ZmYmIyMjZiMDdkYTE1NjgzYjVlYTc0YjQxMTA3ZGQ0ODhlNmE2ZDkyZmQ4ZDNlNjQ3ZTM5ZTgmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.ooDriSIlOrgqXzPl633aLXiLNjEYcsSXnbsJeup5BTk)

## Background:
Image recognition is a major field within machine learning and computer vision. Thanks to technological advances, the image classification process has become easier and can be applied across various sectors, ranging from security systems to healthcare services. This project focuses on fruit image classification to understand the application of deep learning models in distinguishing different types of fruits.

## Business Problem:
In the retail and food industries, the ability to automatically recognize fruits greatly helps optimize processes such as sorting, packing, and quality control of fruits. Automation reduces human errors, increases productivity, and lowers operational and labor costs for companies.

## Project Objectives:
1. Develop an image classification model capable of identifying various fruit types with high accuracy.
2. Save the model in multiple formats compatible with different platforms and devices.
3. Apply deep learning to improve image classification accuracy.

## Project Scope:
1. Search for a dataset
2. Split the dataset into 80% training set and 20% test set
3. Use a Sequential model with Conv2D and pooling layers
4. Plot model accuracy and loss graphs
5. Save the model in SavedModel, TF-Lite, and TFJS formats
6. Implement callbacks
7. Perform inference using one of the models (TF-Lite, TFJS, or SavedModel with TensorFlow Serving).

## Dataset
Dataset is obtained from Kaggle’s <a href="https://www.kaggle.com/datasets/moltean/fruits" target='_blank'>Fruits Dataset</a>, which contains 5 folders:

1. fruits-360_100x100
2. fruits-360_3-body-problem
3. fruits-360_dataset_meta
4. fruits-360_multi
5. fruits-360_original-size

For this project, only the **fruits-360_100x100** folder is used. This dataset contains 207 classes.

1.  Recommended to run on Google Colab
    - Upload the file [Deep Learning]_Submission_Klasifikasi_Gambar_Atifa_Fiorenza.ipynb to Google Colab
    - Adjust or customize the existing code as needed
    - Run run all on the project

2. If running locally
    - Make sure you are connected to the internet to install required modules (libraries)
    - Open cmd or PowerShell as administrator

    ```bash
    pip install -r requirements.txt
    ```
    - Open File `[Deep Learning]_Submission_Klasifikasi_Gambar_Atifa_Fiorenza.ipynb` tp Google Colab 
    - Adjust or customize the existing code as needed
    - Do **run all** in project

 ## Conclusion
- Based on experiments, the results are:
    - Model              : Sequential
    - Train Accuracy     : 96%
    - Test Accuracy      : 98%
- The model is able to predict fruit images inputted through inference.

## Suggestions
- Further experiments using other pretrained models in this project (e.g., VGG, ResNet, etc.)
- Conduct additional experiments using the original and multi datasets
  
