# Overview

A series of experiments combining machine learning and computer vision. I'll summarize fundamentals in machine learning as well as computer vision concepts.

## Machine Learning

We train our machine to recognize very specific patterns and features that will govern how the model will be affected while propogating the various layers. By actively forecasting with the data online, the machine should be able to anticipate its next move fairly precisley. We musn't overfit our data model. I'm expecting many generations while producing various species of said data model. One of my test subjects will be a web site. Can we train our model to recognize the features of a website when tasked with scraping data. The goal is to implement the necessary code that can learn and figure out how to scrape a website by giving it a set of simple inputs and requirements.

Example:

| input  | value                 |
|--------|-----------------------|
| url    | http://www.google.com |

The code must be aware of the general structure of a web page and specialized layouts to determine intent and possible order of operations when it comes to traversal/navigation. 
Train the model in a supervised manner first, in order to keep actual "eyes" on training results. This is necessary in order to familiarize the machine with what a web page characteristics. 

### Neural Network

A series of neural networks provide us with the neccessary "outlets" for inputs and outputs produces by the forward propogation mechanism, parellelized. I'm using the term "outlet" in the documentation, similar in iOS development. 

## Computer Vision

Goals:

- Recognize parts of a web page
- The fitness would be calculated by affirming "distance" to the desired result (a lesser error score)
