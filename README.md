# WildEye: Automated Wildlife Monitoring Using Computer Vision (YOLOv9)

📌 Project Title:
Computer Vision for Automated Monitoring of Wildlife Populations in the Western Ghats Biodiversity Hotspot

🎯 Objective:
To develop a deep learning-based solution using computer vision (YOLOv9) for real-time, automated detection, identification, and counting of wildlife species in the Western Ghats, one of the world’s top biodiversity hotspots.

📁 Project Structure:
- raw_images/             -> Original camera trap images
- annotations/            -> YOLO label text files
- wildlife_dataset/       -> Auto-generated dataset splits (train/val/test)
- wildlife_dataset.yaml   -> Dataset config file for YOLO
- detect_script.py        -> Python script for object detection using YOLO
- output/                 -> Output images with detections
- README.txt              -> Project documentation

🔧 Model Used:
- YOLOv9 pretrained weights
- Custom trained on wildlife species like elephants, tigers, leopards, deer, and monkeys

📦 Requirements:
- Python 3.8+
- Ultralytics YOLOv9: `pip install ultralytics`
- OpenCV: `pip install opencv-python`

🚀 How to Train:
1. Mount your Google Drive
2. Place data under `wildlife_monitoring_project/`
3. Use this code in Colab:
