# Road Pothole Detection using Custom YOLOv8

## Overview

This project was developed as an additional self-initiated experiment based on the concepts learned during the internship tasks related to Computer Vision and YOLO object detection.

The objective of this project was to build a custom pothole detection system using YOLOv8 by preparing datasets, converting annotations, training the model, and performing real-time inference on road videos.

---

# Project Workflow

## 1. Dataset Preparation

* Used a pothole image dataset containing annotated road damage images.

---

## 2. Annotation Creation

* Generated normalized bounding box coordinates required for YOLO training.

---

## 3. Model Training

* Trained a pretrained YOLOv8n model on the pothole dataset.

---

# Training Results

| Metric    | Value |
| --------- | ----- |
| Precision | 0.847 |
| Recall    | 0.613 |
| mAP50     | 0.751 |
| mAP50-95  | 0.465 |

---

## 4. Inference and Detection

* Performed pothole detection on unseen test images and road videos.
* Generated output images and videos with bounding box detections.

---

## 5. Final Outcome

Successfully implemented an end-to-end custom Computer Vision pipeline involving:

* Dataset preprocessing
* Annotation conversion
* YOLO training
* Object detection
* Video inference


