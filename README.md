# Automatic-License-Plate-Recognition-with-YOLO-V8

## Overview
This project aims to detect license plates in images using the YOLOv8 model and extract text from the detected license plates. It includes the complete workflow from data preparation and model training to model deployment using OpenVINO. The main components of this project include:

1. **Data Preparation:**
   - Collect and preprocess a dataset containing images with license plates and labels for car/non-car objects.

2. **Model Training:**
   - Train the YOLOv8 model on the prepared dataset for license plate and car detection.

3. **License Plate Text Extraction:**
   - Implement Optical Character Recognition (OCR) to extract text from detected license plates.

4. **Model Selection:**
   - Evaluate multiple trained models and select the best-performing one based on detection accuracy and OCR performance.

5. **Model Format Conversion:**
   - Convert the selected model to various formats, including ONNX, and quantize it for optimized inference.

6. **OpenVINO Integration:**
   - Use the OpenVINO toolkit to optimize the model for deployment on Intel hardware.

7. **Deployment:**
   - Deploy the OpenVINO-optimized model for real-time license plate detection and text recognition.

## Getting Started
These instructions will help you get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
Before you begin, make sure you have the following prerequisites installed:

- Python 3.x

### Installation
1. Clone this repository.
   ```bash
   https://github.com/Shravani-CV/Automatic_License_Plate_Recognition_System_With_YOLO_V8_and_EasyOCR.git

2. load all the requirements.txt file
   ```bash
   pip install -r requirements.txt
   
### Vehicle License Plate Detection
   
https://github.com/user-attachments/assets/df1b2070-b7a4-4535-8501-f27e06ab96ef
