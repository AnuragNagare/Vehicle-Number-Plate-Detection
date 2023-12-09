# Vehicle-Number-Plate-Detection

This repository contains Python code for an Automated Number Plate Recognition (ANPR) system using computer vision techniques with OpenCV and optical character recognition (OCR) powered by Tesseract.

Overview
The ANPR system is designed to extract vehicle number plates from images and extract the text information embedded on them. This repository showcases the step-by-step process involved in recognizing number plates in images and storing the information in a CSV file.

Requirements
Make sure you have the following libraries installed before running the code:

Python (>= 3.6)
OpenCV (cv2)
NumPy
imutils
pytesseract
Pandas

How to Use
Clone the repository:
git clone https://github.com/AnuragNagare/Vehicle-Number-Plate-Detection.git
cd Vehicle-Number-Plate-Detection

Place the image file (car.jpeg) you want to process in the project directory.

Run the Python script:
python test.py

View the output:
The script will display intermediate processing steps (grayscale conversion, edge detection, contour analysis, etc.) along with the final image highlighting the identified number plate.
Recognized text from the number plate will be printed in the console and stored in a data.csv 
file along with the timestamp.


https://github.com/AnuragNagare/Vehicle-Number-Plate-Detection/assets/85473989/82b71e49-1861-405f-81c9-ba416ff9db2a




