---
layout: default
title: Additional Work
nav_order: 4
---

# Know about my additional works
{: .fs-8, .no_toc}
<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

---
---
## Generative AI
{: .fs-6}
<br>
### 1. ChefGPT using OpenAI LLM Models [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/shruthipv96/ChefGPT)
<br>

- A chatbot that can understand user preferences for food recipes and provide suggestions from a pre-existing dataset.
- LLM Model : gpt-4o
  
An example conversation:

<center>
 <iframe width="920" 
         height="500" 
         src="https://github.com/shruthipv96/portfolio/assets/32814013/a270aaeb-6ed7-424c-87e6-83c3f3d95d1b" 
         title="Output" 
         frameborder="0" 
         allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
         allowfullscreen>
 </iframe>
</center>

---

### 2. ArxivConsultant using LlamaIndex [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/shruthipv96/ArxivConsultant)
<br>

This is a tool, built with LlamaIndex components, designed to assist users in retrieving and interacting with relevant research papers from the arXiv repository. It utilizes natural language processing (NLP) techniques, specifically leveraging OpenAI's GPT-3.5 model, to understand and respond to user queries about academic papers.

An example conversation:

<center>
 <iframe width="920" 
         height="500" 
         src="https://github.com/shruthipv96/portfolio/assets/32814013/23a31620-c8ab-401b-992c-76f07011d75d" 
         title="Output" 
         frameborder="0" 
         allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
         allowfullscreen>
 </iframe>
</center>

---

### 3. FashionAI using RAG model [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/shruthipv96/FashionAI)
<br>

A generative search system (RAG model) capable of searching a plethora of fashion product descriptions to find and recommend appropriate choices against a user query.

**Models Used**

| Topic | Model |
| --- | --- |
| Embedding | [nomic-ai/nomic-embed-text-v1.5](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5) |
| Cross Encoder for reranking | `ms-marco-MiniLM-L-6-v2` |
| Generative Response | `gpt-3.5-turbo` |
  
A sample output:

![Query2_GenerativeSearch](https://github.com/shruthipv96/portfolio/assets/32814013/f2785527-bcee-4dc5-a56b-a915e63f16f9)


---
---
## Neural Network
{: .fs-6}
<br>

### 1. Gesture Recognition [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/shruthipv96/GestureRecognition)
<br>

- Develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote. The gestures are continuously monitored by the webcam mounted on the TV.
- Each gesture corresponds to a specific command:
  
| Gesture | Corresponding Action |
| --- | --- | 
| Thumbs Up | Increase the volume. |
| Thumbs Down | Decrease the volume. |
| Left Swipe | 'Jump' backwards 10 seconds. |
| Right Swipe | 'Jump' forward 10 seconds. |
| Stop | Pause the movie. |

**Objective** : Build a model to recognize the above mentioned gestures with high accuracy.

---

### 2. Melanoma Detection Case Study [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/shruthipv96/MelanomaDetection)
<br>

- Build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.
- A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
  
---
---
## Data Science projects
{: .fs-6}
<br>

### 1. Lending Club Case Study [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/shruthipv96/LendingClubCaseStudy)
<br>

- Lending club company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.
- Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). There are two types of risks associated with the bank’s decision:
> - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
> - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.
- Borrowers who default cause the largest amount of loss to the lenders.

**Objective**: The aim is to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default using EDA.

---

### 2. Bike Sharing Case Study [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/shruthipv96/BikeSharingCaseStudy)
<br>

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

**The company wants to know:**
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands.

**Objective:** Build a model for the demand of shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features.

---

### 3. Sale Price of House Case Study [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/shruthipv96/SurpriseHousing)
<br>

A US-based housing company named **Surprise Housing** has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

**The company wants to know:**
- Which variables are significant in predicting the price of a house.
- How well those variables describe the price of a house.

**Objective:**
The company is looking at prospective properties to buy to enter the market. It is required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

---

### 4. Telecom Churn Case Study [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/shruthipv96/TelecomChurnCaseStudy)
<br>

In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

**Objective:**
The main goal of the case study is to build ML models to predict churn.
- It will be used to predict whether a high-value customer will churn or not, in near future (i.e. churn phase). By knowing this, the company can take action steps such as providing special plans, discounts on recharge etc.
- It will be used to identify important variables that are strong predictors of churn. These variables may also indicate why customers choose to switch to other networks.
- Recommend strategies to manage customer churn based on your observations.

