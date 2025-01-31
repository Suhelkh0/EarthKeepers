# 🌍♻️ Earth Keepers - Gamified Trash Collection App

**Earth Keepers** is a **machine learning-powered** mobile app that gamifies the process of trash collection, making environmental cleanup engaging and rewarding. Users earn points for collecting and categorizing trash in real-time using **YOLOv8 Object Detection** and **MediaPipe Hand Tracking**.

🚀 **Problem Addressed:**  
The increasing prevalence of **uncollected trash in public spaces** poses a serious environmental threat.

💡 **Solution:**  
A **fun, engaging, and gamified experience** that encourages users to participate in **waste collection efforts** using AI-powered recognition.

---

## 📜 Table of Contents
- [🛠 Features](#-features)
- [🎯 Target Audience](#-target-audience)
- [📸 Screenshots](#-screenshots)
- [🚀 How It Works](#-how-it-works)
- [📦 Installation](#-installation)
- [🛠 Technologies Used](#-technologies-used)
- [✅ Verification & Testing](#-verification--testing)
- [📈 Impact](#-impact)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)

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

## 📸 **Screenshots**
| Feature  | Screenshot |
|----------|-----------|
| **Trash Detection in Action** | ![Trash Detection](docs/images/trash-detection.png) |
| **Hand Gesture Recognition** | ![Hand Tracking](docs/images/hand-tracking.png) |
| **Gamification System** | ![Gamification](docs/images/gamification.png) |

---

## 🚀 **How It Works**
1️⃣ **Detect & Categorize Trash**  
   - Uses **YOLOv8 Object Detection** to classify waste items.  

2️⃣ **Recognize Hand Gestures**  
   - **MediaPipe Hand Tracking** detects when users grab trash.

3️⃣ **Gamified Experience**  
   - Users **earn points** based on the type & quantity of trash collected.

4️⃣ **Track Progress** *(Future Scope)*  
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

### 🔹 Clone the Repository
```sh
git clone https://github.com/yourusername/Earth-Keepers.git
cd Earth-Keepers
