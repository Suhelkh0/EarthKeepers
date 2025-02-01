# 🌍♻️ Earth Keepers - Gamified Trash Collection App

**Earth Keepers** is a **machine learning-powered** mobile app that gamifies the process of trash collection, making environmental cleanup engaging and rewarding. Users earn points for collecting and categorizing trash in real-time using **YOLOv8 Object Detection** and **MediaPipe Hand Tracking**.

🚀 **Problem Addressed:**  
The increasing prevalence of **uncollected trash in public spaces** poses a serious environmental threat.

💡 **Solution:**  
A **fun, engaging, and gamified experience** that encourages users to participate in **waste collection efforts** using AI-powered recognition.


---

## A Video of the Game

🔗 **Link to the video on Drive**: [Earth Keepers Video](https://drive.google.com/file/d/153BKVpO8u6qMvd_Xfvm-vfoBHvbb_BWf/view?usp=sharing
)

---

## 📜 Table of Contents
- [🛠 Features](#-features)
- [🎯 Target Audience](#-target-audience)
- [📸 Technologies Used](#-technologies-used)
- [📸 Product Architecture](#-product's-uml)
- [🚀 How It Works](#-how-it-works)
- [📦 Installation](#-installation)

---

## 🛠 **Features**
✔️ **AI-Powered Trash Detection** – Uses **YOLOv8 CNNs** for accurate object recognition  
✔️ **Hand Gesture Recognition** – **MediaPipe Hand Tracking** enhances user interaction  
✔️ **Gamification System** – Users **earn points** based on collected trash  
✔️ **Real-Time Processing** – Detects trash and categorizes items instantly  
✔️ **Community Leaderboards** *(Future Scope)* – Encourages friendly competition  

---

## 🎯 **Target Audience**
- **Environmentally conscious individuals**
- **Community groups** promoting clean spaces
- **Volunteers & sustainability enthusiasts**
- **Gamers** who enjoy interactive challenges with real-world impact

---

## 📸 **Technologies Used**
| Feature  | Screenshot |
|----------|-----------|
| **Trash Detection** | YOLOv8 |
| **Hand Gesture Recognition** | MediaPipe |
| **Language** | Kotlin |
| **Database** | Firebase |

---

## 🚀 **Product's UML**
### **Software Architecture Diagram**

<img width="500" alt="Software Architecture Diagram" src="https://github.com/user-attachments/assets/a70a2996-154c-450f-872b-f0e2333d9263" />

### **Use Case Diagram**

<img width="500" alt="Use Case Diagram" src="https://github.com/user-attachments/assets/b3e7d57e-f06a-4f88-9cca-d1817b21c88b" />

---

## 🚀 **How It Works**
For the full description of the project see the files in the repository:
- Capstone_Project_Phase_A.docx
- Capstone_Project_Phase_B.docx

1️⃣ **Detect & Categorize Trash**  
   - Uses **YOLOv8 Object Detection** to classify waste items.  

2️⃣ **Recognize Hand Gestures**  
   - **MediaPipe Hand Tracking** detects when users grab trash.

3️⃣ **Gamified Experience**  
   - Users **earn points** based on the type & quantity of trash collected.

4️⃣ **Track Progress** 
   - A **leaderboard system** to encourage community participation.

---

## 📦 **Installation**
### 🔹 Prerequisites
Ensure you have the following installed:
- Python 3.8+ (`python --version`)
- OpenCV (`pip install opencv-python`)
- PyTorch (`pip install torch torchvision torchaudio`)
- YOLOv8 (`pip install ultralytics`)
- MediaPipe (`pip install mediapipe`)

Also you must download the trained model of the YOLOv8 by clicking on this link: ➡️ [Click Here to Download `model.tflite`](https://github.com/Suhelkh0/EarthKeepers/releases/latest/download/model.tflite)
You should place model.tflite in this exact path app/src/main/assets/

