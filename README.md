🧠 TrueVision – Deepfake Detection System

TrueVision is a full-stack AI-based application designed to detect deepfake and manipulated media in both images and videos. The system leverages deep learning and computer vision techniques to analyze media authenticity and presents results through an intuitive web-based dashboard for real-time analysis.

This project emphasizes media integrity, AI security, and ethical AI, making it suitable for applications in digital forensics, cybersecurity, and content authenticity verification.

🔍 Core Features

🖼️ 1. Image Deepfake Detection

Detects AI-generated and manipulated images

Uses deep learning–based classification models

Supports fast and accurate inference

🎥 2. Video Deepfake Detection

Analyzes video frames for manipulation patterns

Performs frame-level and aggregated classification

Designed for both short clips and longer videos

🧠 3. Model Training & Management

Modular training pipeline built with PyTorch Lightning

Scalable and configurable model training

Supports experimentation via YAML-based configuration

🌐 4. Web-Based Analysis Dashboard

Upload images or videos for authenticity analysis

Displays detection results in real time

User-friendly interface for technical and non-technical users

📊 5. Inference & Evaluation

Dedicated scripts for model inference and testing

Performance evaluation and accuracy assessment

Designed for research and prototype deployment

⚙️ Tech Stack
Component	Technology Used

Programming Languages	Python, Java

Deep Learning Framework	PyTorch

Training Framework	PyTorch Lightning

Computer Vision	Image & Video Processing Models

Backend Services	Java-based REST APIs

Frontend	Web-based Dashboard / GUI

Data Handling	Custom Image & Video Datasets

Configuration	YAML (config.yaml)

Inference Tools	classify.py, realeval.py

Version Control	Git & GitHub

Environment Management	pip, requirements.txt, Virtual Environments

🚀 Installation
git clone <repository-url>
cd TrueVision
pip install -r requirements.txt

▶️ Usage

🧪 Train the model

python main_trainer.py


🔍 Run inference

python classify.py


🌐 Launch the web interface

python web-app.py


⚙️ Modify model and pipeline parameters using config.yaml

🎯 Applications

Deepfake and media forgery detection

Digital forensics and investigation

Cybersecurity and AI safety

Content authenticity verification

📌 Future Enhancements

Real-time video stream analysis

Support for additional deepfake datasets

Model optimization for faster inference

Cloud-based deployment and scalability
