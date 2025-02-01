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
- [🚀 How It Works](#-how-it-works)
- [🛠️ Product's UML](#-product-uml)
- [📊 Dataset](#-dataset)
- [🧠 Results of the Training](#-results-of-the-training)
- [🧪 Testing](#-testing)
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
| **Trash Detection, Computer Vision** | YOLOv8 |
| **Hand Gesture Recognition** | MediaPipe |
| **Language** | Kotlin |
| **Database** | Firebase |

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

## 🛠️ **Product's UML**
### **Software Architecture Diagram**

<img width="871" alt="Screenshot 2025-02-01 at 13 27 16" src="https://github.com/user-attachments/assets/a420e2d9-4bb7-464a-b49f-66462dfb7ab3" />


### **Use Case Diagram**

<img width="617" alt="Screenshot 2025-02-01 at 13 27 56" src="https://github.com/user-attachments/assets/4445125d-a4d5-4224-adab-ac3eede9d91e" />


### **Activity Diagram**

<img width="868" alt="Screenshot 2025-02-01 at 13 26 16" src="https://github.com/user-attachments/assets/3c571c0c-5ab8-4a15-8a7c-21a600d29b4a" />

---

## 📊 **Dataset**  
The dataset contains 9 different classes: Can, Glass Bottle, Paper Cup, Peel, Plastic Bag, Plastic Bottle, Plastic Cup, Snack Wrapper, Tissue

🌍 View and download the dataset on **Roboflow**:  
➡️ [Click Here to Download the Dataset](https://app.roboflow.com/ds/JNJzUsu9vz?key=l9qvdbAKVO
)

---

## 🧠 **Results of the Training**  
<img width="670" alt="Screenshot 2025-02-01 at 13 51 51" src="https://github.com/user-attachments/assets/d2358430-f865-42bd-9c41-1b1a547bc55c" />
<img width="724" alt="Screenshot 2025-02-01 at 13 52 00" src="https://github.com/user-attachments/assets/4e1a68db-958a-4112-8442-57062fb79980" />
<img width="823" alt="Screenshot 2025-02-01 at 13 52 21" src="https://github.com/user-attachments/assets/6d0d7983-c3de-4122-882a-667abdd278a4" />

---

## 🧪 **Testing**  
<img width="844" alt="Screenshot 2025-02-01 at 13 52 52" src="https://github.com/user-attachments/assets/cd5f81da-8453-48dc-b63e-f9745774b7b7" />

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

