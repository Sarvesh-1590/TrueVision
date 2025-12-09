🧠 TrueVision

A deepfake detection system using PyTorch and EfficientNet-B0, with a web interface for real-time image and video analysis.

🌟 Features

EfficientNet-B0 deep learning model for real/fake classification

Supports images (.jpg, .png) and videos (.mp4, .mov)

Interactive Gradio web interface

Real-time video frame analysis

PyTorch Lightning training pipeline

Model export: PyTorch (.pt) & ONNX

🚀 Quick Start
Prerequisites

Python 3.8+

CUDA GPU (optional, recommended for training)

Usage

Web App:

python web-app.py


Command-line Classification:

python classify.py --image path/to/image.jpg


Video Analysis:

python inference/video_inference.py --video path/to/video.mp4

📁 Project Structure
├── web-app.py            # Web interface
├── main_trainer.py       # Training script
├── classify.py           # Image classification
├── config.yaml           # Training config
├── models/               # Model weights
├── data/                 # Datasets
├── tools/                # Dataset preparation utilities
└── inference/            # Video & ONNX processing

🛠️ Model Details

Backbone: EfficientNet-B0

Classifier: Binary (Real/Fake)

Input: 224×224 RGB images

Output: Confidence scores

🤝 Contributing

Fork the repo

Create a branch: git checkout -b feature-name

Commit: git commit -m "Description"

Push: git push origin feature-name

Open a Pull Request

🙏 Acknowledgments

EfficientNet by Google Research

PyTorch Lightning

Gradio for web interface

This version:

Cuts down dataset details (keep links separately if needed)

Removes repetitive installation/training instructions

Focuses on usage, structure, and contributions
