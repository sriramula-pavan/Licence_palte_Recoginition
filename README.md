# 🔍 License Plate Recognition with OpenCV & Tesseract OCR

A beginner-to-intermediate level Computer Vision project that performs **Automatic License Plate Recognition (ALPR)** using OpenCV for image processing and Tesseract OCR for text extraction. This project serves as a simple proof of concept for recognizing license plates from images — applicable in smart parking, surveillance, and traffic automation systems.

![License Plate Example](https://upload.wikimedia.org/wikipedia/commons/thumb/a/ae/License_Plate_Recognition_Sample.jpg/640px-License_Plate_Recognition_Sample.jpg)

---

## 📁 Notebook Included
- `License Plate Recognition 30.ipynb`:
  - Image preprocessing (grayscale, blur, edge detection)
  - Plate detection via contours
  - Region of interest (ROI) extraction
  - OCR with Tesseract
  - Annotated result visualization

---

## 🔧 Features
- Pure Python-based solution — no deep learning required
- Readable, step-by-step implementation
- Visual feedback with bounding boxes and recognized text
- Modular structure for easy reuse with videos or webcams

---

## 🛠️ Tech Stack
- Python 3.x
- OpenCV
- Pytesseract (Tesseract OCR wrapper for Python)
- Jupyter Notebook
- Matplotlib / cv2 for visualization

---

## 💡 Potential Applications
- 🚗 Smart parking access
- 🛣️ Highway toll monitoring
- 🚓 Police vehicle tracking
- 🛡️ Secure gated entry systems

---

## 🚀 Future Enhancements
- Real-time detection with webcam or CCTV input
- Multi-plate detection for traffic scenarios
- Deep Learning-based object detection (YOLOv5, SSD)
- Preprocessing improvements for low-light or blurry images


---

## 📦 Installation

```bash
pip install opencv-python pytesseract matplotlib

Also install Tesseract OCR on your system, and ensure it’s added to your system PATH.

