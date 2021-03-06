# Bird Watching Robot Project


# Hardware 

## Raspberry Pi 4 Model B 8 GB RAM
![Image](rasp_pi_4_b_03_anw.png)

A small size fully-functional computer that can be programmed almost in any language, and to which additional hardware can be attached.

## Pi Camera V2

8-megapixel camera module attached to Raspberry Pi board with the help of a ribbon cable that gives our robot the ability to see. 
Pi Camera is able to provide 1920x1080 pixels resolution for up to a rate of 30 frames per second

## Pan-Tilt HAT 

![Image](20210218_150350.gif)

The HAT and its on-board microcontroller allow independently drive the two servos (pan and tilt). 
The module pans and tilts through 180 degrees in each axis.


# Object Detection and Classification 

## SSD MobileNetV3 Model

SSD MobileNetV3 pre-trained on Common Objects in Context (COCO) dataset and converted to TensorFlow Lite, an open source deep learning framework that allows to run Tensorflow Models on mobile, embedded, and IoT devices and enables on-device machine learning inference with low latency and a small binary size. 
The model was trained using [TensorFlow Object Detection API](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/ "TensorFlow Object Detection API").

In addition to the rpi-deep-pantilt package that is using Google's TensorflowLite, here is a link to the tutorial on how to implement the pre-trained [MobileNetV2 + SSDLite with Core ML](https://machinethink.net/blog/mobilenet-ssdlite-coreml/ "MobileNetV2 + SSDLite with Core ML") on iOS devices using machine learning framework Core ML developed by Apple for iOS.


| Model Name        | Description   |
| ----------------  | ------------- |
|  [SSD MobileNetV3](https://github.com/jennyrud01/rpi-deep-pantilt/tree/master/models/ "SSD MobileNetV3")  | SSD with MobileNetV3 backbone implementation   |


![Image](birds.gif)

In the implementation you can see real-time object detection based on single-shot detector algorithm. 

## Single-Shot Detector Algorithm
To be continued. 

## Requirements 

To be continued.
