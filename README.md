# Age_gender_detection
In this age gender detection project I have used OpenCV and DNN models.
# 🧠 Face, Age, and Gender Detection using OpenCV

This project performs **real-time face detection**, **age prediction**, and **gender classification** using OpenCV and pre-trained deep learning models.

## 🚀 Features
- Detects faces in a webcam video stream
- Predicts the age range of each detected face
- Predicts the gender (Male/Female) of each detected face
- Uses OpenCV's DNN module and Caffe models

---

## 📦 Requirements

Install the dependencies using pip:

```bash
pip install numpy opencv-python pandas

📁 Pre-trained Model Files
This project requires the following pre-trained model files:

Model Type	Files
Face Detection	opencv_face_detector.pbtxt, opencv_face_detector_uint8.pb
Age Prediction	age_deploy.prototxt, age_net.caffemodel
Gender Prediction	gender_deploy.prototxt, gender_net.caffemodel
🔗 Download Links
You can download all the required files from the LearnOpenCV AgeGender repository:

Face Detector -https://github.com/spmallick/learnopencv/blob/master/AgeGender/opencv_face_detector.pbtxt

Face Detector - https://github.com/spmallick/learnopencv/blob/master/AgeGender/opencv_face_detector_uint8.pb

Age Model - https://github.com/spmallick/learnopencv/blob/master/AgeGender/age_deploy.prototxt

Age Model - https://github.com/spmallick/learnopencv/blob/master/AgeGender/age_net.caffemodel

Gender Model - https://github.com/spmallick/learnopencv/blob/master/AgeGender/gender_deploy.prototxt

Gender Model - https://github.com/spmallick/learnopencv/blob/master/AgeGender/gender_net.caffemodel
