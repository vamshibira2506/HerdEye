# HerdEye

### Where Every Animal Tells Its Health Story

HerdEye is a camera-based livestock health monitoring system designed for
early detection of abnormal behaviour and potential health issues in
cattle and buffaloes.

The system uses edge cameras and AI-based analysis to monitor animals
without requiring wearable devices. It identifies individual animals,
tracks behaviour such as movement and rumination, detects abnormal
patterns, and provides alerts to farmers with supporting video evidence.

---

## 🚨 Problem

Livestock diseases and abnormal health conditions are often identified
only after visible symptoms appear. This can result in:

- Delayed treatment
- Increased veterinary costs
- Reduced milk production
- Higher risk of disease spreading within the herd
- Difficulty in continuously monitoring every animal

Small and medium-scale dairy farms especially need an affordable and
easy-to-use monitoring system.

---

## 💡 Our Solution

HerdEye provides continuous camera-based monitoring of cattle and
buffaloes.

The system:

1. Identifies individual animals
2. Monitors movement and behaviour
3. Tracks rumination-related activity
4. Analyses animal sounds
5. Detects abnormal behavioural changes
6. Generates an animal-level risk indication
7. Saves abnormal behaviour clips as evidence
8. Sends alerts to the farmer
9. Allows the farmer to share evidence with a veterinarian
10. Maintains digital animal health records

---

## 🔄 How HerdEye Works

Camera
   ↓
Animal Detection & Identification
   ↓
Behaviour Monitoring
   ↓
Rumination + Movement + Sound Analysis
   ↓
Abnormality Detection
   ↓
Risk Assessment
   ↓
Farmer Alert
   ↓
Video Evidence
   ↓
Veterinarian
   ↓
Treatment / Referral
   ↓
Digital Health Record

---

## ⭐ Key Features

### 🐄 Animal Identification
Each animal can be assigned a unique Animal ID for individual monitoring.

### 📹 Camera-Based Monitoring
HerdEye uses cameras instead of requiring wearable devices on every
animal.

### 🥬 Rumination Monitoring
The system analyses mouth-area activity to estimate changes in
rumination behaviour.

### 🔊 Sound Analysis
Animal sounds can be analysed to identify patterns associated with
different behavioural or health conditions.

### 🚶 Behaviour Monitoring
Changes in movement and activity are monitored against previous
observations.

### 🚨 Early Alerts
Abnormal patterns can trigger alerts for farmer attention.

### 🎥 Video Evidence
Relevant abnormal behaviour clips can be stored so that farmers can
share evidence with veterinarians.

### 📱 Farmer Application
The farmer can view animal information, alerts and health records.

### 🌐 Multilingual Assistance
Farmer-facing alerts can support regional languages such as Telugu,
Hindi and English.

### 🩺 Digital Animal Health Records
Important observations and health events can be maintained for each
animal.

---

## 🧠 Technologies Used

### Software

- Python
- OpenCV
- Ultralytics YOLO
- TensorFlow / Keras
- Librosa
- YAMNet
- NumPy
- Pandas

### AI / ML

- YOLO for animal detection
- Computer vision for behaviour monitoring
- YAMNet for audio feature extraction
- CNN-based audio classification experiments
- Machine-learning based classification

### Hardware

- Raspberry Pi
- USB Camera
- Edge computing setup

---

## 🏗️ System Architecture

Camera
→ Edge Device
→ Animal Detection
→ Behaviour Analysis
→ Audio Analysis
→ Risk Assessment
→ Alert Generation
→ Farmer Application
→ Veterinary Support

---

## 📊 Prototype Results

The prototype has been tested using livestock audio and video data.

### Audio Dataset

| Class | Number of Samples |
|---|---:|
| Cough Sound | 11 |
| Food Anticipating Call | 100 |
| Estrus Call | 117 |
| Normal Call | 42 |
| **Total** | **270** |

YAMNet-based feature extraction and classification experiments were
conducted on the collected dataset.

> Note: Prototype accuracy should not be interpreted as clinical
> diagnostic accuracy. Further validation with larger, farm-level
> datasets and veterinary-labelled data is required.
