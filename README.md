# Real Time Object/Face Detection Using YOLO-v3

This project implements a real time object and face detection using YOLO algorithm. You only look once, or YOLO, is one of the fastet object detection algorithm, suitable for real-time detection. This repository contains code for object and face detector based on YOLOv3: An Incremental Improvement which originaly implemented in YOLOv3. The first part of this project focuses on object detection algorithm from scratch in pytorch using pre-trained weights. The second part and third part relate to the object detection and face detection algorithm using opencv library using yolo pre-trained weights.

# Requirements

    python 3.5
    Opencv 3.4.2
    pytorch
    numpy

# Object Detection Example
![image](https://user-images.githubusercontent.com/78218075/144877292-33f5e864-9997-4bcf-b25e-40070d21ba14.png)

# Face Detection Example

![image](https://user-images.githubusercontent.com/78218075/144877531-164fb599-80c3-4be6-9778-327a14238f32.png)

# Running the detectors

Object detection using pytorch

To detect a single or multiple images, first clone the repository

git clone https://github.com/pujandave/Object-detection-with-YOLO/Pytorch_ObjectDetection/.git

Then move to the directory

cd Pytorch_ObjectDetection

To run image detection

python detect.py

To run video and real-time webcame

python detect_video.py

Note that YOLO weights can be downloaded from yolov3.weights
Object detection using opencv

OpenCV dnn module supports different pre-trained deep learning models and recently YOLO/Darknet has been added to opencv dnn module. To run the detector, first clone to the repository

git clone https://github.com/pujandave/Object-detection-with-YOLO/OpenCV_ObjectDetection/.git

Then move to the directory

cd OpenCV_ObjectDetection

To run image detection

python yolo_Opencv.py

To run video and real-time webcame

python yolo_Opencv_video.py
Face detection using opencv

To run the face detector, first clone to the repository

git clone https://github.com/pujandave/Object-detection-with-YOLO/OpenCV_FaceDetection/.git Then move to the directory

cd OpenCV_FacetDetection

Run the image detector

python yolo_Opencv_Face.py

Run the video/webcame detector

python yolo_Opencv_Face_video.py

Note that to use yolo for face detection it is required to download yolo face detection weight from yolov3.weights. An example of face detection:
![image](https://github.com/Pujandave/Object-detection-with-YOLO/blob/main/1*NLnnf_M4Nlm4p1GAWrWUCQ.gif)

