# Real-Time-Face-Detection
This project involves creating a system capable of detecting and tracking faces in real-time using a live camera feed. It utilizes the OpenCV library for its powerful and efficient face detection algorithms and the Pillow library for additional image processing functionalities.

This project integrates computer vision and image processing techniques to create an interactive and functional face detection system.

It uses OpenCV's Haar cascades to detect faces in each frame. Converts frames to grayscale for efficient processing. Detects faces and draws bounding boxes around them for visualization.

Further it converts these frames to pillow format for further processing of the image, applies image enhancement such as contrast adjustment using pillow and convert them back to CV format for display.


# STEPS
- Run the face_taker.py to register your face.
- Run the face_train.py to train the model to recognize your face.
- face_recognizer.py will open your default camera which scans and recognize the face.


Note: Give the name of the users in the list accordingly so that their name will appear below them.
