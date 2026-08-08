# Verified AI, OCR & Computer Vision Libraries

---

## Repository 1

### Name
OpenCV

### GitHub
https://github.com/opencv/opencv

### Status
Verified

### Rating
★★★★★

### Purpose
Industry-standard computer vision library.

### Features
- Camera integration
- Face detection
- Object detection
- Image processing
- Video processing
- Motion detection
- Image enhancement

### Claude Should Study
- Camera access
- Face detection
- Image processing
- Video capture
- Computer vision

### Why We Chose It
OpenCV is the most widely used computer vision library and provides the foundation for AI-powered desktop applications.

---

## Repository 2

### Name
EasyOCR

### GitHub
https://github.com/JaidedAI/EasyOCR

### Status
Verified

### Rating
★★★★★

### Purpose
Extract text from images and scanned documents.

### Features
- OCR
- Multi-language support
- Handwritten text support
- Image recognition
- PDF image extraction

### Claude Should Study
- OCR
- Document scanning
- Image text extraction
- Form processing

### Why We Chose It
Allows applications to read printed text from scanned admission letters, transcripts, certificates and identity documents.

---

## Repository 3

### Name
Tesseract OCR

### GitHub
https://github.com/tesseract-ocr/tesseract

### Status
Verified

### Rating
★★★★★

### Purpose
Open-source Optical Character Recognition engine.

### Features
- OCR
- Multi-language support
- PDF OCR
- Image OCR
- High accuracy

### Claude Should Study
- OCR engine
- Language models
- Document recognition

### Why We Chose It
One of the most mature OCR engines available and suitable for offline desktop applications.

---

## Repository 4

### Name
pyzbar

### GitHub
https://github.com/NaturalHistoryMuseum/pyzbar

### Status
Verified

### Rating
★★★★★

### Purpose
Barcode and QR Code reader.

### Features
- QR Code scanning
- Barcode scanning
- Camera support
- Image decoding

### Claude Should Study
- QR scanning
- Barcode recognition
- Camera integration

### Why We Chose It
Useful for student ID verification, transcript verification and inventory systems.

---

## Repository 5

### Name
YOLOv5

### GitHub
https://github.com/ultralytics/yolov5

### Status
Verified

### Rating
★★★★★

### Purpose
Real-time object detection.

### Features
- Object detection
- Image recognition
- Video analysis
- AI inference

### Claude Should Study
- AI object detection
- Image analysis
- Video processing

### Why We Chose It
Provides powerful object detection capabilities for AI-enhanced desktop applications.

---

## Repository 6

### Name
MediaPipe

### GitHub
https://github.com/google-ai-edge/mediapipe

### Status
Verified

### Rating
★★★★★

### Purpose
Cross-platform machine learning framework.

### Features
- Face detection
- Hand tracking
- Pose estimation
- Gesture recognition

### Claude Should Study
- AI pipelines
- Gesture recognition
- Face tracking
- Real-time processing

### Why We Chose It
Excellent for applications requiring advanced camera interaction and human-computer interaction.

---

## Repository 7

### Name
PaddleOCR

### GitHub
https://github.com/PaddlePaddle/PaddleOCR

### Status
Verified

### Rating
★★★★★

### Purpose
High-performance OCR toolkit.

### Features
- OCR
- Table recognition
- Document layout analysis
- Multi-language support

### Claude Should Study
- Advanced OCR
- Table extraction
- Document parsing

### Why We Chose It
Ideal for extracting structured information from complex documents.

---

## Summary

### Primary Recommendation
- OpenCV
- EasyOCR
- Tesseract OCR

### Secondary Recommendation
- PaddleOCR
- MediaPipe
- pyzbar
- YOLOv5

### Best Use Cases
- Student ID verification
- Transcript scanning
- Admission letter processing
- QR Code verification
- Barcode scanning
- Face recognition
- Camera integration
- Document digitisation
- AI-powered image analysis

---

# AI, OCR and Computer Vision Standards

Claude should add AI features only where they solve a clear application need.

AI modules should remain separate from the main user interface and business logic.

## AI Architecture

Use the following structure:

```text
User Interface
      |
AI Controller
      |
AI Service
      |
AI Model
      |
Data / Document
