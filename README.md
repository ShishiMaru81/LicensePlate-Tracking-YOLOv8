# LicensePlate-Tracking-YOLOv8

📌 Project Overview

This project is a real-time number plate detection system using YOLOv8 for accurate license plate detection,with deep-learning-based detection, improving accuracy and reliability. Detected plates are stored in a dataset (CSV file), and images of plates are saved for further processing.

✨ Features

🔍 Real-time detection of vehicle number plates using YOLOv8.

📷 Webcam-based image tracking for license plates.

📂 Storage of detected plates with timestamp and image filename in a CSV file.

🚀 High accuracy and robustness compared to Haar cascades.

📝 Future improvements: OCR for plate recognition, database integration, and web UI(Stremlit).

📜 Installation Guide

1️⃣ Install Required Dependencies --->  pip install ultralytics opencv-python pandas numpy

2️⃣ Download YOLOv8 Model

The pre-trained YOLOv8 model can be downloaded using:---->  from ultralytics import YOLO
---> model = YOLO("yolov8n.pt")  
📊 Dataset Structure

Detected number plates are stored in Number_plate_data.csv with the following format:

Timestamp  <------->  Filename

20250326_143212  <------->  Plate_20250326_143212.jpg
🚀 Future Improvements

✅ OCR Integration: Use EasyOCR or Tesseract to extract plate numbers.

✅ Database Logging: Store detected plates in SQLite or Firebase.

✅ Web Dashboard: Develop a Flask/Django-based dashboard for monitoring.

✅ Mobile App Integration: Create an Android/iOS app for real-time plate monitoring.

📌 Contributing

Want to contribute? Feel free to fork this repository and submit a pull request.

📄 License

This project is licensed under the MIT License. Feel free to use and modify it.
