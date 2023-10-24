
# Face Recognition Attendance System

This is a **Python Flask Web Application** that is designed for facial recognition-based attendance management. It allows users to perform several actions related to attendance tracking and user registration. Here's a brief description of what this project does and who it's for:

1. **User Registration**: The application allows users to register by capturing images of their faces. It captures multiple images of a user's face to train a machine learning model for face recognition.

2. **Face Recognition**: The application uses a K-Nearest Neighbors (KNN) classifier for face recognition. Once trained, it can identify users based on their faces.

3. **Attendance Management**: Users can start taking attendance by using the webcam. The application recognizes faces and records the attendance with a timestamp in a CSV file for the current date.

4. **Web Interface**: The Flask web interface provides functionality for adding new users, starting attendance, and viewing attendance records. It also displays the list of recognized faces, their corresponding roll numbers, and the times when they were recognized.

5. **Data Storage**: User images and attendance records are stored in specific directories within the project directory.

6. **Training Model**: The application can train the face recognition model on the collected face data.

7. **File Management**: It manages directories for storing user images, attendance records, and model files.

This project is intended for organizations, educational institutions, or businesses that want an automated system for tracking attendance based on facial recognition. Users register their faces, and the system can identify and record their attendance when they are in front of a webcam.




## Installation

**Install Dependencies:**

```bash
- import cv2
- import os
- from flask import Flask,request,render_template
- from datetime import date
- from datetime import datetime
- import numpy as np
- from sklearn.neighbors import KNeighborsClassifier
- import pandas as pd
- import joblib
```
    
**Clone the Repository:**
## Link
https://github.com/parth-lotte/Face-Recognition-based-Attendance-System-/tree/main

## Authors

- [@ParthLotte](https://github.com/parth-lotte)

