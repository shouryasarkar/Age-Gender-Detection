# Age and Gender Estimation with Face Detection

This repository contains a Python script for real-time age and gender estimation using face detection with OpenCV and pre-trained deep learning models.
# Overview

The script detects faces in real-time from a webcam feed and estimates the age and gender of each detected face. It utilizes a pre-trained deep learning model for face detection and separate models for age and gender estimation.
# Dependencies

    * Python 3.x
    * OpenCV (cv2)
    * Pre-trained deep learning models:
        * Face detection: opencv_face_detector.pbtxt and opencv_face_detector_uint8.pb
        * Age estimation: age_deploy.prototxt and age_net.caffemodel
        * Gender estimation: gender_deploy.prototxt and gender_net.caffemodel
