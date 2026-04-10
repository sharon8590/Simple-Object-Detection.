<p align="center">
  <img src="assets/Untitled (1).png" alt="Simple Object Detection Banner" width="110%">
</p>

# Simple Object Detection using YOLO

A clean and minimal implementation of **real-time object detection** using **YOLO** and **OpenCV** in Python.  
This repository serves as a strong foundation for computer vision beginners and for future extensions into assistive and embedded vision systems.

---

## 🔍 Overview

This project detects common real-world objects from a live camera feed using a pre-trained YOLO model.  
It focuses on **clarity, simplicity, and reliability**, making it ideal for learning and experimentation.

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?style=for-the-badge&logo=opencv)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-lightgrey?style=for-the-badge)


---

## ✨ Features

- Real-time object detection from webcam
- YOLO pre-trained model
- OpenCV-based video processing
- Lightweight and beginner-friendly
- Easy to extend with new features

---

## 🛠️ Tech Stack

- **Python**
- **OpenCV**
- **YOLO (Ultralytics)**
- **NumPy**

---

## 📦 Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/simple-object-detection-yolo.git
cd simple-object-detection-yolo
```



### 2️⃣ Create a virtual environment (recommended)
```bash
python -m venv venv
```

#### Activate it:

##### Windows:
```bash
venv\Scripts\activate
```

##### Linux / macOS:

```bash
source venv/bin/activate
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### ▶️ Usage
Run the detection script:

```bash
python detect.py
```
A window will open showing detected objects

Press Q to exit

-

## 🧠 Detected Objects
The YOLO model can detect common objects such as:
Person
Chair
Bottle
Mobile phone
Laptop
Vehicles

--

## ⚠️ Note:
Very small objects (e.g., pens, earbuds) may not always be detected due to model and resolution limitations.

--

## ⚙️ Customization
You can improve detection by:
Switching to a larger YOLO model
Increasing input image size
Filtering specific object classes
Adjusting confidence thresholds

--

## 🚧 Limitations
Small object detection is limited
No distance or direction estimation
No audio or assistive feedback (yet)
These features are intentionally left out to keep Version 0 simple and stable.

--

## 🚀 Future Scope
This repository is designed as a base version. Possible future extensions include:
Directional guidance (left / right / center)
Distance estimation
Audio feedback
Embedded deployment (Raspberry Pi)
Assistive vision applications

--

## 📄 License
This project is licensed under the MIT License.

--

## 🙌 Acknowledgements
YOLO by Ultralytics
OpenCV community

-----
