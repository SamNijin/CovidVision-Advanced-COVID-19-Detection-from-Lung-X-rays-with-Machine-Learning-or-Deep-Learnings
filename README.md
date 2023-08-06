# CovidVision: **_Advanced COVID-19 Detection from Lung X-rays with Machine Learning or Deep Learnings_**

## Project Description:

<div style="text-align:justify">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;COVID-19 (coronavirus disease 2019) is an infectious disease caused by severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2), which is a strain of coronavirus. The disease was officially announced as a pandemic by the World Health Organization(WHO) on 11 March 2020. Given spikes in new COVID-19 cases and the re-opening of daily activities around the world, the demand for curbing the pandemic is to be more emphasized. Medical images and artificial intelligence (AI) have been found useful for rapid assessment to provide treatment of COVID-19 infected patients. The PCR test may take several hours to become available, information revealed from the chest X-ray plays an important role for a rapid clinical assessment. This means if the clinical condition and the chest X-ray are normal, the patient is sent home while awaiting the results of the etiological test. But if the X-ray shows pathological findings, the suspected patient will be admitted to the hospital for close monitoring. Chest X-ray data have been found to be very promising for assessing COVID-19 patients, especially for resolving emergency-department and urgent-care-center overcapacity. Deep-learning (DL) methods in artificial intelligence (AI) play a dominant role as high-performance classifiers in the detection of the disease using chest X-rays.

One of the biggest challenges following the Covid-19 pandemic is the detection of the disease in patients. To address this challenge we have been using the Deep Learning Algorithm to build an image recognition model that can detect the presence of Covid-19 from an X-Ray or CT-Scan image of a patient's lungs.

Transfer learning has become one of the most common techniques that has achieved better performance in many areas, especially in medical image analysis and classification. We used Transfer Learning techniques like Inception V3,Resnet50,Xception V3 that are more widely used as a transfer learning method in medical image analysis and they are highly effective.

## Technical Architecture

![Technical Architecture](https://lh5.googleusercontent.com/kaSemjH4Bg4iEK0voEax_0s585VjF5FWcd_jBjpcNwBdk98M1-r-EtVjgCuxPG0uUMZBRIFyk3PFPvM7tt39L2joJuW__nWvHoXH4AKwP3sELWHD2auu8AxfaXhgBzNMK-toJ7a6kOEo6Q8ndSchCA)

## Features or Innovation in the project

#### Transfer Learning

- The process of using the pretrained model with pretrained weights to have better performance metrics.
- This also requires low computation power than that of the real computation power needed for the entire model to train.

- The following image will show the illustration of the tranfer learning technique.

#### Ensemble Learning

- Ensemble learning is the process of using two or more model for better predictions.

* We must use some technique to be get the predictions from those models.
* In this project we have chosen the upvoting technique, which refers to taking the model of the predictions of all the three model.
* This process really makes the very good accuracy.

* The following image shows the emsemble learning in visual way,

## Deployment

- The application along with the models are deployed in the cloud.
- Then the communcation between the applications and the cloud are done in a way by using the REST API.

#### Django Web Application

- Django is a python framework for the web applications.
- It is the web based result of the project.
- This web application is made in a way that it has the ability to get the image from the user sents to the cloud with the help of the REST API.
- Then the cloud responses with the result.
- Finally this web application displays the result to the end user.

#### Flutter Mobile Application

- Flutter is a cross platform framework.
- In this project flutter is used to develop a mobile application for this project.
- This mobile app serves the end user by making them upload the image by cropping the image.
- Once the user submits the image then the REST API gets the image and transfer it to the cloud where the business logic takes place.
- Then the result from the cloud is displayed on the flutter mobile app.
</div>

[!Overall Demontration](https://github.com/naanmudhalvan-SI/IBM--13630-1682660810/assets/103887376/48bed622-f113-4668-aebb-b05c20778326)
