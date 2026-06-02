# 🚶 Human Detection and Automated Pedestrian Counting

This project uses **YOLOv8** (You Only Look Once Version 8) for real-time human detection and pedestrian counting from **images**, **videos**, and **live webcam feeds** using **Python** and **OpenCV**.

---

## 📌 Project Overview

The goal of this project is to detect and count pedestrians in a given media source and display the total count in real time. The system can be used for crowd monitoring, surveillance, traffic analysis, and smart city applications.

### Modes of Operation

* **pd.py** – Detects pedestrians from an image or video file.
* **realtime.py** – Detects pedestrians using a live webcam feed.

---

## 🧠 Model Used

* **Model:** YOLOv8n (Nano version for fast inference)
* **Framework:** Ultralytics YOLO
* **Language:** Python
* **Libraries:** OpenCV, NumPy, Ultralytics

---

## ✨ Features

* Real-time human detection
* Pedestrian counting
* Image and video processing
* Live webcam support
* Fast inference using YOLOv8
* Bounding box visualization
* Lightweight and easy to deploy

---

## 📸 Results

### Human Detection Output

![Output 1](output1.jpg)

### Pedestrian Counting Output

![Output 2](output2.jpg)

---

## 🗂️ Project Structure

```plaintext
Human-Detection-and-Automated-Pedestrian-Counting/

├── pd.py              # Detection from image or video file
├── realtime.py        # Live pedestrian detection via webcam
├── output1.jpg        # Sample output image
├── output2.jpg        # Sample output image
├── requirements.txt   # Dependencies
└── README.md          # Project documentation
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/bhoomika-subramanya/Human-Detection-and-Automated-Pedestrian-Counting.git

cd Human-Detection-and-Automated-Pedestrian-Counting
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Download YOLOv8 Model

The YOLOv8 model weights will be downloaded automatically during the first execution.

---

## ▶️ Usage

### Run Detection on Image/Video

```bash
python pd.py
```

### Run Real-Time Webcam Detection

```bash
python realtime.py
```

---

## 📦 Requirements

```txt
ultralytics
opencv-python
numpy
```

---

## 🎯 Applications

* Crowd Monitoring
* Smart City Surveillance
* Traffic Analysis
* Public Safety Systems
* Shopping Mall Analytics
* Event Management

---

## 🔮 Future Enhancements

* Multi-object tracking
* People flow analytics
* Heatmap generation
* Entry/exit counting
* Cloud deployment
* Dashboard visualization

---

## 🏁 Conclusion

This project demonstrates the implementation of YOLOv8 for efficient and accurate pedestrian detection and counting. By combining deep learning and computer vision techniques, the system provides a practical solution for real-time monitoring and analytics applications.
