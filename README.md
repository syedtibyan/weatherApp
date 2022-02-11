# Weather Forecasting Application
A simple IoT project for Software Engineering Course (SKEL413) on a Weather Forecasting Application.
## Group 4 Members: 
 1. Syed Mohammed Tibyan Tisher (A17KE4031)
 2. Mohammed Muatasim Siddig (A18KE4011)
 3. Ahlam Forqan (A17KE3003)

### Table of Contents 

- [Weather Forecasting Application](#weather-forecasting-application)
    + [Table of Contents](#table-of-contents)
  * [IoT Weather Forecasting Application](#iot-weather-forecasting-application)
    + [Problem Statement](#problem-statement)
      - [Use Case Diagram](#use-case-diagram)
      - [Use Case Description - Weather Forecasting App](#use-case-description---weather-forecasting-app)
    + [System Architecture](#system-architecture)
    + [Sensor/Devices](#sensordevices)
    + [Cloud Platform](#cloud-platform)
    + [Dashboard](#dashboard)
      - [Before improvement:](#before-improvement)
      - [After improvement:](#after-improvement)
  * [Milestone videos showing the progess of our project](#milestone-videos-showing-the-progess-of-our-project)
    + [Milestone 2](#milestone-2)
    + [Milestone 3](#milestone-3)
    + [Milestone 4](#milestone-4)
    + [Milestone 5](#milestone-5)
   
## IoT Weather Forecasting Application

### Problem Statement

Weather has an impact on people's health and habits, as well as the economy, society, and the environment. The severity of the impact is determined by a number of elements, including the type of weather event, the date of the event, the severity of the event, the duration of the event, and the location of the event. Malaysia has an equatorial climate, which means that the weather is hot and humid most of the year, with plenty of rain. It is one of the Asian countries most sensitive to climate change, therefore weather forecasts are a useful tool for people to prepare ahead and take precautions when necessary. This software provides current weather information as well as forecasts for the future based on the date and time entered by the user. It warns people of severe weather conditions, such as heat waves and heavy rains. 


#### Use Case Diagram
![Use Case Diagram](https://user-images.githubusercontent.com/94036456/152689391-502c9f98-0544-41c4-8a1a-9d48fc1d3f97.png)


#### Use Case Description - Weather Forecasting App


|        | Description |
| ------- | ---------------|
| System | Weather Forecasting Application |
| Use Case Name | Reporting Weather |
| Actors | Normal user, weather station database |
| Pre Condition | User enters the name of the city for which they want weather information |
| Data | The weather station sends summary of weather data that has been collected from the sensors. The data will be covering on the temperature, day, time and status |
| Post Condition | The data is summarized and sent to the user and the user receives weather information|


### System Architecture

Below is a general overview of our IoT weather monitoring system's system architecture. For the system, it has been decided to use a data base from Kaggle for our data resource and use a mobile as a device. The ingest data is Django Rest Framework and the device will communicate using HTTP data protocol transmission for data transmission, and it will send the data to the Heroku Cloud platform before updating the data on our simple dashboard app, which will be created using Thunkable.


![system architechture](https://user-images.githubusercontent.com/94036456/152691410-3158de8e-142f-468c-b774-7ec75873128a.png)


### Sensor/Devices

Proposed Device: Smart Phone

Proposed Data Transmission Protocol : HTTP

Database: Google Data


### Cloud Platform

Backend Framework: Django REST Framework

Cloud Hosting Platform: Heroku

URL of our Heroku App: https://weather-forecasting-django.herokuapp.com/

  

### Dashboard

This is the dashboard that was created using Thunkable. It displays the temperature, day, time and weather status of the desired place/city.

#### Before improvement:

![Slide1](https://user-images.githubusercontent.com/94036456/152692129-943704db-f688-462f-a7e9-fd87e54d43a6.PNG)


#### After improvement:

![Slide2](https://user-images.githubusercontent.com/94036456/152692137-7faa842a-78c6-4d9d-9a12-0afd5f1531b0.PNG)

 
 
## Milestone videos showing the progess of our project
 
 ### Milestone 2
 Milestone 2: This is the Github [link](https://github.com/syedtibyan/hello-world/tree/main) for the initial project proposal.
 
 This [video](https://www.youtube.com/watch?v=OulPHqP3-Do) shows how we deploy Heroku App for cloud computing.
 
 ### Milestone 3
 Milestone 3: This milestone 3 [video](https://www.youtube.com/watch?v=_Uaw4Dv0HQo) shows the process of sending data to the server using GET function where Django server catches the data and stores it.

 ### Milestone 4
 Milestone 4: This milestone 4 [video](https://www.youtube.com/watch?v=euC4TuT2mGY) shows how our app sends data followed by the dashboard that displays the selected results.


 ### Milestone 5
 Milestone 5: This milestone 5 [video](https://www.youtube.com/watch?v=wLowEuN7x4Y) shows some user feedback and demonstrates the current version of the product.
