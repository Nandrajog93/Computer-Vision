# Facial-Recognition-using-Machine-Learning-
Build an App that basically train recognizing your face using Machine Learning using Opencv&amp; LBPHFaceRecognizer.


Collecting & Training data:

1) First I will use HAAR cascade classifier on webcam images to collect 100 images of the user's face.
2) Then normalize the image by greyscaling and resizing the image by 200 by 200 pixels. 
3) Create an array of labels for recorded images.
4) Then train the model using LBPHFaceRecognizer_create() facial recognition library. 


Classify new face:

1) Extract the face from webcam using the HAAR cascade
2) Normalize by greyscaling and resizing to 200 by 200 pixels.
3) Pass face to our model predictor to get label and confidence value.
