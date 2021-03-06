# JJ111 SUBMISSION NAME

Team Members:
- Benjamin Neo Ser Teng
- Charles Lim Jia Le
- Koh Shi Qi
- Ng Ying Ting

Requirements:
- short description of team members and team name
- short description of the problem, how technology can help, idea the team is proposing
- pitch video
- architecture of proposed solution
- hyperlink to detailed solution (pdf proposal or just put our longer slidedeck since the pitch is only 2mins)
- project roadmap/timeline (OPTIONAL)
- getting started (Step-by-step instructions to install the required software and how to run a demo of your solution) (IMPOSSIBLE!!!)
- running the tests (Explanation and breakdown on how to run tests for the proposed solution) (OPTIONAL)
- live demo (actual working demo/website) (OPTIONAL && IMPOSSIBLE)
- what we used to build our solution

## Contents

1. [Short Description](#short-description)
1. [Demo Video](#demo-video)
1. [The Architecture](#the-architecture)
1. [Long Description](#long-description)
1. [Project Roadmap (OPTIONAL)](#project-roadmap)
1. [Getting Started](#getting-started)
1. [Method (place under long description???)](#Method)
1. [Running the Tests (OPTIONAL)](#running-the-tests)
1. [Live Demo (OPTIONAL)](#live-demo)
1. [Built with](#built-with)

## Short Description

### What's the problem?

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc lacinia nisi ut fringilla sodales. Etiam elementum a arcu vel fringilla. Nulla ac efficitur felis. In a nisi bibendum, efficitur felis vel, consectetur quam. Aenean ornare justo velit, sed malesuada massa efficitur ut. Sed non augue vel risus tempus lacinia ac nec est. Nunc vel finibus felis. Vivamus felis diam, porta sed rhoncus eu, luctus eget justo.

Mauris odio ante, rhoncus et varius vel, vulputate et enim. Aliquam erat volutpat. Proin lacinia libero velit, a dictum sapien ultricies quis. Vivamus dolor nibh, efficitur in ipsum vitae, faucibus eleifend felis. Praesent consectetur turpis sit amet lorem tempor cursus. Nullam nec lectus massa. Proin feugiat placerat nisi lacinia lobortis. Duis efficitur ac orci ac lobortis.

### How can technology help?

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc lacinia nisi ut fringilla sodales. Etiam elementum a arcu vel fringilla. Nulla ac efficitur felis. In a nisi bibendum, efficitur felis vel, consectetur quam. Aenean ornare justo velit, sed malesuada massa efficitur ut. Sed non augue vel risus tempus lacinia ac nec est. Nunc vel finibus felis. Vivamus felis diam, porta sed rhoncus eu, luctus eget justo.

Mauris odio ante, rhoncus et varius vel, vulputate et enim. Aliquam erat volutpat. Proin lacinia libero velit, a dictum sapien ultricies quis. Vivamus dolor nibh, efficitur in ipsum vitae, faucibus eleifend felis. Praesent consectetur turpis sit amet lorem tempor cursus. Nullam nec lectus massa. Proin feugiat placerat nisi lacinia lobortis. Duis efficitur ac orci ac lobortis.

### The Idea

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc lacinia nisi ut fringilla sodales. Etiam elementum a arcu vel fringilla. Nulla ac efficitur felis. In a nisi bibendum, efficitur felis vel, consectetur quam. Aenean ornare justo velit, sed malesuada massa efficitur ut. Sed non augue vel risus tempus lacinia ac nec est. Nunc vel finibus felis. Vivamus felis diam, porta sed rhoncus eu, luctus eget justo.

Mauris odio ante, rhoncus et varius vel, vulputate et enim. Aliquam erat volutpat. Proin lacinia libero velit, a dictum sapien ultricies quis. Vivamus dolor nibh, efficitur in ipsum vitae, faucibus eleifend felis. Praesent consectetur turpis sit amet lorem tempor cursus. Nullam nec lectus massa. Proin feugiat placerat nisi lacinia lobortis. Duis efficitur ac orci ac lobortis.

## Demo Video

[![Watch the video](https://github.com/Code-and-Response/Liquid-Prep/blob/master/images/IBM-interview-video-image.png)](https://youtu.be/vOgCOoy_Bx0)

## The Architecture

*** INSERT ARCHITECTURE IMAGE ***

1. lorem ipsum
2. lorem ipsum
3. lorem ipsum
4. lorem ipsum

## Long Description

[More detail is available here](DESCRIPTION.md)

## Project Roadmap (OPTIONAL)

*** INSERT ROADMAP IMAGE ***

## Getting Started (IMPOSSIBLE)

```bash
print('hello world')
```

## Method (place under long description???)

### Prediction using Watson Machine Learning and AutoAI

#### Training Data

Using the available data on [air temperature, rainfall and relative humidity](/prediction_training_dataset) retrieved from [Data.gov.sg](https://data.gov.sg) and mock vegetation fire data (estimated using news reports), a Watson Machine Learning model is trained to identify correlation between weather patterns and vegetation fire occurences.

*Limitations:*  
*- Insufficient data on daily air temperature, rainfall, relative humidity and wind speed to accrately train machine learning model*  
*- Insufficient data on vegetation fire occurrence (Date/Time/Location) to accurately train machine learning model*

#### Live Prediction

Once deployed, realtime weather readings across Singapore can be retrieved using APIs from [Data.gov.sg](https://data.gov.sg) to continue training the machine learning model to adapt to realistic scenarios.

These are the following APIs that will provide Watson Machine Learning with the realtime data:
- [Air Temperature across Singapore](https://data.gov.sg/dataset/realtime-weather-readings?resource_id=17494bed-23e9-4b3b-ae89-232f87987163)
- [Rainfall across Singapore](https://data.gov.sg/dataset/realtime-weather-readings?resource_id=8bd37e06-cdd7-4ca4-9ad8-5754eb70a33d)
- [Relative Humidity across Singapore](https://data.gov.sg/dataset/realtime-weather-readings?resource_id=59eb2883-2ceb-4d16-85f0-7e3a3176ef46)
- [Wind Speed across Singapore](https://data.gov.sg/dataset/realtime-weather-readings?resource_id=16035f22-37b4-4a5c-b024-ca2381f11b48)

In order to enhance predictive capabilities, accurate weather forecasts can be retrieved from IBM's Weather Company through the [Weather Company Data API](https://twcservice.mybluemix.net/rest-api/?cm_mc_uid=37684228856315685703470&cm_mc_sid_50200000=51294231592077646327&_ga=2.32643646.1059871242.1591976735-1932570688.1591976735) to predict probability of vegetation fire occurence in the next week.

### Identification using Watson Machine Learning 

Using prediction data, Airborne Early Warning Device (AEWD) [or just Patrol Drone] will be deployed according to probability of vegetation fire. Integrating Watson Machine Learning and onboard sensors, HD camera and thermal imager, the AEWD is able to identify areas with potential for vegetation fire occurence, early signs of vegetation fire such as smoke, and undetected vegetation fire deep in the vegetation.

#### Training Data

Training image for dry vegetation identification on HD camera.  
*** INSERT DRONE IMAGES (dry vegetation)***  

Training image for dry vegetation identification on thermal imager.  
*** INSERT DRONE IMAGES (dry vegetation thermal)***  

Training image for smoke identification on HD camera.  
*** INSERT DRONE IMAGES (smoke)***  

Training image for smoke identification on thermal imager.  
*** INSERT DRONE IMAGES (smoke thermal)***  

Training image for small vegetation identification on HD camera.  
*** INSERT DRONE IMAGES (small vegetation fire)***  

Training image for small vegetation identification on thermal imager.  
*** INSERT DRONE IMAGES (small vegetation fire thermal)***  

## Running the Tests (OPTIONAL)

## Live Demo

## Built with

* [IBM Cloud]
