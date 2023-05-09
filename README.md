# Python-Security-Camera-OpenCV
This code is a Python script that uses OpenCV library to detect faces and bodies in a live video stream from a camera. The program captures video frames from the camera, converts them to grayscale, and applies a cascade classifier to detect any face or body present in the frame.

If a face or body is detected, the program starts recording the video for 5 seconds, and saves it to a file with the current date and time stamp in the filename. The program continues to monitor for face or body presence, and if none is detected for 5 seconds, the recording stops and the output file is closed.

The program uses a loop to continuously capture and process video frames from the camera, and also displays the video stream with rectangles around the detected faces and bodies.
