# Driver-Drowsiness-Detection-System
This is a small prototype model which can be used to check if drivers driving in the night are awake enough to safely drive. It is coded on Python and uses OpenCV, Keras and Pygame. It measures drowsiness of a person by calculating the time for which he/she closes her eyes while blinking.


# Working 
This model uses Keras to create a neural network.
OpenCV to process images/frames  extracted from video feed.
Haar Cascade to identify faces, left eye , right eye.
Pygame to ring the alarm.

The model calculates the time for which both the eyes of the user are closed continously ans assigns a score.
If this score crosses a threshold limit alarm rings.
The model uses very basic methods to detect face and eyes hence it is susceptible to factors like lighting, variations in face and eye shapes/sizes.

Note:- 
The model.py should automatically create a model and save it in a folder models as cnncat2.h5 file but in case it doesn't download the file from following link.
https://drive.google.com/file/d/1_WW-ojwzAs9g-D4xShA2rhPJ8NmZYvh1/view?usp=sharing
Create a folder models, put the file in tht folder and save in the the directory containing rest of the files.(Tht file couldn't be uploaded due to size constraints on github).
