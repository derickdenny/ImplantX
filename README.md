⭐ ImplantX: YOLOv8-Powered Multi-Class Dental Implant Detection

ImplantX is an advanced deep learning system designed for automated detection and classification of dental implants from radiographic images. The model is built on the YOLOv8 architecture and is capable of identifying four implant systems — Adin, Dentium, Noris, and Osstem — with high reliability. This solution is intended to support dentists in post-operative assessment, treatment planning, and situations where clinical records are unavailable.


🚀 Key Features

Multi-class implant detection trained on a curated dataset

YOLOv8-based anchor-free architecture for high precision

FastAPI backend for real-time inference

Frontend (Lovable AI) for intuitive image upload and visualization

Confidence threshold optimization for clinically interpretable predictions

Comprehensive evaluation using mAP, F1, precision–recall, and confusion matrix


🧠 Tech Stack

Deep Learning: YOLOv8 (Ultralytics)

Backend: FastAPI + Uvicorn

Frontend: React (Lovable AI)

Language: Python, JavaScript

Deployment-ready for cloud or local execution


🧪 Model Performance

mAP@0.5: 0.891

F1 Score: 0.87

Best Confidence Threshold: 0.44

Class-wise AP: 0.844–0.937


📦 Dataset

The dataset includes annotated radiographs of four implant systems.

🔗 Dataset Link: (Dataset is not included in this repository due to size constraints.)

▶️ Running the Backend
cd backend
uvicorn backend.main:app --reload

▶️ Running the Frontend
cd frontend
npm run dev


Swagger UI:
👉 http://127.0.0.1:8000/docs

📌 Future Improvements

Integration of CBCT or multi-view imaging

Expansion to additional implant systems

Enhanced transformer-based detection models

Explainable AI visualization for clinical adoption


👨‍🏫 Authors & Acknowledgments

This project was developed as part of academic work at Vellore Institute of Technology, under the guidance of Professor Vijay Mane.
