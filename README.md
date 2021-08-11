# Facial-Emotion-Detector
* I have build a facial emotion detector web app. In this project, I used **Keras** API with **TensorFlow** as backend, **OpenCV** and **Flask**. 
## This project has 3 distinctive parts:-  
### EXPRESSION REGRESSOR 
Using keras I trained a model with images of 7 different facial expressions :
* happy
* angry
* sad
* disgust
* neutral
* surprise
* fear

### FACE DETECTOR
The next part was capturing images from my webcam and detecting faces. I accomplished this task by OpenCV's  **haarcascade_frontalface_default.xml**. So, basically the faces that were detected were feeded to my expression regressor model and the predicted emotion were shown on the camera screen.

### MODEL DEPLOYMENT
The final part was model deployment, for which I used Flask framework.  
