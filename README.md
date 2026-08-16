# Real-Time Text Recognition and Braille Conversion System

An assistive technology project that converts **printed text into physical Braille output in real time** using computer vision, OCR, Python, and Arduino.

## 📌 Overview

The **Real-Time Text Recognition and Braille Conversion System** is designed to help visually impaired users access printed text through tactile Braille.

The system captures text using a webcam, recognizes the text using **Optical Character Recognition (OCR)**, converts the detected words into their corresponding **Braille representation**, and sends the converted data to an **Arduino-based hardware system** for physical Braille output.

## ✨ Features

* 📷 Real-time text detection using a webcam
* 🔍 Optical Character Recognition using **Tesseract OCR**
* 📝 Text extraction and processing using Python
* 🔤 Automatic **Text-to-Braille conversion**
* 🔌 Arduino-based hardware integration
* ⠿ Physical Braille output from recognized text
* 🖥️ Simple graphical interface using Tkinter
* ⚡ Real-time processing and conversion

## 🔄 System Workflow

```text
        Webcam
           │
           ▼
    Image Capture
           │
           ▼
   OpenCV Processing
           │
           ▼
      Tesseract OCR
           │
           ▼
   Detected Text/Word
           │
           ▼
  Text-to-Braille Logic
           │
           ▼
   Arduino Communication
           │
           ▼
   Braille Hardware
           │
           ▼
   Physical Braille Output
```

## 🛠️ Technologies Used

### Software

* **Python**
* **OpenCV**
* **Tesseract OCR**
* **spaCy**
* **Tkinter**

### Hardware

* **Arduino**
* Webcam
* Braille output hardware

## ⚙️ How It Works

1. The webcam captures an image containing printed text.
2. OpenCV processes the captured image for text recognition.
3. Tesseract OCR identifies and extracts the text.
4. The detected word/text is processed using Python.
5. The text is converted into its corresponding Braille representation.
6. The Braille data is communicated to the Arduino.
7. The Arduino controls the connected Braille hardware.
8. The corresponding Braille pattern is produced as physical tactile output.

## 🚀 Getting Started

### Prerequisites

Make sure the following are installed:

* Python 3.7+
* Arduino IDE
* Tesseract OCR
* Arduino board
* Webcam

### 1. Clone the Repository

```bash
git clone https://github.com/MallikaSingh1773/Real-Time-Text-Recognition-and-Braille-Conversion-System-.git
cd Real-Time-Text-Recognition-and-Braille-Conversion-System-
```

### 2. Install Python Dependencies

```bash
pip install -r requirements.txt
```

If spaCy is required by the implementation:

```bash
python -m spacy download en_core_web_sm
```

### 3. Configure Arduino

1. Connect the Arduino to the Braille hardware.
2. Open the Arduino source code in Arduino IDE.
3. Select the appropriate Arduino board and serial port.
4. Upload the Arduino program.
5. Connect the Arduino to the computer.

### 4. Run the Application

```bash
python main.py
```

The application will start the webcam interface and process the detected text.

## 📁 Project Structure

```text
Real-Time-Text-Recognition-and-Braille-Conversion-System/
│
├── Arduino/
│   └── Arduino source code
│
├── Python/
│   └── Python source files
│
├── Files/
│   └── Project resources
│
├── requirements.txt
├── main.py
└── README.md
```

> The exact folder structure may vary depending on the project files included in the repository.

## 🎯 Use Case

The project demonstrates how **computer vision and hardware integration** can be combined to convert visual information into tactile information.

It can be used as a foundation for assistive systems that help visually impaired users interpret printed text through Braille.

## 🔮 Future Improvements

* Improve OCR accuracy for different fonts and lighting conditions.
* Support longer sentences and continuous text recognition.
* Add support for additional Braille characters and punctuation.
* Improve processing and hardware response time.
* Develop a more compact and portable Braille output device.
* Extend support for multiple languages.

## 👩‍💻 Author

**Mallika Singh**

Computer Science Engineering
VIT-AP University

---

⭐ If you find this project interesting, feel free to explore the repository.
