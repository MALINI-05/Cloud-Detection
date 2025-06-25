# ☁️ Cloud Detection using CNN

This project implements a **CNN-based cloud detection model** for satellite imagery.  
The model performs two main tasks:
1. **Classifies images** based on cloud coverage:
   - **Kept**: Minimal cloud presence
   - **Rejected**: High cloud coverage
2. **Segments the cloud regions** in the image using pixel-wise classification.

It is designed to automate **satellite image quality checks** by evaluating cloud cover percentage and providing segmentation masks for visual analysis.

---

## 🚀 Features

- Binary classification of cloud coverage (Kept / Rejected)
- Semantic segmentation of cloud pixels
- Outputs cloud coverage **percentage** with a confidence score
- Produces both segmented masks and classification labels
- Achieved **~90% segmentation accuracy** on test data
- Lightweight CNN model suitable for use in real-time and resource-limited environments (e.g., CubeSats)

---

## 🛰️ Dataset

- **Input**: Satellite RGB images (with varying levels of cloud cover)
- **Masks**: Ground truth cloud segmentation masks (binary)
- Images preprocessed to standard sizes (e.g., 128×128 or 256×256)

---

## 📁 Project Structure

