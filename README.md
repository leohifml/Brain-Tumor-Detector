# Brain Tumor Detector

This repository contains a machine learning model for detecting brain tumors from MRI images, along with a FastAPI application for making predictions.

## Model

The model is a pre-trained machine learning model saved as `brain_tumor_detector-v0.0.1.pkl`. It is trained to classify MRI images into four categories:

* glioma
* meningioma
* pituitary
* notumor

## Application

The application is built using FastAPI and OpenCV (`cv2`). It provides an API endpoint for uploading an MRI image and receiving a prediction.

## Requirements

* Python 3.9+
* pip
* Virtual environment (recommended)

Install the required Python packages:

```bash
pip install -r requirements.txt
