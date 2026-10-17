# Hi, I'm Musa 👋

I build data and AI products that solve real operational problems: taking a model out of the notebook and fitting it to how people actually work.

- 🌐 **Portfolio:** [musawaghu.github.io](https://musawaghu.github.io)
- 🎓 **MS in Analytics** at Georgia Tech (in progress, 2027) · **BS in Computer Science**, data science minor, Cal Poly Pomona
- 📋 **CAPM** certified (PMI)
- 🏗️ Recently focused on AI for the **architecture, engineering, and construction (AEC)** industry
- 🎯 Interested in **Forward Deployed Engineering**, **Product**, and **Data/AI** roles
- 📍 Greater Chicago Area · open to relocation

---

## Featured Projects

### 🏛️ [FIRM FLOW](https://github.com/musawaghu/FirmFlow): AI onboarding for architecture firms
**[Live demo](https://firmflow-iota.vercel.app)** · Built at an AEC hackathon with a five-person team

Turns a firm's existing onboarding manual into structured, interactive onboarding, without letting the AI invent anything. Every rewritten passage links back to its source, unsupported content is flagged for review, and a "Who do I ask?" assistant routes new hires to real people from the firm's directory.

- **My role:** lead technical architect (chose the stack), backend and database, and originated the manual enhancer and AI assistant concepts
- **Stack:** Python, FastAPI, Supabase (Postgres), Claude API, React, TypeScript, Google Cloud Run, Vercel

### 🧠 [Brain Tumor Detection](https://github.com/musawaghu/Brain-Tumor-Detection-DL): MRI classification with explainability
Fine-tuned ResNet-50 classifier that detects glioma in brain MRI scans, with Grad-CAM heatmaps that show where the model is looking and a web demo for uploading a scan.

- **Results:** 95.7% accuracy (95% CI 91.3–99.1%) and 0.989 ROC-AUC on a held-out test set. My first version reported 98%, but that was measured on the data used to pick the model, and duplicate scans crossed the splits; fixing both gave the honest number.
- **Stack:** Python, PyTorch, torchvision, scikit-learn, Gradio

### 👷 [Jobsite Check-In](https://github.com/musawaghu/Realtime-Facial-Recognition): face recognition for construction sites
Turned my real-time face recognition pipeline (MTCNN + FaceNet) into a gate check-in system for construction sites: accurate hours for payroll, a live on-site roster, and a one-click emergency muster list. Designed privacy-first, with explicit consent, embeddings only (no photos stored), and automatic deletion. Adds a head-turn liveness check and hard-hat/vest detection, and keeps working offline.

- **Results:** 99.43% accuracy on the LFW benchmark, 98.9% true-accept rate at a 0.1% false-accept rate, and 45 ms per scan on GPU (68 ms on CPU)
- **Stack:** Python, PyTorch, OpenCV, YOLO11, FastAPI, SQLite, Docker

### ⚡ [Parallel SIFT](https://github.com/musawaghu/parallel-sift): why more threads didn't help
My undergraduate senior research parallelized SIFT feature extraction for content-based image retrieval by splitting images into tiles across threads. The speedup never appeared, and the reason was Python's GIL. The rebuild benchmarks serial vs. threads vs. processes vs. free-threaded (no-GIL) Python 3.14t and shows the fix.

- **Results:** processes run 6.65× faster than serial and no-GIL threads 5.82×, cutting 50 images from 59.6 to 8.8 minutes
- **Stack:** Python, OpenCV, NumPy, multiprocessing, Python 3.14t

### 🏙️ [NYC Airbnb Analysis](https://github.com/musawaghu/Airbnb_Data_Analysis): pricing and neighborhood insights
Cleaned and modeled 2019 NYC Airbnb listings in SQLite, then explored pricing, room types, and availability by neighborhood in Python and a Power BI dashboard.

- **Finding:** 86% of hosts have a single listing, but the other 14% control a third of all listings
- **Stack:** Python, pandas, SQL, SQLite, Power BI

### 🩺 Sihha: clinical NLP middleware
**[Live site](https://sihha-sooty.vercel.app)** · Solo founder project (private repo)

Turns discharge summaries and radiology reports into structured, coded records and explainable 30-day readmission risk scores, with every fact linked back to the words it came from. A self-hosted MedGemma model means no clinical text is sent to a third-party AI service.

- **Results:** 1.000 de-identification recall and 0.964 medication-extraction F1 on synthetic notes; readmission AUC 0.671 on held-out patients, against a best published baseline of 0.667
- **Stack:** Python, MedGemma, Ollama, Presidio, scikit-learn, SHAP, React, Supabase, Google Cloud

---

## Tools I Work With

- **Languages:** Python · SQL · TypeScript
- **ML and AI:** PyTorch · scikit-learn · XGBoost · OpenCV · Claude API · prompt engineering
- **Data:** pandas · NumPy · PostgreSQL · SQLite · Supabase · Power BI · Streamlit
- **Backend and Cloud:** FastAPI · Docker · Google Cloud Run · Vercel · Git

---

## Connect

[![Portfolio](https://img.shields.io/badge/Portfolio-musawaghu.github.io-3054DE?logo=githubpages&logoColor=white)](https://musawaghu.github.io)

[LinkedIn](https://www.linkedin.com/in/musawaghu)
