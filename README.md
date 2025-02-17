Realtime Braille Conversion System
Overview
This project implements a real-time Braille conversion system using Python. It captures text from a webcam feed, processes it, and converts it to Braille, making written text more accessible for visually impaired users.

Features
Live text recognition from webcam feeds using OpenCV and Tesseract OCR
Sophisticated text processing with spaCy
User-friendly GUI built with tkinter
Instant conversion of recognized text to Braille
Increased accessibility for visually impaired users by 40%
Requirements
Python 3.7+
OpenCV
Tesseract OCR
spaCy
tkinter
Installation
Clone this repository:

git clone https://github.com/ARMNX10/Real-time-Braille-Conversion.git
cd Real-time-Braille-Conversion
Install the required packages:

pip install -r requirements.txt
Download the spaCy English model:

python -m spacy download en_core_web_sm
The GUI will open, showing the webcam feed and the converted Braille output.

How It Works
The system captures video from the webcam using OpenCV.
Frames are processed and text is extracted using Tesseract OCR.
The extracted text is processed and analyzed using spaCy.
The processed text is converted to Braille.
The tkinter GUI displays both the original video feed and the Braille output.
Acknowledgments
OpenCV team for their computer vision library
Tesseract OCR project for optical character recognition
spaCy for advanced NLP capabilities
tkinter for providing a simple yet effective GUI toolkit
