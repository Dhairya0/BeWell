# Medical_Diagnosis |  A Machine Learning Based Web Application

![Pyhon 3.4](https://img.shields.io/badge/ide-Jupyter_notebook-blue.svg) ![Python](https://img.shields.io/badge/Language-Python-brightgreen.svg)  ![Frontend](https://img.shields.io/badge/Frontend-Bootstrap-purple.svg)  ![Frontend](https://img.shields.io/badge/Libraries-Streamlit-purple.svg)    ![Bootstrap](https://img.shields.io/badge/BaseEnvironment-AnacondaPrompt-brown.svg)   ![Bootstrap](https://img.shields.io/badge/Deployment-Github-yellow.svg)   ![Bootstrap](https://img.shields.io/badge/Debugging-LocalHost-blue.svg)  

## Table of Content
  * [Problem statment / Why this topic?](#Problem-statment)
  * [Flow Chart / Archeticture](#Flow-chart)
  * [Directory Tree](#directory-tree)
  * [Quick start](#Quick-start)
  * [Screenshots](#screenshots)
  * [Technical Aspect](#technical-aspect)
  


  
## Problem Statment
The proposed project would be very useful in the medical field. In the proposed project a machine learning- based web application would be created for medical diagnosis. For a medical diagnosis, a machine learning model would be developed and integrated with the created web application. The user would be able to upload his medical data on the web application. The web application would pass this data to a developed machine learning model for health disease detection. After detection of health disease, if the person wants to take advice from a doctor then he can fix the appointment on the web application. A chat(Email) option would be provided on the web application to provide the communication between the patient and the doctor.

## Why this Project?
Although, we know that humans can do the mistakes but machines doesnt. Plus we can check the predicted outcome accuracy with machine learning. So we go for Machine learning, Keeping this in mind we researched alot in the allopathic, homeopathy and ayurvedic data. Due to less research paper for the data set of patients in homeopathy and ayurvedic we go for allopathic data set that are avalible in Kaggle and UCI machine learning portals.
  
  
## Flow chart
Front-end UX/UI, Back-end Machine learning, Deep learning flow chart
  

![ml](https://user-images.githubusercontent.com/62024355/120781058-4fac3300-c546-11eb-83be-dfc8319fd2f3.png)
  
  
  
  
## Directory Tree 
```
├── Pyhon notebooks code files
├── trained models.pkl file
├── static logos
├── Templates
│   ├── Home.html
│   ├── contact.html
│   ├── about us.html
│   ├── services.html
│   ├── css folder
│   ├── js folder
│   ├── images folder
│   └── fonts folder
│         ├── Diabetes
│         ├── Breast Cancer
│         ├── Heart Disease
│         ├── Kidney Disease
│         ├── Liver Disease
│         ├── Malaria
│         └── Pneumonia
├── app.py
├── readme.md
├── runtime.txt
└── requirements.txt


```

  
  
  
## Quick start
  
**Step-1:** Download the files in the repository.<br>
**Step-2:** Get into the downloaded folder, open command prompt in that directory and install all the dependencies using following command<br>
```python
pip install -r requirements.txt
```
**Step-3:** After successfull installation of all the dependencies, run the following command<br>
```python
python app.py
```

```python
or
flask run
```
**Step-4:** Go to the __New command prompt__ of root folder, run the following commands in new cmd terminal<br> 
```
cd templates
index.html
```



  
## Screenshots


![g1](https://user-images.githubusercontent.com/62024355/120784738-09f16980-c54a-11eb-8742-daca4ada33b0.jpg)
![g2](https://user-images.githubusercontent.com/62024355/120784742-0a8a0000-c54a-11eb-81a3-daee8b1eafd8.jpg)
![g3](https://user-images.githubusercontent.com/62024355/120784744-0b229680-c54a-11eb-9596-d324a25a192a.jpg)
![g4](https://user-images.githubusercontent.com/62024355/120784746-0bbb2d00-c54a-11eb-9365-df3172efcde1.jpg)
![g5](https://user-images.githubusercontent.com/62024355/120784749-0bbb2d00-c54a-11eb-9d8a-3f4b53b9f208.jpg)
![g7](https://user-images.githubusercontent.com/62024355/120784730-078f0f80-c54a-11eb-8c37-dffa48791db5.jpg)
![Untitled1](https://user-images.githubusercontent.com/62024355/120785797-1cb86e00-c54b-11eb-8323-47ab1312e6d6.png)
  
  

## Technical aspect

This webapp was developed using Flask Web Framework. The models used to predict the diseases were trained on large Datasets. All the links for datasets and the python notebooks used for model creation are mentioned below in this readme. The webapp can predict following Diseases:
* Diabetes
* Breast Cancer
* Heart Disease
* Kidney Disease
* Liver Disease
* Malaria
* Pneumonia

__Models with their Accuracy of Prediction__

Disease | Type of Model | Accuracy
--- | --- | ---
Diabetes | Machine Learning Model | 98.25%
Breast Cancer | Machine Learning Model | 98.25%
Heart Disease | Machine Learning Model | 85.25%
Kidney Disease | Machine Learning Model | 99%
Liver Disease | Machine Learning Model | 78%
Malaria | Deep Learning Model(CNN) | 96%
Pneumonia | Deep Learning Model(CNN) | 95%

__NOTE__
<br>
==> Python version 3.6.8 was used for the whole project.<br>

__Dataset Links__
All the datasets were used from kaggle.
* [Diabetes Dataset](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
* [Breast Cancer Dataset](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data)
* [Heart Disease Dataset](https://www.kaggle.com/ronitf/heart-disease-uci)
* [Kidney Disease Dataset](https://www.kaggle.com/mansoordaku/ckdisease)
* [Liver Disease Dataset](https://www.kaggle.com/uciml/indian-liver-patient-records)
* [Malaria Dataset](https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria)
* [Pneumonia Dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)


__Links for Python Notebooks used for model creation__
* [Diabetes Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Diabetes_Prediction.ipynb)
* [Breast Cancer Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Cancer_Prediction.ipynb)
* [Heart Disease Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Heart_Disease_Prediction.ipynb)
* [Kidney Disease Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Kidney_Disease_Prediction.ipynb)
* [Liver Disease Notebook](https://github.com/venugopalkadamba/Multi_Disease_Predictor/blob/master/Python%20Notebooks/Liver_Disease_Prediction.ipynb)

Contributors: 
[Krupal Parmar](https://github.com/krupalparmar7),
[Dhairya Gajjar](https://github.com/Dhairya0)
