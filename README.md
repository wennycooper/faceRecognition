# faceRecognition
This is a sample code to use openCV FaceRecognizer for face recognition.

# Installation & Build
    $ git clone this project
    $ cd faceRecognition
    $ g++ -o facerec_demo ./facerec_demo.cpp ``pkg-config --cflags --libs opencv``
    $ ./facerec_demo ./faces/faces.txt
    
# Faces
* You will need to put your training images into ~/faces, and modify ~/faces/faces.txt
* Plz check ~/faces/faces.txt for the format (path;label)
* One line for one training images
* The last line is for the test image. it will not be trained

# Reference
* http://blog.csdn.net/abcd1992719g/article/details/24008513
* http://docs.opencv.org/2.4/modules/contrib/doc/facerec/facerec_api.html
