This project detects human faces and smiles in real-time using a webcam.
It uses Haar Cascade Classifiers provided by OpenCV to locate the face region and identify whether the person is smiling.
If a smile is detected, the frame can be optionally saved as an image.

******Tech Stack*******
Technology 	          Purpose
Python	         Programming & Logic
OpenCV	         Face & Smile Detection
Haar Cascades	   Pre-trained ML models for image processing

*****Project Structure***
Smile-Detection-OpenCV
│── main.py                 # Main application
│── datasets
│   ├── haarcascade_frontalface_default.xml
│   └── haarcascade_smile.xml
│── README.md
