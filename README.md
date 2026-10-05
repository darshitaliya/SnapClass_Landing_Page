# 📸 SnapClass - AI Powered Attendance System

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://snapclassproo.streamlit.app/)
[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-Web%20Framework-lightgrey.svg)](https://flask.palletsprojects.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> **Revolutionizing the classroom with next-gen computer vision and voice biometrics.**  
> Trusted by educators for speed, accuracy, and security.

---

## 🌐 Live Application

- **🚀 Live App**: [https://snapclassproo.streamlit.app/](https://snapclassproo.streamlit.app/)
- **💻 Landing Page Repository**: [darshitaliya/SnapClass_Landing_Page](https://github.com/darshitaliya/SnapClass_Landing_Page)

---

## ✨ Features

- **📸 AI Face Analysis**: Advanced neural networks recognize student faces from a single group photo, making attendance instant and automated.
- **🎙️ Sequential Voice ID**: Students speak sequentially ("Present") and audio-AI matches their voice biometrics against stored embeddings in real-time.
- **📱 QR-Driven Roster**: Course codes generate unique QR codes for seamless and instant student onboarding.
- **📊 Real-time Dashboard**: Teachers can manage subjects, review historical logs, check confidence scores, and export detailed CSV reports.
- **🎓 Student Portal**: Students can register their biometrics once, join courses, and monitor their attendance records live.

---

## 🛠️ Tech Stack

| Domain | Technologies |
| :--- | :--- |
| **Landing Page** | Flask, HTML5, Vanilla CSS3, Modern JavaScript |
| **Core Application** | [Streamlit](https://snapclassproo.streamlit.app/) |
| **Vision AI** | FaceRecognition, Dlib, OpenCV |
| **Voice AI** | Resemblyzer, Librosa |
| **Database & Auth** | Supabase Cloud (PostgreSQL, Realtime, Storage) |

---

## 📸 Screenshots & Workflow

### 👨‍🏫 Teacher's Journey
1. **Secure Login**: Access encrypted administrative portal.
2. **Interactive Dashboard**: View course attendance and student stats.
3. **Course Management**: Create and configure subject rosters.
4. **FaceID Attendance**: Upload/capture classroom photo for automated roll-call.
5. **Voice ID Roll-call**: Audio-driven sequential verification.
6. **Actionable Records**: Download CSV logs and inspect confidence metrics.

### 🎓 Student's Journey
1. **Instant Enrollment**: Join classes using quick QR codes or shared links.
2. **Biometric Registration**: One-time voice and face profile enrollment.
3. **Personal Dashboard**: Track attendance percentages across enrolled courses.

---

## 🚀 Getting Started Locally

### Prerequisites
- Python 3.9 or higher
- Git installed on your machine

### 1. Clone the Repository
```bash
git clone https://github.com/darshitaliya/SnapClass_Landing_Page.git
cd SnapClass_Landing_Page
```

### 2. Set Up Virtual Environment
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS / Linux
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Landing Page Application
```bash
python app.py
```

Open your browser and navigate to:
```
http://localhost:5002
```

---

## 📂 Project Structure

```plaintext
SnapClass_Landing_Page/
├── app.py                 # Flask server entry point (port 5002)
├── requirements.txt       # Python dependencies (Flask, Gunicorn)
├── README.md              # Project documentation
├── .gitignore             # Git ignore configurations
├── templates/
│   └── index.html         # Responsive landing page template
└── static/
    ├── css/
    │   └── style.css      # Core styles & animations
    ├── js/
    │   └── script.js      # Scroll reveal & interactive effects
    └── img/
        ├── app_logo.png   # SnapClass brand logo
        └── demo/          # Product screenshots and flow previews
```

---

## 👨‍💻 Author

**Darsh Italiya**
- GitHub: [@darshitaliya](https://github.com/darshitaliya)
- Live App: [SnapClass AI on Streamlit](https://snapclassproo.streamlit.app/)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
