# 🚚 AI-Based Truck Auditing System

An **end-to-end AI-powered vehicle inspection system** developed during my internship at [Pickkup.io](https://pickkup.io), designed to automate the auditing of trucks using Computer Vision (CV) and Optical Character Recognition (OCR).

This system integrates **part detection**, **license plate recognition**, and **damage classification** into a single automated pipeline, producing a **structured inspection checklist** to replace manual audits.

---

## 📌 Key Features
- **Part Detection** – YOLO-based deep learning model to detect truck components (e.g., headlights, mirrors, bumpers).
- **License Plate Recognition** – OCR pipeline fine-tuned for Indian number plates with custom preprocessing.
- **Damage Detection** – Multi-class damage classification with bounding box localization.
- **Audit Report Generation** – Structured checklist output for each vehicle, reducing manual effort.

---

## 🛠️ Tech Stack
**Languages & Frameworks:** Python, PyTorch, OpenCV  
**Models:** YOLO (part & damage detection), EasyOCR/Tesseract (OCR), custom preprocessing scripts  
**Tools:** FastAPI (API service), Docker (deployment), MongoDB (data storage)  

---

## 🧠 System Architecture

![Architecture](Structure.png)


---

## 📈 Results & Impact
- **Reduced manual audit time by ~35%**
- Increased **accuracy & consistency** in part condition detection
- Built modular components for **easy scaling** to other vehicle types

---

## ⚠️ Disclaimer
This repository contains **a demo implementation** using public datasets and synthetic examples for illustration purposes.  
No proprietary code, models, or data from Pickkup.io are included.

---

