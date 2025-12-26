# Custom-Trained-Yolo-Model

#Custom YOLO Training for Vehicle Detection

This repository demonstrates the complete workflow for custom vehicle detection using a YOLO-based object detection model, with dataset annotation and preprocessing handled through Roboflow.

# Project Purpose

The main goal of this project is to explore how a custom-trained YOLO model can effectively detect vehicles in road traffic scenes using a relatively small, domain-specific dataset. Instead of relying solely on large, generic datasets, this project shows how tailored data annotation and augmentation can significantly improve model performance for specific traffic environments.

# Dataset & Annotation

Road traffic images were manually annotated using Roboflow
Bounding boxes were created for vehicle classes such as cars, buses, trucks, and bikes (depending on dataset scope)

Roboflow was also used for:
Image preprocessing (resizing, auto-orientation)
Data augmentation (brightness, blur, motion blur, mosaic, etc.)
Exporting the dataset in YOLO-compatible format

#Model Training

A YOLO model was trained on the annotated dataset

The training process focuses on:
1. Learning vehicle appearance at different scales
2. Handling lighting variations, motion blur, and partial occlusions
3. Improving real-world robustness through controlled augmentation

# This project is useful for:

Learning end-to-end custom object detection pipelines
Understanding how Roboflow simplifies annotation and augmentation
Training YOLO models with limited but high-quality data

# Applications:

Traffic monitoring
Intelligent transportation systems
Smart city solutions
Autonomous and assisted driving research

# Key Takeaway

Even with a modest number of images, combining accurate annotations, realistic augmentations, and YOLO’s efficient architecture can produce a strong baseline vehicle detection model tailored to specific road environments.
