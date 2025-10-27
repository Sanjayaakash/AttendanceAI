# 🧠 LIVE VIDEO FEED BASED ONLINE ATTENDANCE CAPTURING TOOL

## 📘 Overview  
The **Live Video Feed Based Online Attendance Capturing Tool** is an AI-powered attendance system that automates attendance marking using **real-time facial recognition**.  
It uses **Deep Learning** models to detect and recognize faces from a live video stream and automatically updates attendance records.  
This project eliminates the need for manual attendance processes and provides a fast, contactless, and efficient solution for classrooms, offices, and institutions.

---

## 🚀 Features  
- 🎥 **Real-time video capture** using webcam feed.  
- 🧩 **Face detection** using YOLOv8 (You Only Look Once) for accurate detection.  
- 🧠 **Face recognition** powered by ArcFace and CosFace deep learning models.  
- 📂 **Dataset management** – Automatically captures and stores new user faces for training.  
- ✅ **Attendance marking** – Recognized faces are logged with timestamps in the attendance sheet.  
- 💾 **Scalable and extendable** for multiple users or networked deployment.  

---

## 🧰 Tech Stack  
| Component | Technology Used |
|------------|----------------|
| **Programming Language** | Python |
| **Face Detection** | YOLOv8 |
| **Face Recognition** | ArcFace, CosFace |
| **Deep Learning Frameworks** | PyTorch / TensorFlow |
| **Data Handling** | NumPy, OpenCV |
| **Environment** | Jupyter Notebook / Python Script |

---

## ⚙️ How It Works  
1. **Training Phase**  
   - The system loads the dataset containing user face images.  
   - The model is trained using ArcFace and CosFace to learn unique facial embeddings.  

2. **Registration Phase**  
   - New users are registered by capturing their face using a live video feed.  
   - The system stores the images in the dataset folder for future recognition.  

3. **Recognition & Attendance Phase**  
   - When a live feed is initiated, YOLOv8 detects faces in real time.  
   - The recognition model compares the detected face embeddings with stored data.  
   - If a match is found, attendance is automatically marked with the user’s name and timestamp.  

---

## 🖥️ Setup and Installation  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/<your-username>/Live-Attendance-Capturing-Tool.git
cd Live-Attendance-Capturing-Tool
```

### 2️⃣ Install Dependencies  
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Project  
```bash
python main.py
```
or if using a Jupyter Notebook:  
```bash
jupyter notebook Proj.ipynb
```

---

## 📊 Output  
- Displays a **live webcam window** with bounding boxes around detected faces.  
- Shows the **recognized name and confidence score**.  
- Logs the attendance in a `.csv` file or database with timestamp.  


---

## 🧩 Future Enhancements  
- Integration with **cloud database** or **Firebase** for centralized attendance storage.  
- Development of a **web dashboard** for admin management.  
- Support for **multi-camera input** and **edge AI devices**.  

---

## 👩‍💻 Author  
**Developed by:** Sanjayaakash T, Rupesh kumar M  
🎓 *Mini Project – Panimalar Engineering College
📅 *Academic Year: 2025*
