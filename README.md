# Face & Eye detection using OpenCV 

Face detection uses classifiers, which are algorithms that detects what is either a face(1) or not a face(0) in an image. Here we work with face detection using Haar-Cascade classifier with OpenCV.
OpenCV comes with many pre-trained models of haarcascade classifiers like face, eye, smile etc in XML file. Those XML files (pre-trained models) are stored in *opencv/data/haarcascades/* folder. You can also add those classifiers if you want, but here I am going to use only two classifiers i.e. one for face and another for eye.

In this project, we are going to use default camera of our system/laptop to take input as live video OR you can also pass a video as an argument to perform face detection on video. As we can't directly work on video, we will be extracting each frames from the video and then perform face detection on frames.

## Steps to run:

#### Prerequisites:
Python with OpenCV installed.

To install opencv
> pip install opencv-python

#### Run:

1. clone this repo using
> git clone https://github.com/Sonkaryasshu/Face_Detection.git

> cd Face_Detection

2. Run python file, specifying input source

*If input is any video, pass that video as an argument*
> python detector.py "input_video.mp4"

*Else input will be taken from default camera of your system*
> python detector.py

3. To quit the program
*Press 'q'* from keyboard



