# Drowsiness Detection

Detects eyes and alert when the user is drowsy.

## Applications 🎯
This can be used by riders who tend to drive for a longer period of time that may lead to accidents.

### Code Requirements 🦄
The example code is in Python ([version 2.7](https://www.python.org/download/releases/2.7/) or higher will work). 

### Dependencies

1) import cv2
2) import imutils
3) import dlib
4) import scipy


### Description 📌

A computer vision system that can automatically detect driver drowsiness in a real-time video stream and then play an alarm if the driver appears to be drowsy.

### Algorithm 👨‍🔬

Each eye is represented by 6 (x, y)-coordinates, starting at the left-corner of the eye (as if you were looking at the person), and then working clockwise around the eye.

It checks 20 consecutive frames and if the Eye Aspect ratio is less than 0.25, Alert is generated.

<img src="https://github.com/arefin97/Drowsiness-Detection/blob/master/eye1.jpg">


#### Relationship

<img src="https://github.com/arefin97/Drowsiness-Detection/blob/master/eye2.png">

#### Summing up

<img src="https://github.com/arefin97/Drowsiness-Detection/blob/master/eye3.jpg">


For more information, [see](https://www.pyimagesearch.com/2017/05/08/drowsiness-detection-opencv/)

### Results 📊

<img src="https://github.com/arefin97/Drowsiness-Detection/blob/master/drowsiness.gif">


### Execution 🐉
To run the code

```
python Drowsiness_Detection.py
```

## References 🔱
 
 -   Adrian Rosebrock, [PyImageSearch Blog](https://www.pyimagesearch.com/2017/05/08/drowsiness-detection-opencv/)
