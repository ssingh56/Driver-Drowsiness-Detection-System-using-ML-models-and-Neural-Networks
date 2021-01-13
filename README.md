# Driver-Drowsiness-Detection-System-using-ML-models-and-Neural-Networks
Driver Drowsiness Detection System using ML and Neural Networks


### Problem Statement:

Feeling drowsy while we are behind the wheels is something all of us have faced sometime or the other. Long road trips, driving continuously for several days and nights can lead us to feel fatigued and drowsy while driving. According to the statistics – “1 in 25 adult drivers report that they have fallen asleep at the wheel in the past 30 days”. Moreover, 1 in 4 vehicle accidents happen because the driver is feeling drowsy while driving. Drowsy driving can have severe consequences, and this is a problem that needs to be addressed

To resolve this major societal problem, I have designed a ‘Driver Drowsiness Detection System’. This system will identify the key factors of drowsiness seen while driving and trigger an alert when a driver feels drowsy before it’s too late.

I have designed several machine learning models for 'Driver Drowsiness Detection System' that will be taking in features such as Eye-Aspect-Ratio, Mouth-Aspect-Ratio, Pupil-Circularity and Mouth-Over-Eye as inputs and will be predicting the States of the driver as either Alert or Drowsy as the outputs. This is a binary classification problem.

### Information about the Dataset:

For our training and testing data, I have used the RLDD (Real-Life Drowsiness Dataset) which has been specifically curated for this purpose by a research team at University of Texas, Arlington for detecting multi-stage drowsiness. This dataset consists of 180 RGB videos which is around 30 hours of videos of 60 unique participants. Each video is around 10 min long and was recorded by a personal cell phone or web camera in a way to replicate the videos similar to what would be obtained in a car or from a phone holder on the car dash.For each participant, there is one video for each of the two different classes:

1) Alert – subject is completely conscious and can easily drive for long hours

2) Drowsy – subject is falling asleep and needs to actively try to not fall asleep

For my project, I have currently used 18 videos of 9 unique participants and have trained the machine learning models using these videos

Link to the dataset: https://sites.google.com/view/utarldd/home


### Deep Learning Models implemented:

- Simple Feedforward Neural Networks

- Recurrent Neural Networks

- Long Short Term Memory

- Gated Recurrent Units

- Convolutional Neural Networks
