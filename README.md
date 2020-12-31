# FaceDetectionOpenCV

OpenCV(Open Computer Vision) is an open source C++ library for computer vision. It features algorithms for face detection. In this repository we use OpenCV in Python to detect faces in a picture.

We are using the Viola-Jones object detection framework. A cascade of Haar-like classifiers has been trained on many images to detect faces. We use haarcascade_frontalface_default.xml.

[alt picture]/('results.png')

Discussion:

All detected objects are faces, one face out of four faces is not detected. The face that was not detected is not perfectly facing the camera, whereas the faces in the training set were. 




