# FaceRecognizationAttendenceSystem (Artifical Intelligence)

An AI‑powered attendance tracking system using face recognition, designed to automate attendance marking using machine learning and computer vision. Built with Python, this system captures, trains, recognizes faces and logs attendance in a structured, data‑driven way — eliminating manual entry and improving accuracy.

📌 Live Demo 

https://github.com/dhrumilc2005-a11y/FaceRecognizationAttendenceSystem.git

📖 Table of Contents

🧠 Introduction

🚀 Key Features

📋 Technologies Used

📁 Project Structure

🐍 Getting Started

🧠 Face Recognition (AI & CV)

📊 Data Science Logging & Analytics

📊 Attendance Output & Reports

🔧 Customization

🛠 Troubleshooting

🤝 Contributing

📄 License

🧠 Introduction

Traditional attendance systems (roll‑call, ID cards, manual logs) are error‑prone and time‑consuming. With modern computer vision and AI techniques, we can automate this process using facial biometrics. This project uses face detection, face recognition models, and Python libraries to:

Detect faces in real‑time (via webcam or camera feed)

Recognize known faces from a dataset

Log attendance with timestamps and metadata

Generate structured attendance data for analysis

🚀 Key Features

✔ User Dataset Creation – Capture multiple face images per person to train models 
GitHub

✔ Face Detection & Recognition – Real‑time recognition using state‑of‑the‑art AI models 
GitHub

✔ Automated Attendance Logging – Saves name, time, and attendance status in CSV or database 


✔ Reporting & Analytics – Load CSVs into Pandas for attendance statistics & insights
✔ Extensible Python Architecture – Modular scripts for training, recognition, and analytics

Clone the Repository
git clone https://github.com/dhrumilc2005-a11y/FaceRecognizationAttendenceSystem.git
cd FaceRecognizationAttendenceSystem

Set Up Python Environment

Make sure you have Python 3.8+:

python3 --version

Create a virtual environment:

python3 -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows


Install Dependencies
pip install -r requirements.txt


Typical dependencies include:

opencv-python
face_recognition
numpy
pandas
matplotlib

🧠 Face Recognition (AI & CV)
🧩 Face Detection

The system uses libraries like OpenCV and face_recognition to detect faces within image frames. Detected faces are aligned and processed before recognition.

🧠 Face Embeddings & Recognition

Face recognition typically works by converting each face into a numerical vector (embedding) using pre‑trained models such as FaceNet or dlib embeddings. These embeddings are then compared to known face embeddings to find a match.

This approach is common in open‑source attendance projects where each person’s face is registered and then recognized during attendance capture.
