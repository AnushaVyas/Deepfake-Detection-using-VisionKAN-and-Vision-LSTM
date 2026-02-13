DeepFake Detection using Vision-KAN and Vision-LSTM::

Overview:

This project presents a deep learning-based DeepFake detection system that leverages Vision-KAN and Vision-LSTM architectures to identify manipulated facial content using spatial and temporal feature learning. The model is trained and evaluated using the DFDC (DeepFake Detection Challenge) dataset.

Problem Statement:

DeepFake technologies are increasingly used to generate manipulated media, posing serious risks in misinformation, cybersecurity, and digital identity verification. This project focuses on developing a robust detection pipeline capable of identifying facial manipulations across image sequences.

Dataset:

Dataset: DFDC (DeepFake Detection Challenge)
Total samples analyzed: 100,000+ images
Includes both real and manipulated facial data
Frames extracted from video sequences for temporal modeling

Model Architecture::

Vision-KAN:

Extracts spatial features from facial images
Captures complex nonlinear visual patterns
Enhances feature representation beyond traditional CNN models

Vision-LSTM:

Captures temporal dependencies across image frames
Models sequence-based manipulation patterns
Improves detection consistency across video frames


Methodology:

Face extraction and preprocessing
Spatial feature extraction using Vision-KAN
Temporal sequence modeling using Vision-LSTM
Model training and validation
Performance evaluation using multiple metrics

Evaluation Metrics:

Accuracy
ROC-AUC
F1-Score
Equal Error Rate (EER)


Results:
Model                      	Validation Accuracy
CNN-LSTM                    Baseline	Lower Performance
Vision-KAN + Vision-LSTM   	96.5% Accuracy

The proposed architecture demonstrates improved detection performance compared to baseline deep learning models.

Technologies Used:

Python
PyTorch
OpenCV
NumPy
Scikit-learn
Jupyter Notebook


Repository Structure
DFDC_Project.ipynb     # Main training and evaluation notebook

How To Run:

Clone repository
git clone https://github.com/AnushaVyas/Deepfake-Detection-using-VisionKAN-and-Vision-LSTM.git

Install dependencies
pip install -r requirements.txt

Run notebook
jupyter notebook

Applications:

Misinformation detection
Digital forensics
Social media content verification
AI security systems

Future Improvements:

Real-time video detection
Lightweight deployment models
Multi-modal DeepFake detection
Transformer-based architecture integration

Author:
Anusha Vyas
M.S. Computer Science – University of Texas at Arlington
