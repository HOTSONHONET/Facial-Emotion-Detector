# Facial-Emotion-Detector
I have build a facial emotion detector web app. In this project, I used keras API with tensorflow as backend, OpenCV and flask. This project has 3 distinctive parts:-  
EXPRESSION REGRESSOR 
#Using keras I trained a model with images of 7 different facial expressions (happy, angry, sad, disgust, neutral, surprise, fear). During this model development, I faced class imbalance problem which I tackled with ImageDataGenerator.   

FACE DETECTOR
#The next part was capturing images from my webcam and detecting faces. I accomplished this task by OpenCV's face detector (haarcascade_frontalface_default.xml). So, basically the faces that were detected were feeded to my expression regressor model and the predicted emotion were shown on the camera screen.

MODEL DEPLOYMENT
#The final part was model deployment, for which I used flask framework.  An interesting thing about this project is that it  also detect facial emotions in  videos or images with just one line change in code.
