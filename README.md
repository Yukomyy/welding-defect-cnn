# Welding Defect Detector — Real-Time CNN Visual Inspection

Automated web-based visual inspection system utilizing a Convolutional Neural Network (CNN) to classify industrial welding surface quality in real time via camera and video streams.

---

## Key Features

- **Multi-Class CNN Classification:** Real-time inference pipeline classifying weld surfaces into **Good Weld**, **Bad Weld**, and **Defect** categories with live confidence percentage scoring.
- **Dual Input Stream Support:** Supports both local **PC Webcam** feeds and **Mobile IP Camera** streams for flexible on-site industrial Quality Control (QC) sorting.
- **Interactive Web Interface:** Browser-based monitoring dashboard displaying live bounding/classification overlays, inference status, and inspection logs.

---

## Tech Stack

- **Core Language:** Python 3.x
- **Deep Learning & Computer Vision:** Convolutional Neural Network (CNN), TensorFlow / Keras, OpenCV (`cv2`), NumPy
- **Web Interface:** Python Web UI / Streaming Server, HTML5, CSS3, JavaScript

---

## System Architecture

1. **Frame Capture & Preprocessing:** Captures continuous video frames from local USB webcams or remote IP camera endpoints, resizing and normalizing pixel tensors for model input.
2. **CNN Inference Engine:** Evaluates normalized frames against the trained multi-class convolutional model to compute class probabilities (`Good Weld`, `Bad Weld`, `Defect`).
3. **Real-Time Telemetry Overlay:** Renders the predicted classification label and confidence score onto the output stream for immediate operator feedback.

---

## System Screenshots

*(Drag & drop 2–3 application screenshots from your portfolio/CV here via the GitHub web editor)*

---

## Author

**Fahmi Irfan** — D4 Sistem Informasi, Politeknik STMI Jakarta
