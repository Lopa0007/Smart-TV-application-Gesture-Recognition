# Project Name
> Neural Networks Project - Gesture Recognition


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
A smart-TV manufacturer wants to build a cool feature that can recognise five different gestures performed by the user which will help users control the TV without using a remote. The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:

Thumbs up:  Increase the volume
Thumbs down: Decrease the volume
Left swipe: 'Jump' backwards 10 seconds
Right swipe: 'Jump' forward 10 seconds  
Stop: Pause the movie

The training dataset contains videos of these five categories where each videos has 30 frames (images).

## Conclusions

Based on the above observation, we are considering Conv2d+GRU to be the best model resulting 89% validation accuracy. It has also been observed that optimisers RMSProp and Adam is doing better than SGD in terms of valuation accuracy while Adam is giving the slightly better result than RMSProp.


## Technologies Used
Python 3.10


## Acknowledgements
- This project was based on Upgrad ACP DL curriculam.


## Contact
Created by [@Lopa0007] - feel free to contact me!


