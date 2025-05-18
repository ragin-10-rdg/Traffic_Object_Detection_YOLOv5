# Traffic Object Detection - YOLOv5 Implementation

## Overview

This repository hosts the **Traffic Object Detection** project which leverages the power of the YOLOv5 deep learning model to accurately detect and classify various traffic objects such as cars, trucks, pedestrians, traffic signs, and more. The project aims to enhance intelligent traffic monitoring systems by providing real-time object detection capabilities that can be integrated into smart city infrastructure, autonomous vehicles, and traffic management platforms.

By combining advanced computer vision techniques with Java programming, this repository provides a practical demonstration of applying AI to real-world challenges in traffic surveillance and safety.

---

## About Me

Hello! I’m **Ragin Karki**, an enthusiastic software developer and IT student dedicated to mastering programming and artificial intelligence. Through this project, I explore the fundamentals of Java programming alongside the cutting-edge YOLOv5 framework, deepening my understanding of object detection and computer vision applications.

This repository represents my commitment to continuous learning, problem-solving, and contributing to the open-source community with practical AI projects.

---

## Project Structure

Traffic_Object_Detection_YOLOv5/
│
├── yolov5/ # YOLOv5 submodule with detection model and scripts
│ ├── models/ # Model architectures and weights
│ ├── data/ # Dataset configurations
│ ├── utils/ # Utility scripts
│ └── train.py # Training script
│
├── src/ # Java source code for integrating detection model
│ └── (Java files)
│
├── docs/ # Documentation and usage guides
│
├── README.md # Project overview and instructions
└── .gitmodules # Git submodule configuration 
---

## Features

- Real-time traffic object detection using YOLOv5.
- Integration of Java-based application layer with AI detection backend.
- Modular design using Git submodules for easy management and updates.
- Support for training and inference with customizable datasets.
- Detailed logging and result visualization for model evaluation.

---

## Technologies & Tools Used

| Technology       | Purpose                                          |
|------------------|-------------------------------------------------|
| Java             | Application development, model integration      |
| Python           | Running and training the YOLOv5 model            |
| YOLOv5 (PyTorch) | Object detection deep learning framework         |
| Git & GitHub     | Version control and repository management        |
| Git Submodules   | Handling the YOLOv5 code as a sub-repository     |
| OpenCV           | Image/video processing and visualization         |

---

## Installation & Setup Guide

### Prerequisites

- Java JDK 11 or higher installed on your machine.
- Python 3.7+ with dependencies (PyTorch, OpenCV, numpy, etc.)
- Git installed and configured.
- IDE such as IntelliJ IDEA (for Java) and a code editor for Python.

### Steps

1. **Clone this repository with submodules:**

   ```bash
   git clone https://github.com/ragin-10-rdg/Traffic_Object_Detection_YOLOv5.git
   cd Traffic_Object_Detection_YOLOv5
   git submodule update --init --recursive
