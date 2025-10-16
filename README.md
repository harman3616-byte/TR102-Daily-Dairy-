# TR102-Daily-Dairy-

---

## 📅 30-Day Progress Diary
# ⚽ Football Player Face Recognition (Football Player Face Recoginisation)

**Author:** Harmanjot Singh  
**Duration:** 30 Days  
**Project Goal:** Build an ML/AI system to detect and recognize football players from images and video (webcam), including preprocessing, model training, evaluation, and a simple demo application.  

---

## 🔍 Project Overview
This project implements a full **face recognition pipeline** for football players using **Python and ML/AI libraries**. The pipeline covers:  

1. Data collection and preprocessing  
2. Face detection and alignment  
3. Feature extraction (embeddings)  
4. Classifier training and evaluation  
5. Deployment through a demo app (Streamlit / Flask)  

This repository documents **daily progress over 30 days**, including tasks, learnings, and practice exercises.

### 🗓️ Day 1 — Project Setup
- Created GitHub repo  
- Set project goals  
- Installed Python, virtual environment, and libraries  

**Practice:** Initialize GitHub repo and add README.

---

### 🗓️ Day 2 — Research & Planning
- Researched face recognition pipelines: detection → embedding → classifier → evaluation  
- Planned dataset, metrics, and final demo application  

**Practice:** Write project plan and architecture diagram.

---

### 🗓️ Day 3 — Dataset Sourcing (Part 1)
- Selected 10–15 football players  
- Collected initial images from public sources  
- Organized folders: `data/raw/<player_name>/`  

**Practice:** Download 20–30 images per player.

---

### 🗓️ Day 4 — Dataset Sourcing (Part 2)
- Continued image collection (aim for 40–100 images per player)  
- Ensured proper naming and consistency  

**Practice:** Organize images and log source URLs.

---

### 🗓️ Day 5 — Data Cleaning
- Removed duplicates and low-resolution images  
- Ensured images were suitable for training  

**Practice:** Script to remove images <100x100 px.

---

### 🗓️ Day 6 — Face Detection & Cropping
- Used `face_recognition` to detect faces  
- Cropped detected faces and saved in `data/processed/`  

**Practice:** Verify cropped faces for quality.

---

### 🗓️ Day 7 — Face Alignment & Preprocessing
- Aligned faces using eye/landmark detection  
- Resized all faces to 160x160 pixels  

**Practice:** Implement preprocessing pipeline in `src/data_prep.py`.

---

### 🗓️ Day 8 — Data Augmentation
- Applied rotation, flip, brightness, and slight shifts  
- Increased dataset diversity for better training  

**Practice:** Generate augmented images programmatically.

---

### 🗓️ Day 9 — Feature Extraction (Embeddings)
- Used `face_recognition` to extract 128-D embeddings per face  
- Saved embeddings and labels in `.pkl` format in `models/`  

**Practice:** Verify embeddings with a few sample images.

---

### 🗓️ Day 10 — Exploratory Data Analysis
- Analyzed dataset distribution and embeddings  
- Visualized with PCA/TSNE to check separability  

**Practice:** Save EDA plots in `results/`.

---

### 🗓️ Day 11 — Baseline Classifier
- Trained SVM / Logistic Regression classifier on embeddings  
- Evaluated accuracy on validation set  

**Practice:** Save classifier and record metrics.

---

### 🗓️ Day 12 — Classifier Tuning
- Tuned hyperparameters (C, kernel, scaling)  
- Improved classification accuracy  

**Practice:** Compare baseline vs tuned classifier.

---

### 🗓️ Day 13 — Test on Unseen Images
- Created hold-out test set  
- Evaluated accuracy, precision, recall, and F1 score  

**Practice:** Save test results and misclassification cases.

---

### 🗓️ Day 14 — Error Analysis & Data Fixes
- Analyzed misclassifications  
- Collected additional images for confused players  
- Re-trained classifier  

**Practice:** Document improvements.

---

### 🗓️ Day 15 — Speed & Optimization
- Measured inference time for detection + embedding + classification  
- Optimized batch processing and reduced latency  

**Practice:** Save optimized scripts in `src/`.

---

### 🗓️ Day 16 — Thresholding & Unknown Faces
- Implemented threshold for “unknown” detection  
- Verified behavior on unseen players  

**Practice:** Tune threshold using validation set.

---

### 🗓️ Day 17 — Real-time Webcam Prototype
- Built a basic script `recognize.py` to detect and label faces live  
- Tested webcam detection accuracy  

**Practice:** Record demo video.

---

### 🗓️ Day 18 — Streamlit Demo App
- Started building Streamlit app  
- Added upload image and live webcam functionality  

**Practice:** Verify UI loads correctly and shows predictions.

---

### 🗓️ Day 19 — UI Enhancements
- Added labeled bounding boxes, confidence scores  
- Showed player info (name, stats, brief description)  

**Practice:** Add sample player profiles.

---

### 🗓️ Day 20 — Robustness Testing
- Tested on different lighting, angles, occlusion  
- Noted failure cases and retrained model with new images  

**Practice:** Document results in `results/`.

---

### 🗓️ Day 21 — Expand Player Set
- Added new players or updated existing dataset  
- Fine-tuned classifier  

**Practice:** Save new model version in `models/`.

---

### 🗓️ Day 22 — Batch Inference & API (Optional)
- Added batch processing for folder images  
- Created Flask API endpoint to accept images and return predictions  

**Practice:** Test API with Postman.

---

### 🗓️ Day 23 — Model Versioning
- Saved all model artifacts with version numbers  
- Added README for models  

**Practice:** Include version tags: v1.0, v1.1, etc.

---

### 🗓️ Day 24 — Ethics & Privacy
- Added documentation for responsible usage  
- Noted limitations and ethical considerations  

**Practice:** Ensure public data only, warn about bias.

---

### 🗓️ Day 25 — Documentation & Examples
- Added step-by-step instructions for running project  
- Included example commands, demo screenshots  

**Practice:** Save sample input/output in `results/`.

---

### 🗓️ Day 26 — Testing & CI
- Added unit tests for data pipeline and inference  
- Configured GitHub Actions for automated testing  

**Practice:** Ensure all tests pass before commit.

---

### 🗓️ Day 27 — Deployment Preparation
- Added `requirements.txt`, deployment instructions  
- Tested Streamlit Cloud / Heroku deployment locally  

**Practice:** Prepare demo for submission.

---

### 🗓️ Day 28 — Final Evaluation & Metrics
- Ran full evaluation on test set  
- Documented metrics: accuracy, confusion matrix, F1 scores  

**Practice:** Save final evaluation report in `results/`.

---

### 🗓️ Day 29 — Presentation & Demo Video
- Prepared short demo video  
- Created presentation summarizing workflow, results, and learnings  

**Practice:** Upload media to `results/`.

---

### 🗓️ Day 30 — Wrap-up & Publish
- Finalized README, license, and author notes  
- Published GitHub repo and shared demo link  
- Tagged release v1.0  

**Practice:** Celebrate project completion 🎉
Also revised all major concepts covered during the training:  
Dart basics, OOP, Flutter widgets, layouts, navigation, Firebase, and API integration.  

✅ **Practice Task:**  
Finalized, tested, and documented the NotShelf project for submission.

---

## 🏁 Conclusion
This 30-day training strengthened my foundations in **Dart programming**, **Flutter UI development**, **Firebase backend**, and **API integration**.  
Through daily practice and a capstone project, I gained real-world experience in developing scalable mobile applications with modern Flutter architecture.

---
