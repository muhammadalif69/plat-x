<h1 align="center">🚔 Plat-X — Smart License Plate Detection & E-Ticketing System</h1>

<p align="center">
  <i>An intelligent traffic enforcement and e-ticketing application built using</i><br>
  <b>Flask · OpenCV · YOLO · Tesseract OCR</b><br>
  — Developed to automatically detect, read, and log vehicle license plates —
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white">
  <img src="https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=opencv&logoColor=white">
  <img src="https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=yolo&logoColor=black">
  <img src="https://img.shields.io/badge/TesseractOCR-4285F4?style=for-the-badge&logo=google&logoColor=white">
  <img src="https://img.shields.io/badge/Database-PostgreSQL-blue?style=for-the-badge&logo=postgresql&logoColor=white">
</p>

---

## 💡 About the Project

**Plat-X** (*Plate Detection & e-Ticketing System*) is a smart, web-based surveillance and enforcement platform.  
It automatically **detects, recognizes, and records vehicle license plates** using computer vision and OCR technology.  

This project simulates a real-world **e-tilang (electronic ticketing)** workflow — capturing license plates, extracting text, and storing the results in a centralized database for monitoring and reporting.

---

## ⚙️ Features

✅ Real-time license plate detection using **YOLO + OpenCV**  
✅ Optical Character Recognition (OCR) via **Tesseract**  
✅ Automatic capture and text extraction from images or video streams  
✅ Web dashboard for monitoring detected plates  
✅ Multi-camera support and modular Flask architecture  
✅ Local data logging and image storage  
✅ Secure user login authentication  

---

## 🧠 Tech Stack

| Component | Technology |
|------------|-------------|
| **Backend** | Flask (Python) |
| **Frontend** | HTML, CSS, JS (Jinja Templates) |
| **Detection Engine** | YOLO + OpenCV |
| **Text Recognition** | Tesseract OCR |
| **Database** | PostgreSQL / SQLite /MySQL |
| **Utilities** | Werkzeug, Requests, SQLAlchemy |
| **Authentication** | Flask sessions |

---

## 📁 Project Structure

```plaintext
plat-x/
│
├── app.py                     # Main Flask app entry point
│
├── static/                    # Static resources (CSS, JS, images)
│   ├── css/
│   │   ├── dashboard.css
│   │   └── login.css
│   ├── img/
│   │   ├── logo.png
│   │   └── icon_logo.png
│   └── tool/
│       └── password_generator.py
│
├── templates/                 # HTML templates for web interface
│   ├── camera.html
│   ├── capture.html
│   ├── dashboard.html
│   ├── data.html
│   └── login.html
│
└── data/
    ├── images/                # Captured frames from cameras
    ├── plates_text/           # OCR text results
    └── processed_images/      # Cropped plate images
```

🚀 Installation & Usage
1. Clone the Repository
```plaintext
git clone https://github.com/muhammadalif69/plat-x.git
cd plat-x
```

2. Create a Virtual Environment
```plaintext
python -m venv venv
venv\Scripts\activate      # On Windows
# or
source venv/bin/activate   # On Linux/Mac
```

3. Install Dependencies
```plaintext
pip install -r requirements.txt
```

4. Install Tesseract OCR
```plaintext
Windows:
Download and install from Tesseract OCR GitHub

Linux (Debian/Ubuntu):
sudo apt install tesseract-ocr

Mac (Homebrew):
brew install tesseract

Make sure Tesseract is added to your system PATH.
```

5. Run the Application
```plaintext
python app.py
```

Then open your browser and visit:
```plaintext
http://127.0.0.1:5000
```

## 💬 Acknowledgments

<p align="center">
  Special thanks to <b>Politeknik Negeri Lhokseumawe (PNL)</b> for continuous guidance and inspiration,<br>
  and to everyone who has supported my growth as a web developer 🙌
</p>

<p align="center">
  ⭐ If you like this project, consider giving it a star — it means a lot!
</p>

## 📞 Contact Me

<p align="center">
  👤 <b>Muhammad Alif</b><br>
  📧 <a style="text-decoration:none;" href="mailto:62.muhammadalif@gmail.com">62.muhammadalif@gmail.com</a><br>
  🌍 <a style="text-decoration:none;" href="https://github.com/muhammadalif69">GitHub Profile</a>
</p>

<p align="center">
  <i>"Every great journey begins with a single line of code."</i><br>
  💻✨
</p>