---
---

## Self Driving Online Course
{: .fs-6}
<br>
The 6 month Udacity course helps to establish a knowledge on self driving cars.
<br>
<br>
### 1. Lane Detection [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/shruthipv96/CarND_Udacity_Lane_Detection)
<br>
The goal is to find the lanes on the road using camera and py-OpenCV library.

In the below video, the red lines(output) are marked  over the lane markings.

<center>
 <iframe width="920" 
         height="500" 
         src="https://github.com/shruthipv96/portfolio3/assets/32814013/618dbfe6-359f-48f7-9cb9-362941587e93" 
         title="Output" 
         frameborder="0" 
         allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
         allowfullscreen>
 </iframe>
</center>

---

### 2. Advanced Lane Detection [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/shruthipv96/CarND_Udacity_AdvancedFindingLane)
<br>
The goal is to find the lanes on the road in a more realistic environment like shadows, curves, etc.

In the below video, you can find the green area (output) indicating the lane. Additionally, the radius of curvature of the road and the offset of the vehicle from the center of the lane is also displayed.

<center>
 <iframe width="920" 
         height="500" 
         src="https://github.com/shruthipv96/portfolio3/assets/32814013/7e0f3c1f-620d-4296-b824-b3f78753ac7e" 
         title="Output" 
         frameborder="0" 
         allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
         allowfullscreen>
 </iframe>
</center>

---

### 3. Traffic Sign Classifier [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/shruthipv96/CarND_Udacity_TrafficSignClassifier)
<br>
The goal is to classify various traffic signs on the road using Neural Network which helps to make a decision about how to proceed our driving
The open source German traffic sign dataset is used to train the network.

In the below image,the test image against the top predictions by the trained ML model is shown.
<center> <img src="https://github.com/shruthipv96/portfolio3/assets/32814013/ee1912b8-2948-4961-85b8-1638814d7967"> </center>

---

### 4. Behavioural Cloning [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/shruthipv96/CarND_Udacity_BehaviouralCloning)
<br>
The goal is to clone the behaviour of our driving using deep neural network. The data was collected by driving the car by myself in the simulation.

In the below video, the car is driving by self without any user input based on the model trained. Input to model is camera feed and output from model is the steer angle. (Note: The video quality is poor because it is exported from simulation)

<center>
 <iframe width="320" 
         height="160" 
         src="https://github.com/shruthipv96/portfolio3/assets/32814013/e39c0081-c35b-46fe-86b6-4f672fd049bf" 
         title="Output" 
         frameborder="0" 
         allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
         allowfullscreen>
 </iframe>
</center>

---

### 5. Extended Kalman Filter [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/shruthipv96/CarND_Udacity_ExtendedKalmanFilter)
<br>
In reality, only the data from camera alone will not help to drive the car. We need to fuse Laser and Radar sensors to predict the position 
of the vehicle. The goal is to design a Kalman filter which can be used for both linear and non-linear models to predict the value based on input from multiple sources.

In the below image, the green triangle shows the predicted output. The blue and red circles indicate the input from Laser and Radar sensor.
<center> <img src="https://github.com/shruthipv96/portfolio3/assets/32814013/37652c1b-a11f-4a83-b7c8-ca65550ee6c3" width="640" height="480"> </center>

---
---

## Experimental Repositories
### Farming Solution

This project was developed for Hackathon to provide a smart farming solution. It includes live monitoring of soil nature (temperature, humidity from DHT-11 sensor using Raspberry Pi) and uploading into database, live billing of items in shops across the country using one central database and additional information regarding farming.
Website is run on xampp localhost server with php mySQL as backend database.

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/shruthipv96/farmingsolution)

---
---

## College Projects

| Project      | Description     | 
|:-------------|:------------------|
| Digital Power Factor Meter |The meter developed finds the power factor of the load using microcontroller(Arduino) and its interrupt function. |
| Home Automation |  A system was developed where one can control home appliances using a smart phone. |
| Networking of motors | A prototype was developed where two independent motors were synchronized at same speed using Arduino. |
| Automated Cloth Protector | A system was developed to protect the clothes on terrace from rain using Arduino. |
| LabVIEW based Robotic Arm control | A model was developed in LabVIEW interfaced with Arduino to control a two degree of freedom robotic arm |

---
---
