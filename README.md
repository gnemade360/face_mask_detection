# face_mask_detection

Face Mask Detection in Python
Introduction
Welcome to the Face Mask Detection Python program! This program uses computer vision and deep learning techniques to detect whether a person is wearing a face mask or not. The program leverages the TensorFlow framework with the MobileNetV2 model for face mask detection.

Requirements
This program requires Python 3.x and the following libraries to run:

TensorFlow
TensorFlow Hub
OpenCV
You can install the required libraries using pip:

Copy code
pip install tensorflow tensorflow-hub opencv-python

How to Run the Face Mask Detection
Clone or download the repository to your local machine.
Ensure you have a webcam connected to your system.
Navigate to the project directory containing the Python script (face_mask_detection.py).
Run the face_mask_detection.py script using the following command:
Copy code
python face_mask_detection.py

The program will start capturing video from the webcam and detecting face masks in real-time.
Program Description
The Face Mask Detection program uses a pre-trained MobileNetV2 model from TensorFlow Hub. This model is trained on a large dataset of images, including masked and unmasked faces. The program captures video from the webcam (or a video file), processes each frame, and uses the model to detect faces and check for face masks.

Customization
You can modify the model URL in the script to use a different pre-trained model suitable for face mask detection.
To process a video file instead of webcam, change the cv2.VideoCapture(0) to the path of your video file.



