# CrimeVision AI – Intelligent Multimodal Forensic Analysis Platform

**Platform ID:** 6ac4c9851dcde6d7857c163b  
**Category:** Generative AI | Criminal Justice & Public Safety  
**Skill Wallet Capstone Project 2**

## 📌 Project Overview
CrimeVision AI is an automated forensic intelligence platform that fuses image, video, and audio evidence to detect suspects and weapons, transcribe witness audio statements, reconstruct chronological crime timelines, provide grounded AI evidence Q&A, and generate court-admissible PDF reports.

## 🚀 Key Features
- **Visual Evidence Tagger (Epic 2):** RT-DETR visual object detection identifying threat levels, weapons, and forced entry points.
- **Witness Audio Transcription (Epic 3):** Whisper AI transcription for emergency calls and witness timeline extraction.
- **CCTV Video Analysis (Epic 4):** Video frame trajectory tracking and penal crime classification.
- **Multimodal Fusion & Grounded Chat (Epic 5):** Unified master evidence ledger with zero-hallucination RAG evidence Q&A.
- **Forensic PDF Export (Epic 6):** 1-click automated court-admissible PDF generation using ReportLab.

## 🛠️ Tech Stack
- **Frontend/App Framework:** Streamlit (Python 3.9+)
- **Document Generation:** ReportLab
- **Data Processing:** Pandas, NumPy, Pillow

## 📦 How to Run Locally
```bash
pip install -r requirements.txt
streamlit run app.py
```
