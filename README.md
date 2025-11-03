# 🪖 Helmet Detection System using YOLOv5

This project uses a deep learning-based YOLOv5 model to automatically detect whether a person in a video is wearing a helmet or not. It analyzes video footage frame-by-frame and flags frames where no helmet is detected. The system can be applied in smart surveillance, traffic monitoring, and industrial safety compliance.

## 🚀 Features
- Real-time helmet detection using YOLOv5  
- Automatically saves frames without helmets into a “suspect” folder  
- Configurable confidence threshold for detection accuracy  
- Easy to extend with custom-trained YOLOv5 models  

## 🧠 Tech Stack
- Python  
- OpenCV  
- PyTorch  
- YOLOv5  

## 📂 Project Structure

├── detector.py 

├── helmet_detection_model.pt

├── data/

├── suspect

└── README.md


## ⚙️ How to Run
1. Install dependencies:
   ```bash
   pip install torch torchvision opencv-python
   
2. Run the script:
    ```bash
   python detector.py
