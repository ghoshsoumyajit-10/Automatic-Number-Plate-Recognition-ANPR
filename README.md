# Automatic-Number-Plate-Recognition-ANPR
Automatic Number Plate Recognition (ANPR) system using OpenCV, dlib, PyTorch, imutils, and NumPy for intelligent vehicle identification.

An Automatic Number Plate Recognition (ANPR) system developed using computer vision and deep learning–ready pipelines to detect and localize vehicle license plates from images or video frames.

This project demonstrates how classical vision techniques integrate with modern frameworks (PyTorch) to build scalable intelligent transportation solutions.

🔧 Tech Stack & Libraries

Python

OpenCV (cv2) – Image processing, edge detection, contour analysis

dlib – Object detection utilities and shape analysis

PyTorch – Model-ready deep learning framework for future plate/OCR extensions

imutils – Image resizing, rotation, and contour handling

NumPy – Numerical computations

Matplotlib – Visualization and debugging

🧠 System Pipeline

Image Acquisition

Input vehicle images or frames

Pre-processing

Grayscale conversion

Noise reduction

Edge detection

Plate Candidate Detection

Contour extraction using OpenCV + imutils

Region filtering based on geometry

License Plate Localization

ROI extraction and bounding box refinement

Robust handling of scale and orientation

Visualization & Analysis

Bounding box overlays

Step-by-step visualization using Matplotlib

Deep Learning Ready

PyTorch integrated for future OCR / CNN-based enhancements

Automatic-Number-Plate-Recognition-ANPR/
│
├── ANPR.ipynb              # Full detection pipeline (Jupyter)
├── sample_images/          # Input vehicle images
├── outputs/                # Detected plate results
├── requirements.txt        # Project dependencies
└── README.md               # Documentation

🎯 Real-World Applications

This ANPR system is directly applicable to:

🚦 Traffic & Signal Monitoring

🅿️ Automated Parking Systems

🚓 Law Enforcement & Surveillance

🏢 Secure Entry Systems

🌆 Smart City Infrastructure

🛣️ Toll Collection Automation

📊 Vehicle Analytics Platforms

💡 Key Highlights (Interview-Ready)

Combines classical computer vision + modern deep learning frameworks

Uses imutils for clean, readable CV pipelines

PyTorch integration enables future CNN / OCR expansion

Demonstrates strong understanding of image preprocessing & ROI extraction

Suitable for both research and production-level extension

🚀 Future Enhancements

Integrate OCR (Tesseract / EasyOCR / CRNN via PyTorch)

Add real-time video stream processing

Improve robustness under poor lighting & motion blur

Deploy as an API or edge-based system

👤 Author

Soumyajit Ghosh

“This project demonstrates how classical computer vision pipelines can be seamlessly extended with PyTorch-based deep learning models to build scalable ANPR systems.”
