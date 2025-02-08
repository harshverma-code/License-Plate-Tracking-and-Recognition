# License-Plate-Tracking-and-Recognition

## Overview

This project is designed to track vehicles and recognize their license plates in real-time using a combination of image processing and machine learning techniques. The application uses video feeds from cameras to detect vehicles and extracts license plates for recognition.

## Features

- **Vehicle detection**: Identifies vehicles in real-time from live video streams or recorded footage.
- **License plate detection**: Locates the license plate on detected vehicles.
- **Optical Character Recognition (OCR)**: Converts the detected license plate image into readable text.
- **Database logging**: Logs recognized license plates with time stamps into a database for further analysis or tracking.
- **Alerts**: Option to trigger alerts for specific license plates (e.g., stolen vehicles, blacklisted numbers).

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - OpenCV (for video and image processing)
  - Tesseract (for Optical Character Recognition)
  - YOLO (You Only Look Once) or other object detection models for vehicle and plate detection
- **Tools**:
  - Pre-trained deep learning models (for vehicle detection)



### Prerequisites

- Python 3.x
- Install the necessary dependencies listed in `requirements.txt`:
  
  ```bash
  pip install -r requirements.txt
