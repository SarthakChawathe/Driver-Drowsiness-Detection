# Driver-Drowsiness-Detection

The Driver Drowsiness Detection repository offers a real-time solution for monitoring driver drowsiness using computer vision techniques. By analyzing video input, the system detects signs of drowsiness based on eye tracking and triggers an alarm to alert the driver, helping to prevent accidents caused by fatigue. The repository provides the necessary code and resources to implement the system, with opportunities for further contributions to enhance its effectiveness in promoting road safety.



# Table of Contents
- [Introduction]()
- [Features]()
- [Usage]()
- [Customization]()

## Introduction
This repository contains a driver drowsiness detection system that uses computer vision techniques to monitor a driver's level of alertness. The system analyzes real-time video input from a camera which can be placed inside a vehicle and alerts the driver if signs of drowsiness are detected, helping to prevent potential accidents caused by driver fatigue.

The project utilizes OpenCV, a popular computer vision library, to perform facial landmark detection and eye aspect ratio (EAR) calculation. By tracking the driver's eyes, the system can determine if the eyes are closed for an extended period, indicating drowsiness. When drowsiness is detected, an alarm is triggered to alert the driver, allowing them to take necessary measures to stay awake and focused.


## Features
1) Real-time driver drowsiness detection using a webcam or video input.
2) Facial landmark detection to locate the driver's eyes accurately.
3) Calculation of eye aspect ratio (EAR) for drowsiness detection.
4) Adjustable threshold for determining drowsiness based on the EAR.
5) Audible alarm to alert the driver when drowsiness is detected.
6) Compatibility with various platforms and operating systems.

## Usage
1) Connect a webcam to your computer or provide a video file as input.
2) Run the drowsiness_detection.py script.
3) The system will start analyzing the video stream and monitoring the driver's drowsiness level.
4) If drowsiness is detected, an alarm will be triggered.
6) To stop the program, press Q or Esc.

## Customization
1) Adjust the EAR_THRESHOLD variable in drowsiness_detection.py to set the threshold for drowsiness detection according to your preference.
2) Modify the alarm sound by replacing the alarm.wav file in the project directory with your desired sound file.




