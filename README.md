# 📌 Depth Estimation using Stereo Camera (ESP32-CAM)

This project demonstrates a cost-effective real-time depth estimation system using a stereo vision setup with two ESP32-CAM modules. The system captures synchronized image streams and computes depth using OpenCV-based disparity techniques.

This is an independent project developed to explore stereo vision, embedded systems, and real-time computer vision.

---

## 🎯 Objectives

- Build a stereo vision system for real-time depth estimation  
- Enable live video streaming using ESP32-CAM over Wi-Fi  
- Perform stereo calibration and disparity-based depth computation  
- Create an affordable alternative to expensive depth cameras  

---

## 🛠️ Technologies Used

- ESP32-CAM  
- OpenCV (Python)  
- Arduino IDE  
- Stereo Vision & Camera Calibration  
- Wi-Fi Streaming  

---

## 🚘 Applications

- Obstacle detection  
- Smart parking systems  
- Autonomous navigation  
- Robotics and learning systems  

---

## 📘 Stereo_Calibration.py

### Purpose
Performs stereo camera calibration using image pairs to compute parameters required for accurate depth estimation.

### Key Features
- Uses Mask R-CNN for object detection  
- Computes disparity between stereo images  
- Estimates focal length and camera geometry  
- Outputs calibration parameters for depth calculation  

---

## 📘 Depth_Estimation.py

### Purpose
Main script for real-time depth estimation using live streams from ESP32-CAM modules.

### Key Features
- Streams video from ESP32-CAM via IP  
- Performs Mask R-CNN-based object detection  
- Calculates disparity and estimates object distance  
- Displays object labels with real-time distance (cm)  
- Supports dynamic camera setting adjustments  

---

## ⚡ Summary

This project showcases how stereo vision and deep learning can be combined with low-cost hardware to achieve real-time depth perception, making it suitable for embedded and scalable vision applications.
