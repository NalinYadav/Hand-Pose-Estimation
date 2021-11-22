# Hand-Pose-Estimation
This is an OpenCV and DL based project that predicts different gestures of hand.
Specifically we have divided gestures into 10 classes and these are : 'okay', 'peace', 'thumbs up', 'thumbs down', 'call me', 'stop', 'rock', 'live long', 'fist', 'smile'

# Prerequisites

## Installing necessary libraries
Majorly 3 libraries have to be installed along with python : Tensorflow , OpenCV , Mediapipe

To install these libraries firstly we need to make sure that we have python 3.0 version or higher installed in our machine.
After installing python we have to open command prompt and write the following commands to install the required libraries:
* Tensorflow : pip install tensorflow
* OpenCV : pip install opencv-python
* Mediapipe : pip install mediapipe

## Including necessary files
The gesture.names file and mp_hand_gesture folder have to be downlaoded.These are provided in this repository.
* gesture.names file contains the names of gesture classes separated by new lines
* mp_hand_gesture folder contains the tensorflow trained model and other necesarry variables required to load our model

Make sure to keep these files in the same directory of the code.

After following the above steps our code will be ready to use.
