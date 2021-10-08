# Cotton-Disease-Prediction


## Table of Content
  * Demo
  * Overview
  * Motivation
  * Data Collection
  * Random Forest
  * Deployement on Heroku
  * Installation and Run 
  * Future scope of the project
 
## Linkdin Profile
For any queries regarding about this project contact me

Link : https://www.linkedin.com/in/anil-l-b023631b6/

## Demo

https://user-images.githubusercontent.com/71332138/136520856-67c28702-1462-4e5a-96fa-57f149c5a2dd.mov


Project output demo Link: []

## Overview
I developed “🌿Cotton Plant Disease Prediction & Get Cure App” using Artificial Intelligence especially Deep learning. As Farmer, I know Farmer can’t solve Farm’s complex and even small problems due to lack of perfect education. So as AI enthusiastic I decided to solve this problem using the latest technology like AI.

I just took baby step and start to collect lots of images of cotton crop plants from my farm. To collect accurate data we need expertise in that domain and as a farmer it help me a lot.

Then I decide which algorithm is best to solve this problem and I select Transform Learning “Resnet” . I create my own Resnet architecture and it works well on the training and as well as testing dataset.

## Motivation
What to do when you are at home due to this pandemic situation? I started to learn Machine Learning model to get most out of it. I came to know mathematics behind all supervised models and unspurervised models. Finally it is important to work on application (real world application) to actually make a difference. To get a experience you have to work thats the reason to perform my favourable work done.


## Data Collection 
Movie dataset Extracted the Dataset from the Kaggle you can also extract the data from this link is given my main ipnyb file, Kaggle is an Open source and have a large community also they conduct competitions every month,Kaggle allows users to find and publish data sets, explore and build models in a web-based data-science environment, work with other data scientists and machine learning engineers, and enter competitions to solve data science challenges,Given the thousands of other people also doing them, it is becoming harder and harder for merely working through them to be enough to differentiate you. You'll learn a lot, but it won't make you stand out from your competition.Data scientists of all levels can benefit from the resources and community on Kaggle. Whether you are a beginner, looking to learn new skills and contribute to projects, an advanced data scientist looking for competitions, or somewhere in between, Kaggle is a good place to learn

## Random Forest(99% Accuracy)

Introduction
Random forest is a Supervised Machine Learning Algorithm that is used widely in Classification and Regression problems. It builds decision trees on different samples and takes their majority vote for classification and average in case of regression.

One of the most important features of the Random Forest Algorithm is that it can handle the data set containing continuous variables as in the case of regression and categorical variables as in the case of classification. It performs better results for classification problems.

Real Life Analogy
Let’s dive into a real-life analogy to understand this concept further. A student named X wants to choose a course after his 10+2, and he is confused about the choice of course based on his skill set. So he decides to consult various people like his cousins, teachers, parents, degree students, and working people. He asks them varied questions like why he should choose, job opportunities with that course, course fee, etc. Finally, after consulting various people about the course he decides to take the course suggested by most of the people.

Working of Random Forest Algorithm
Before understanding the working of the random forest we must look into the ensemble technique. Ensemble simply means combining multiple models. Thus a collection of models is used to make predictions rather than an individual model.

### Important Features of Random Forest
1. Diversity- Not all attributes/variables/features are considered while making an individual tree, each tree is different.
2. Immune to the curse of dimensionality- Since each tree does not consider all the features, the feature space is reduced.
3. Parallelization-Each tree is created independently out of different data and attributes. This means that we can make full use of the CPU to build random forests.
4.  Train-Test split- In a random forest we don’t have to segregate the data for train and test as there will always be 30% of the data which is not seen by the decision tree.
5.  Stability- Stability arises because the result is based on majority voting/ averaging.


Deep Explanation of Random forest(Good Content) : https://www.analyticsvidhya.com/blog/2021/06/understanding-random-forest/



## Streamlit Framework
Streamlit is an open-source Python library that makes it easy to create and share beautiful, custom web apps for machine learning and data science. In just a few minutes you can build and deploy powerful data apps, We use the streamlit to develop the API for this project

