# 🚦 Smart Traffic Management System using AI and IoT

## 📌 Overview

An AI and IoT based adaptive traffic management system designed to optimize traffic flow dynamically using real-time vehicle detection and density estimation.

The system integrates YOLOv8 computer vision, Raspberry Pi 5, STM32F407G microcontroller, LiDAR sensing, and IoT technologies for intelligent traffic signal control.

---

## 🎯 Objectives

* Real-time traffic density detection
* Dynamic signal timing allocation
* Reduced vehicle waiting time
* Improved junction throughput
* Emergency vehicle prioritization

---

## 🧠 Technologies Used

### Hardware

* Raspberry Pi 5
* STM32F407G
* YDLIDAR X4
* Infrared Sensors
* LEDs and Breadboard

### Software

* Python
* YOLOv8
* OpenCV
* MATLAB
* Embedded C
* VS Code

---

## ⚙️ Key Features

✅ Real-time vehicle detection
✅ Adaptive traffic signal timing
✅ ROI optimized object detection
✅ Vehicle tracking and counting
✅ Density estimation
✅ IoT monitoring dashboard

---

## 🏗️ System Architecture

![Architecture](images/architecture.png)

---

## 🔄 System Flowchart

![Flowchart](images/flowchart.png)

---

## 🔌 Circuit Diagram

![Circuit](images/circuit_diagram.png)

---

## 📊 Working Principle

1. Traffic cameras capture live traffic feed.
2. YOLOv8 detects vehicles in each lane.
3. Vehicle density is calculated dynamically.
4. Traffic signals are adjusted in real time.
5. Data is uploaded to cloud dashboard.
6. Emergency vehicles can receive signal priority.

---

## 🚗 Vehicle Detection using YOLOv8

* Detects cars, buses, trucks, and bikes
* Real-time object tracking
* High accuracy density estimation
* Optimized ROI detection

---

## 📈 Optimization Parameters

### Confidence Threshold

```python
confidence = 0.4
```

### IOU Threshold

```python
iou = 0.5
```

---

## 💻 MATLAB Simulation

Traffic junction simulation performed using MATLAB for:

* Signal optimization
* Density analysis
* Throughput improvement

---

## 🔮 Future Enhancements

* Emergency vehicle priority
* Smart city integration
* Real-time CCTV integration
* Edge AI deployment
* Cloud analytics dashboard

---

## 👨‍💻 Team Members

* Sarthi Singh (1032231223)
* Vatsal Jha (1032231151)
* Tanay Kadam (1032231871)

### Guide

Dr. Vibha Utpal Patel

### Co-Guide

Dr. Raghunath Bhadade

---

## 📜 License

MIT License
