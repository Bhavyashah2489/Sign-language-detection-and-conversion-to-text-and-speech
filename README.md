# Sign Language Detection and Conversion to Text and Speech

This project is a real-time sign language detection and conversion system implemented in Python, leveraging deep learning (LSTM) models and computer vision techniques. It allows for the detection of sign language gestures from live video frames, converting them into text and then into speech using natural language processing libraries. This solution aims to enhance communication accessibility for the hearing-impaired community.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)

## Introduction

Sign language is a crucial means of communication for the hearing-impaired. This project offers a technological solution to bridge the communication gap by detecting and interpreting sign language gestures in real-time. It combines deep learning techniques with computer vision and natural language processing to make communication more accessible.

## Features

- Real-time sign language detection using LSTM deep learning model.
- Conversion of detected signs into text.
- Speech synthesis of the interpreted text using gTTS library.
- User-friendly and accessible interface.
- Supports multiple sign languages and gestures.

## Requirements

To run this project, you need the following dependencies:

- Python 
- OpenCV (cv2) library
- TensorFlow or PyTorch (for LSTM model)
- gTTS (Google Text-to-Speech) library

You can install the required libraries using pip:

```bash
pip install opencv-python
pip install tensorflow  
pip install torch
pip install gTTS
```
