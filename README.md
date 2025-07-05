⌚ Wrist Watch Detection with YOLOv5

> Detect wristwatches in real-time using a custom YOLOv5 object detection model.

---

## 🔍 Overview

This project demonstrates object detection of **wristwatches** using a custom-trained YOLOv5 model.  
Useful in attendance systems, security scanning, or retail monitoring environments.

---

## 📦 Features

- 🎯 Custom YOLOv5 model (`watchdetector.pt`)
- 📷 Real-time webcam-based watch detection
- 📸 Can detect wristwatches in both photos and video
- 📁 Outputs bounding boxes with confidence scores

---

## ⚙️ Tech Stack

- Python
- PyTorch
- OpenCV
- YOLOv5
- Torchvision

---

## 📁 Files

wrist-watch-detection/
├── app.py # Main detection script
├── watchdetector.pt # Custom trained YOLOv5 model
├── requirements.txt
├── dataset/ # (Optional) sample input images
└── README.md



## 🚀 Getting Started

```bash
pip install -r requirements.txt
python app.py
Make sure watchdetector.pt is in the root directory.

🧠 Use Cases
Touchless attendance systems (watch-based tracking)

Smart security systems

Fashion product detection

Retail behavior analytics

👤 Creator
Fahad Nasir
GitHub: @fahadnasir13
LinkedIn: linkedin.com/in/fahadnasir15
