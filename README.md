#Webcam Motion Detector
This Python script implements a webcam motion detector application using the OpenCV library. The application captures video from the computer's webcam and detects motion in the video stream. 
When motion is detected, it records the start and end times of the motion events and saves them to a CSV file named "Times.csv". 
The script utilizes image processing techniques such as background subtraction and contour analysis to identify areas of change in consecutive frames of the video.