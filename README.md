
---

## **README.md for Arc Suit Classifier**
```markdown
# Arc Suit Classifier

A VIT model for classifying arc flash protective suits in high-voltage and industrial environments, ensuring PPE compliance and worker safety.

---

## 📌 Overview
This project uses a **two-stage detection system**:
1. **YOLOv8** — detects persons in the frame.
2. **Vision Transformer (ViT)** — classifies cropped person detections into:
   - `arc_suit`
   - `no_arc_suit`

The model is trained on a **custom YOLO-format dataset** FROM RoboFlow.

---

## ✨ Features
- PPE compliance verification for electrical safety
- End-to-end pipeline: detection → cropping → classification
- Confidence scores for each classification
- Comprehensive evaluation metrics

---

## 📂 Project Structure
