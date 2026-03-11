# 🕵️‍♂️ Karthikeya-7-Venkata — OBJECT DETECTION WITH YOLOv7 & EXPLAINABILITY

Real-time object detection with **YOLOv7** and **Grad-CAM explainability**, providing **class-wise counts**, **performance metrics**, and **attention heatmaps** for enhanced model interpretability.

---

## 📁 Files Included

**YOLOv7 weights/config/labels:**  
- Pre-trained model files: `yolov7.weights`, `yolov7.cfg`, `coco.names`

**Video file:**  
- Example input video: `cycling.mp4`

**Python scripts:**  
- `yolov7_video_detection.py` — YOLOv7 video object detection  
- `grad_cam_video.py` — Grad-CAM visualization for attention/explainability  
- `metrics.py` — Performance evaluation (precision, recall, F1-score, mAP)  
- `visualization.py` — Plots class-wise detection counts and Grad-CAM heatmaps  

---

## 📊 Key Features

- 🚀 Real-time object detection on videos using YOLOv7  
- 📈 Class-wise detection counts visualization  
- 📌 Precision, Recall, F1-score, and mAP metrics calculation  
- 🔥 Grad-CAM for explainable AI: visualizes areas of attention in video frames  
- 🖼 Frame-wise and combined average heatmaps  
- ⚡ Supports GPU acceleration with CUDA if available  

---

## 🛠 Requirements

- Python 3.8+  
- OpenCV  
- PyTorch & torchvision  
- Matplotlib  
- Optional: CUDA-enabled GPU for faster inference  

---

## 📊 Results & Observations

- ✅ YOLOv7 accurately detects objects in video frames with confidence scores  
- 🔥 Grad-CAM highlights the regions contributing to model predictions  
- 📊 Class-wise detection plots show frequency of detected object classes  
- 📈 Performance metrics (precision, recall, F1-score, mAP) provide quantitative evaluation  

---

## ✅ Conclusion

- YOLOv7 provides high-accuracy object detection  
- Grad-CAM adds explainability, showing model attention  
- Combining detection and explainability enhances transparency and interpretability  

---

## 🔮 Future Work

- 🎥 Support multiple videos or live camera feeds  
- 🤖 Integrate additional attention mechanisms or transformers for detection  
- 🌐 Develop a web-based dashboard for real-time monitoring and Grad-CAM visualization  
- ⚡ Improve performance metrics using larger datasets and object tracking  
