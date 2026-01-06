# Aquatic Waste Decision System
AI-based vision system to classify aquatic waste and wildlife
# AI-Based Aquatic Waste Classification System

## Overview
This project presents an AI-based vision system that classifies objects detected in water into **Waste** and **Natural/Wildlife** categories. The system acts as a decision-making engine to determine whether an object should be collected or released, supporting safe and automated aquatic waste management.

## Problem Statement
Manual waste collection in water bodies is inefficient and risks harming aquatic life. There is a need for an intelligent vision-based system that can distinguish waste from natural aquatic objects using only camera input.

## Proposed Solution
The proposed solution uses a CNN-based deep learning model (MobileNetV2) to analyze aquatic images. The model classifies objects as waste or wildlife, and based on the classification, a collect-or-release decision is generated.

## Technologies Used
- Python  
- TensorFlow / Keras  
- Google Colab  
- OpenCV  
- Gradio  
- Google Drive  

## System Workflow
1. Image acquisition (camera or upload)
2. Image preprocessing (resize and normalize)
3. CNN-based classification
4. Decision generation (Collect / Release)
5. Result display through a web interface

## Results
The model achieved high accuracy in classifying aquatic waste and wildlife and successfully generated automated collect-or-release decisions.

## Future Scope
- Real-time video stream processing
- Integration with autonomous aquatic robots
- Support for multiple waste categories

## Demo Video
(Add your Google Drive demo video link here)

## GitHub Repository
(This repository contains the source code and documentation for the project.)
