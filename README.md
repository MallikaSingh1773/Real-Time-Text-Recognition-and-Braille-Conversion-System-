# Real-Time Text Recognition and Braille Conversion System

An assistive technology project that recognizes printed text in real time and converts the detected text into **physical Braille output using an Arduino-based embedded system**.

## 📌 Overview

The **Real-Time Text Recognition and Braille Conversion System** is designed to help visually impaired users interpret printed text through tactile Braille.

The system uses a **webcam** to capture printed text, processes the image using **OpenCV and Tesseract OCR**, identifies the detected word or text, and converts it into its corresponding **Braille representation**.

The generated Braille data is then communicated to an **Arduino programmed using C/C++**, which controls the connected hardware mechanism to produce the corresponding **physical Braille pattern**.

The project combines **computer vision, OCR, text processing, C/C++ embedded programming, Arduino, and hardware-software integration** into a real-time assistive system.

---

## ✨ Features

* 📷 Real-time printed text detection using a webcam
* 🔍 Optical Character Recognition using **Tesseract OCR**
* 🖼️ Image processing using **OpenCV**
* 📝 Detection and processing of words/text
* ⠿ Automatic **Text-to-Braille conversion**
* 🔌 Communication between Python software and Arduino hardware
* ⚙️ Arduino-based embedded control using **C/C++**
* ⏱️ Real-time processing and hardware response
* 🖥️ Graphical interface using **Tkinter**
* 🤝 Integration of software and physical hardware for assistive technology

---

## 🔄 System Workflow

```text
              Webcam
                 │
                 ▼
         Image Acquisition
                 │
                 ▼
        OpenCV Image Processing
                 │
                 ▼
            Tesseract OCR
                 │
                 ▼
       Detected Word / Text
                 │
                 ▼
        Text-to-Braille Logic
                 │
                 ▼
        Python → Arduino
       Communication Layer
                 │
                 ▼
       Arduino (C/C++)
                 │
                 ▼
       Braille Hardware
                 │
                 ▼
       Physical Braille Output
```

---

## 🛠️ Technologies Used

### Programming Languages

* **Python**
* **C/C++**

### Software & Libraries

* **OpenCV** – Image processing and webcam integration
* **Tesseract OCR** – Optical character recognition
* **spaCy** – Text processing
* **Tkinter** – Graphical user interface

### Embedded & Hardware

* **Arduino**
* **Embedded C/C++**
* Hardware-software integration
* Serial communication
* Real-time hardware control
* Webcam
* Braille output mechanism

---

## ⚙️ How It Works

### 1. Image Capture

The webcam captures an image or video frame containing printed text.

### 2. Image Processing

OpenCV processes the captured frame to prepare it for OCR and improve text recognition.

### 3. Text Recognition

**Tesseract OCR** analyzes the processed image and extracts the detected text or word.

### 4. Text Processing

The recognized text is processed by the Python application before conversion.

### 5. Text-to-Braille Conversion

The detected text is mapped to its corresponding **Braille representation**.

### 6. Arduino Communication

The generated Braille data is sent from the Python application to the Arduino.

### 7. Embedded Hardware Control

The Arduino, programmed using **C/C++**, receives the Braille data and controls the connected hardware mechanism.

### 8. Physical Braille Output

The hardware produces the corresponding tactile Braille pattern, allowing the recognized text to be interpreted through touch.

---

## 🔌 Software-Hardware Integration

The project consists of two major layers:

### Software Layer

The Python application handles:

* Webcam input
* Image processing
* OCR
* Text extraction
* Text processing
* Braille conversion
* Communication with Arduino
* Graphical interface

### Embedded Hardware Layer

The Arduino handles:

* Receiving Braille data
* Processing the received information
* Controlling the Braille output mechanism
* Producing the physical tactile representation

This integration allows the system to transform **visual text → digital text → Braille data → physical tactile output**.

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following:

* Python 3.7+
* Arduino IDE
* Arduino board
* Webcam
* Tesseract OCR
* Required Python libraries
* Braille hardware/output mechanism

### 1. Clone the Repository

```bash
git clone https://github.com/MallikaSingh1773/Real-Time-Text-Recognition-and-Braille-Conversion-System-.git

cd Real-Time-Text-Recognition-and-Braille-Conversion-System-
```

### 2. Install Python Dependencies

```bash
pip install -r requirements.txt
```

If spaCy is used by the implementation, install the required model:

```bash
python -m spacy download en_core_web_sm
```

### 3. Configure Arduino

1. Connect the Arduino to the Braille hardware.
2. Open the Arduino source code in the Arduino IDE.
3. Select the appropriate Arduino board.
4. Select the correct serial/COM port.
5. Upload the Arduino program to the board.
6. Connect the Arduino to the computer.

### 4. Run the Application

```bash
python main.py
```

The application will start the webcam interface and begin processing the detected text.

---

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

---

## 🎯 Use Case

The system is designed as an **assistive technology solution** for visually impaired users.

It demonstrates how computer vision and embedded hardware can work together to convert information from the visual domain into a tactile representation.

The overall process is:

```text
Printed Text
     ↓
Camera
     ↓
OCR
     ↓
Recognized Text
     ↓
Braille Conversion
     ↓
Arduino
     ↓
Physical Braille
```

---

## 💡 Key Technical Concepts

This project demonstrates practical implementation of:

* Computer Vision
* Optical Character Recognition
* Text Processing
* Text-to-Braille Conversion
* C/C++ Programming
* Embedded Systems
* Arduino Programming
* Hardware-Software Integration
* Serial Communication
* Real-Time Processing
* Object-Oriented Programming
* Python Application Development

---

## 🔮 Future Improvements

* Improve OCR accuracy under different lighting conditions.
* Support continuous sentence-level text recognition.
* Add support for additional Braille characters and punctuation.
* Improve real-time processing speed.
* Improve communication efficiency between the software and Arduino.
* Develop a more compact and portable Braille hardware system.
* Extend the system to support multiple languages.
* Improve the physical Braille output mechanism for faster tactile response.

---

## 📚 Acknowledgments

* **OpenCV** for computer vision and image processing.
* **Tesseract OCR** for optical character recognition.
* **spaCy** for text processing.
* **Arduino** for embedded hardware control.
* **Tkinter** for the graphical user interface.

---

## 👩‍💻 Author

**Mallika Singh**

B.Tech Computer Science Engineering
VIT-AP University

---

⭐ If you find this project useful or interesting, feel free to explore the repository.
