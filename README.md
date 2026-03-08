# Helmet Detection and Image Classification Project

## Overview
This project focuses on automated worker safety monitoring at hazardous workplaces. It uses **YOLOv5** for person detection to isolate workers from the background, followed by a **ResNet50-based CNN classifier** to determine if the detected person is wearing a safety helmet.

## Dataset
The dataset consists of 640 images:
- **320 images** of workers with helmets.
- **320 images** of workers without helmets.

## Project Structure
- `Adv_CV_Project_Helmet_Detection_FullCode.ipynb`: The main notebook with complete implementation (EDA, YOLO, 4 Model Variations).
- `Adv_CV_Project_Helmet_Detection_FullCode_Final.html`: The ready-to-submit report in HTML format.
- `Adv_CV_Project_Helmet_Detection_LowCode.ipynb`: A simplified version of the project.

## Models Evaluated
1. **Model 1:** Baseline ResNet50 (Transfer Learning).
2. **Model 2:** ResNet50 with an additional Feed-Forward Neural Network (FFN).
3. **Model 3:** ResNet50 + FFN + Data Augmentation + Dropout (**Best Model**).
4. **Model 4:** ResNet50 + FFN + SGD Optimizer.

## Results
The finalized model (Model 3) achieves high accuracy and generalizability by using data augmentation and dropout to prevent overfitting.

---
*Created for the GREATLEARNING Computer Vision Project.*
