TrueVision – Deepfake Detection System
TrueVision is a full-stack AI application designed to detect manipulated media in both images and videos. The system leverages deep learning and computer vision techniques to identify deepfake content and presents results through an intuitive web-based dashboard for real-time analysis.
This project focuses on media authenticity, AI security, and ethical AI, making it suitable for applications in digital forensics, cybersecurity, and content verification.

Features
Detection of deepfake and manipulated images and videos
Deep learning–based classification and inference
Real-time result visualization through a web interface
Modular and configurable ML pipeline
Scalable training using PyTorch Lightning

Tech Stack
Languages
Python
Java

Deep Learning & AI
PyTorch
PyTorch Lightning
Computer Vision

Image and video deepfake detection models
Backend
Java-based REST services

Frontend
Web-based dashboard / GUI for media upload and analysis

Data & Configuration
Custom image and video datasets
YAML-based configuration (config.yaml)
Inference & Evaluation
Model inference and classification (classify.py)
Performance evaluation (realeval.py)
Tools & DevOps
Git & GitHub
pip and requirements.txt
Virtual environments

Project Structure
├── datasets/            # Training and evaluation datasets
├── models/              # Deep learning model architectures
├── lightning_modules/   # PyTorch Lightning modules
├── inference/           # Inference pipeline
├── tools/               # Utility scripts
├── classify.py          # Media classification script
├── main_trainer.py      # Model training pipeline
├── realeval.py          # Evaluation script
├── web-app.py           # Web-based application
├── config.yaml          # Configuration file
├── requirements.txt     # Python dependencies
└── README.md

Installation
git clone <repository-url>
cd TrueVision
pip install -r requirements.txt

Usage
Train the model using main_trainer.py
Run inference using classify.p
Launch the web interface using web-app.py
Modify parameters via config.yaml

Applications
Deepfake and media forgery detection
Digital forensics
Cybersecurity and AI safety
Content authenticity verification

