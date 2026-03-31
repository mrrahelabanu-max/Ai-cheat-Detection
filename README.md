AI Cheat Detector System

An AI-based system that detects cheating in uploaded interview videos using video, audio, and AI analysis.

🚀 Features
Face detection (no face / multiple faces)
Phone detection using YOLOv8
Audio detection for suspicious voice
AI-based decision making using Google Gemini
Alert-based scoring system
Dashboard to store and view past results
🛠️ Technologies Used
OpenCV – Video processing
MediaPipe – Face detection
YOLOv8 – Phone detection
Streamlit – User interface
MySQL – Data storage
MoviePy – Audio extraction
📁 Project Structure
app.py – Main application file
MySQL Database – Stores user and cheating logs
YOLOv8 model – Automatically downloaded during execution
⚙️ Installation

Install required libraries:

pip install opencv-python numpy streamlit mysql-connector-python ultralytics mediapipe moviepy
🗄️ Database Setup

Create database:

CREATE DATABASE ai_cheat_detector;

Update credentials in app.py if needed:

DB_USER = "root"
DB_PASSWORD = "1234"
🔑 Gemini Setup (Optional)

Set your API key:

set GEMINI_API_KEY=your_api_key
▶️ Run the Project
streamlit run app.py
🔐 Login Credentials
Username: admin
Password: 1234
🔄 System Flow

Upload video → Face/Phone/Audio analysis → Alerts generated → Score calculated → AI decision → Results stored in database

📊 Output
Cheating score and probability
Risk level (Low / Medium / High)
Final decision (Clean / Suspicious / Cheating)
Reasons and alerts displayed clearly
🚀 Future Improvements
Real-time live monitoring
Better audio analysis
More accurate behavior detection
👥 Contributors
Vishnupriya K.M
Hamsa S.M
Raheela Banu M.R
Shaik Shekha
Nandini R.R
Shreeraksha Girish Kulkarni
📌 Note

This project is developed for educational purposes to demonstrate AI-based cheating detection