Streamlit Tutorial : [https://streamlit.io/]

## Deployement on Heroku
Once the model has good accuracy, we deploy the model either in the cloud or Rasberry py or any other place. Once we deploy, we monitor the performance of the model.if its good...we go live with the model or reiterate the all process until our model performance is good.
It's not done yet!!!
What if, after a few days, our model performs badly because of new data. In that case, we do all the process again by collecting new data and redeploy the model.

Heroku is a container-based cloud Platform as a Service (PaaS). Developers use Heroku to deploy, manage, and scale modern apps. Our platform is elegant, flexible, and easy to use, offering developers the simplest path to getting their apps to market.



Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually deploy this project.

[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)


## Screenshots of Project


--------------------------------------------------------------------------------------------------------------------------------------------------------------
![Screenshot 2021-10-03 at 10 13 53 PM](https://user-images.githubusercontent.com/71332138/135763968-ad9547cf-8916-448b-b20b-798240d17f20.png)


---------------------------------------------------------------------------------------------------------------------------------------------------------------
![Screenshot 2021-10-03 at 10 15 10 PM](https://user-images.githubusercontent.com/71332138/135763970-1697a694-7f4b-4022-b614-96196e921c01.png)


-------------------------------------------------------------------------------------------------------------------------------------------------------------
![Screenshot 2021-10-03 at 10 15 17 PM](https://user-images.githubusercontent.com/71332138/135763972-a4f11957-4a67-4001-a493-4ca563ca1f37.png)


## Installation and Run
The Code is written in Python 3.9 If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:

Install Required Libraries

     Step 1: pip install -r requirements.txt
     
Running Project

     Step 2: Streamlit run app.py

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)  ![pandas](https://user-images.githubusercontent.com/71332138/134156736-9dcc4675-e588-42a6-9481-816ac08654ab.png). ![nltk](https://user-images.githubusercontent.com/71332138/134540164-b00fafda-ccde-49ce-a5c5-3019a856f860.png) 

![blog sklearn](https://user-images.githubusercontent.com/71332138/134540412-a009eb7d-f4fa-412f-bc1a-a5c89ba74aa4.png). ![numpy](https://user-images.githubusercontent.com/71332138/134540645-95fa9566-18ca-4719-8cc6-82153e96683c.png) 
                               ![streamlit](https://user-images.githubusercontent.com/71332138/134540838-49dda9c6-3cf8-4695-be7b-5af1aff6e394.png)


## Deploy Heroku tutorial video link :

[https://www.youtube.com/watch?v=IWWu9M-aisA]
 
## Future Scope

* Optimize Streamlit app.py
* Some Features want add
* Front-End 



I developed “🌿Cotton Plant Disease Prediction & Get Cure App” using Artificial Intelligence especially Deep learning. As Farmer, I know Farmer can’t solve Farm’s complex and even small problems due to lack of perfect education. So as AI enthusiastic I decided to solve this problem using the latest technology like AI.

I just took baby step and start to collect lots of images of cotton crop plants from my farm. To collect accurate data we need expertise in that domain and as a farmer it help me a lot.

Then I decide which algorithm is best to solve this problem and I select as usual you know “Convolution Neural Network” (CNN). I create my own CNN architecture and it works well on the training and as well as testing dataset.

It gives me more than 98% accuracy on training and validation data set in just 500 epochs. I am trying to increase accuracy with more data and epochs.

After that I have deployed this model on AWS cloud. Please have look


## Tools / IDE
I used Jupyter NoteBook (Google Colab) for model training. used spyder for model deployment on the local system. To use Jupyter NoteBook and Spyder, just install anaconda.

Software Requirments
Python == 3.7.7
TensorFlow == 2.1.0
Keras == 2.4.3
NumPy == 1.18.5
Flask == 1.1.2

![Screenshot 2021-10-07 at 11 17 47 PM](https://user-images.githubusercontent.com/71332138/136440157-0381d568-bdf8-43a1-b65b-cc46034700d0.png)
![Screenshot 2021-10-07 at 11 18 05 PM](https://user-images.githubusercontent.com/71332138/136440173-a208913b-20e8-41ce-aa2d-b9835d89592f.png)
![Screenshot 2021-10-07 at 11 18 12 PM](https://user-images.githubusercontent.com/71332138/136440175-2558f401-538e-475a-b4c1-e72c3be120de.png)
![Screenshot 2021-10-07 at 11 18 23 PM](https://user-images.githubusercontent.com/71332138/136440178-fadd1176-ca4b-4aea-8ffb-90f7bb3e2dcf.png)
![Screenshot 2021-10-07 at 11 18 33 PM](https://user-images.githubusercontent.com/71332138/136440180-83ccb370-4aa9-4cab-a7a6-a2a23ae242a1.png)
![Screenshot 2021-10-07 at 11 18 43 PM](https://user-images.githubusercontent.com/71332138/136440187-2828f15b-45dd-4932-9d6d-5a98f0b008e1.png)
