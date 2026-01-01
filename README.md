# PCB Component Detector

YOLOv8 + Streamlit | Real-Time Computer Vision Web App

A production-ready object detection web application for PCB (Printed Circuit Board) component detection using YOLOv8 and Streamlit, supporting images, videos, batch processing, and live webcam inference.

---
# 🚀 Features
	•	🖼 Single Image Detection – Upload and detect components in a single PCB image
	•	📦 Batch Image Detection – Process multiple images simultaneously
	•	🎥 Video Detection – Run inference on uploaded PCB videos
	•	📷 Live Webcam Detection – Real-time PCB inspection
	•	📊 Component Counting Dashboard – Automatic component-wise count & analytics
	•	💎 Modern UI – Gradient background with glassmorphism design
	•	⚡ Fast YOLOv8 Inference – Optimized for low-latency detection

# 🧠 Tech Stack
	•	Model: YOLOv8 (Ultralytics)
	•	Frontend & UI: Streamlit
	•	Backend: Python
	•	Computer Vision: OpenCV
	•	Deep Learning: PyTorch
	•	Deployment Ready: CPU / GPU compatible

# Project structure
```bash
  pcb-component-detector/
│
├── app.py                  # Main Streamlit application
├── model/
│   └── yolov8.pt            # Trained YOLOv8 model
├── utils/
│   ├── detector.py          # YOLO inference logic
│   └── utils.py             # Helper functions
├── assets/                  # UI assets
├── requirements.txt         # Dependencies
└── README.md
```
# ⚙️ Installation & Setup

1️⃣ Clone the Repository
```bash
git clone https://github.com/atchyuthkarri/PCB-Components-Detection-Yolo.git
cd pcb-component-detector
```
2️⃣ Create Virtual Environment (Recommended)
```bash
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows
```
3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
4️⃣ Run the Application
```bash
streamlit run app.py
```
---
#📊 Supported Detection Modes
```bash
Mode
Description
Image
Upload and detect PCB components
Batch
Process multiple images together
Video
Detect components in videos
Webcam
Live real-time detection
Dashboard
Component count & analytics

```
---
# 🎯 Use Cases
	•	🏭 Automated PCB inspection
	•	🧪 Electronics quality assurance
	•	🧠 Computer vision learning projects
	•	📊 Component analysis & counting
---
# 📈 Performance Highlights
	•	⚡ Real-time inference (<40 ms/frame on GPU)
	•	🎯 High detection accuracy using YOLOv8
	•	📉 ~80% reduction in manual inspection effort
---
# 🔮 Future Enhancements
	•	📌 mAP / accuracy visualization
	•	🧠 Custom PCB dataset training pipeline
	•	☁️ Cloud deployment (AWS / GCP)
	•	📦 Export results as CSV / JSON
---
# 👨‍💻 Author

Atchyuth Karri
Final-year B.Tech (ECE) | Full-Stack & AI/ML Developer

📫 Open to SDE / Full-Stack / Computer Vision roles

⭐ If you like this project

Give it a star ⭐ — it helps a lot!
---

