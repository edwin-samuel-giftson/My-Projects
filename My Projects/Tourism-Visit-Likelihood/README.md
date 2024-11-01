# German Biography Generator

## Table of Contents
1. [Introduction](#introduction)
2. [Requirements](#requirements)
3. [Architecture](#architecture)
4. [Implementation and Results](#implementation-and-results)
5. [Conclusions](#conclusions)
6. [Future Scope](#future-scope)

---

## Introduction

This project explores opinion mining on Twitter, focusing on tourism as an application domain. Using a Bayesian-based framework, the system processes tweets through Twitter's API to derive and evaluate user sentiments regarding travel preferences. By leveraging a probabilistic reasoning system, Problog, and an incremental learning strategy, the model can continuously improve its predictions about users’ intentions to visit specific locations. This flexible approach can also be adapted for opinion mining across various other topics on social media.


---

## Requirements

### Hardware Requirements

  • System : Intel Pentium 4 3.0GHZ. 
  
  • Hard Disk : Sufficient 
  
  • Input Devices : Keyboard, Mouse 
  
  • Ram : 1 GB 

### Software Requirements 

  • OS : Windows 7 or above 
  
  • Coding Language : Python 
  
  • IDE : Jupyter Notebook 
  
  • Python Distribution: Anaconda 
  
  • Libraries : Numpy 1.16.1, Pandas 0.24.1, Pip 19.0.3, 10 Problog 2.1.0.39, Tkinter 8.5.9



---

## Architecture

![image](https://github.com/edwin-samuel-giftson/My-Projects/blob/main/My%20Projects/Tourism-Visit-Likelihood/Architecture.png?raw=true)


---

## Implementation and Results

### Home Window

![image](https://github.com/edwin-samuel-giftson/My-Projects/blob/main/My%20Projects/Tourism-Visit-Likelihood/Implementation%20and%20Results/1_Home%20Window.png?raw=true)

### Initial Training of the Model

![image](https://github.com/edwin-samuel-giftson/My-Projects/blob/main/My%20Projects/Tourism-Visit-Likelihood/Implementation%20and%20Results/2_Initial%20Training%20of%20the%20Model.png?raw=true)

### Incremental Learning

![image](https://github.com/edwin-samuel-giftson/My-Projects/blob/main/My%20Projects/Tourism-Visit-Likelihood/Implementation%20and%20Results/3_Incremental%20Learning%201.png?raw=true)

![image](https://github.com/edwin-samuel-giftson/My-Projects/blob/main/My%20Projects/Tourism-Visit-Likelihood/Implementation%20and%20Results/4_Incremental%20Learning%202.png?raw=true)

### Test the Trained Model

![image](https://github.com/edwin-samuel-giftson/My-Projects/blob/main/My%20Projects/Tourism-Visit-Likelihood/Implementation%20and%20Results/5_Test%20the%20Trained%20Model.png?raw=true)

---

## Conclusions

This project demonstrates a robust system for applying probabilistic reasoning to opinion mining on social media, specifically using Twitter data to predict user interest in visiting specific destinations. By automating tasks such as sentiment analysis, entity recognition, and rule generation, our model constructs a Bayesian Network with the ability to learn incrementally. Built on the Problog toolbox, this adaptable framework can be extended to analyze user sentiment across various social media platforms, offering valuable insights for applications in tourism and beyond.


---

## Future Scope

This project’s Bayesian model could be extended to various domains beyond tourism, such as healthcare, where it might analyze user sentiment to answer questions like “Is this user showing signs of depression?” Additionally, multiple Bayesian models could be developed to assess user intent across different locations within the same domain, such as determining intent to visit Crete, Paros, or other destinations. These expansions would enhance the system's adaptability and application scope across diverse topics and regions.

--- 

