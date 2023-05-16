# Face-Detection
Real-Time Face Detection using OpenCV

This project demonstrates real-time face detection using OpenCV library in Python. It uses the Haar cascade classifier to detect frontal faces in a live video stream and also from Picture

Prerequisites

To run this project, you need to have the following prerequisites installed:

    Python (version 3.6 or above)
    OpenCV library (version 4.0 or above)

You can install OpenCV using pip:

pip install opencv-python

Usage

    Clone the repository or download the source code.
    Download the Haar cascade classifier XML file from the OpenCV GitHub repository: haarcascade_frontalface_default.xml.
    Save the XML file in the same directory as the Python script.
    Open a terminal or command prompt and navigate to the project directory.
    Run the following command to start the face detection:

python face_detection.py

    A video window will open, showing the live webcam stream with detected faces highlighted in a blue rectangle. Press 'q' to quit the program.

Customization

You can customize the face detection parameters in the code to adjust the performance. Here are some parameters you can modify:

    scaleFactor: Specifies how much the image size is reduced at each image scale. A lower value increases detection accuracy but slows down the algorithm.
    minNeighbors: Specifies how many neighbors each candidate rectangle should have to retain it. A higher value reduces false detections but may miss some faces.

You can experiment with different values for these parameters to achieve the desired trade-off between accuracy and speed.
License

This project is licensed under the MIT License.
Acknowledgments

The face detection algorithm used in this project is based on the work of Viola and Jones. The Haar cascade classifier XML file used is part of the OpenCV library.
References

    OpenCV Documentation
    OpenCV GitHub Repository

Feel free to modify and enhance the README file according to your project's requirements and additional information you want to provide.
