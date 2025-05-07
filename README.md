# 🧠 Logo Detection with YOLOv2

This project implements a logo detection system using the YOLOv2 (You Only Look Once) object detection algorithm.

---

## 📁 Project Structure

```
├── 1.mp4                              # Sample input video 1
├── 2.mp4                              # Sample input video 2
├── obj.names                          # Class names for detection
├── README.md                          # Project documentation
├── yolo_logo.py                       # Python script for detection
├── YOLOv2_logo_detection_10000th_iteration.weights (ignored) # Trained weights (not uploaded)
├── yolov2_logo_detection.cfg         # YOLOv2 configuration file
```

> 🔥 Note: The `.weights` file is **not included** in this repository due to GitHub's 100MB file size limit.

---

## 🚀 How to Use

1. **Install dependencies** (Python 3.x required):

```
pip install opencv-python numpy
```

2. **Run the detection script**:

```
python yolo_logo.py
```

3. **Output**: The script processes `1.mp4` and `2.mp4`, detects logos, and displays results with bounding boxes.

---

## 🧠 Files Explained

- `yolo_logo.py`: Main script that loads the model and runs detection.
- `yolov2_logo_detection.cfg`: YOLOv2 config file tuned for logo detection.
- `obj.names`: List of logo classes to detect.
- `*.mp4`: Sample input videos for testing the model.

---

## 📦 Model Weights

To run detection, download the weights file and place it in the project folder:

**Filename**: `YOLOv2_logo_detection_10000th_iteration.weights`  
> 🚫 Not included in this repo.
> Google Drive link - https://drive.google.com/drive/folders/1tLf6zU5AESHgcX8kKWVTGqf3E4IEhMvW?usp=drive_link
---

## 📸 Demo

Coming soon — demo images or GIF of detection in action!

---

## 📝 License

This project is for educational/research purposes. Please check individual file licenses if reusing.
