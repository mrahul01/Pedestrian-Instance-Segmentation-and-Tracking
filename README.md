# 👤 Pedestrian Instance Segmentation and Tracking using YOLOv8

A real-time computer vision project that performs **instance-level segmentation and tracking of pedestrians** in video streams using **YOLOv8 Segmentation** and **OpenCV**.  
The system assigns persistent IDs to each detected person and visualizes precise object boundaries using segmentation masks.

---

## 🔍 Key Features
- 🧠 Instance segmentation using **YOLOv8 Segmentation (yolov8n-seg)**
- 👤 Pedestrian detection and tracking (COCO class: person)
- 🆔 Persistent ID assignment across frames
- ✂️ Accurate contour extraction from segmentation masks
- 🎥 Works on recorded street or surveillance videos

---

## 🛠️ Tech Stack
- **Python**
- **Ultralytics YOLOv8 (Segmentation)**
- **OpenCV**
- **NumPy**
- **Deep Learning–based Computer Vision**

---

## ⚙️ How It Works
1. YOLOv8 Segmentation detects pedestrians and generates pixel-level masks.
2. The tracking module assigns persistent IDs to each person.
3. Segmentation masks are resized to match frame dimensions.
4. Contours are extracted from masks and overlaid on the video.
5. Each segmented pedestrian is labeled with a unique tracking ID.

---

## ▶️ How to Run
```bash
pip install ultralytics opencv-python numpy
