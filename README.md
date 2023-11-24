Face Anonymizer Project

Overview
The Face Anonymizer project is a simple Python script that utilizes OpenCV and MediaPipe to detect and anonymize faces in images, videos, or webcam feeds. The project aims to provide a privacy-enhancing solution by replacing detected faces with anonymized regions, making it suitable for scenarios where individuals' identities need to be protected.

Features
Face Detection: The script uses the face detection module from MediaPipe to locate faces in the input media.

Anonymization: Detected faces are anonymized by replacing them with blurred or pixelated regions.

Modes of Operation:

Image Mode: Anonymize faces in a given image.
Video Mode: Process a video file, anonymizing faces in each frame.
Webcam Mode: Anonymize faces in real-time from the webcam feed.

Dependencies
Python 3.x
OpenCV
MediaPipe


Notes
Ensure that you have the necessary permissions to access the webcam.

The level of face anonymization (blurring, pixelation) can be adjusted within the script.

-Freddy Fernandes