# Step we have followed while executing the azure pipeline.
create the resources- AKS, ACR, DB
import the source code from local to azure repos.
start the confguration first we have to replace the token. write the yaml file as per the requirement.
once the CI part is completed.
then will move for the CD part (release part)
setup the agent called the AKS resource and do the configuration to run our CD piepline.
with the help of LB expose the application outside the world.

# My Health Clinic - A Demo app for Azure DevOps Zero to Hero

## Overview
My Health Clinic, a sample application built for demo and training purposes, is for a fictitious health care provider **HealthClinic.biz**. 
HealthClinic.biz uses different Microsoft and multi-channel apps built with Visual Studio and Azure to grow their business and modernize their customer experience. 
They also innovate and offer multiple apps and services—including websites, mobile apps, and wearable apps—to empower their patient’s well-being with easy access to manage their healthcare data and stay healthy.

**Note:** 
This repo was imported from the Azure Repos provided with this [Lab](https://github.com/Microsoft/azuredevopslabs/tree/master/labs/vstsextend/kubernetes/)

The code has been modified from the original version. The mobile (Xamarin and Cordova) projects have been removed and the web project has been upgraded to work in Visual Studio 2017.      
You can find the old, original code on this [GitHub repo](https://github.com/Microsoft/HealthClinic.biz)

![image](https://github.com/piyushsachdeva/MyHealthClinic-AKS/assets/40286378/3fd648b3-e0bc-44f3-ae29-8296e848a89c)

![](mhc-dashboard.png)


## Licenses

This project uses some third-party assets with a license that requires attribution:

Roboto Font: by [Christian Robertson](https://plus.google.com/110879635926653430880/about) ([Roboto at Google Fonts](https://fonts.google.com/specimen/Roboto))
Raleway Font: by Matt McInerney, Pablo Impallari, Rodrigo Fuenzalida and by Igino Marini ([Raleway at Google Fonts](https://www.google.com/fonts/specimen/Raleway))
For additional information about the licenses, please see the dependency repositories.

# Error while excuting this pipeline.
![image](https://github.com/user-attachments/assets/ae8862a6-5d57-4463-a501-12c45b707b50)
we have started the docker then below error is resolve and new error is appear.
![image](https://github.com/user-attachments/assets/c7dedb6a-795e-4a4a-bb5b-f0693234e8b1)


