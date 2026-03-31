AI Cheat Detector System

An AI-based system that detects cheating in uploaded interview videos using video, audio, and AI analysis.

🚀 Features
Face detection
No face detection
Multiple face detection
Phone detection using YOLOv8
Audio detection for suspicious voice
AI-based decision making using Google Gemini
Alert-based scoring system
Dashboard to store and view past results
🛠️ Technologies Used
OpenCV
Used for video processing
MediaPipe
Used for face detection
YOLOv8
Used for phone detection
Streamlit
Used for user interface
MySQL
Used for data storage
MoviePy
Used for audio extraction
📁 Project Structure
app.py
Main application file
MySQL Database
Stores user details and cheating logs
YOLOv8 Model
Automatically downloaded during execution
⚙️ Installation

Install required libraries:

pip install opencv-python numpy streamlit mysql-connector-python ultralytics mediapipe moviepy
🗄️ Database Setup

Create database:

CREATE DATABASE ai_cheat_detector;

Update credentials in app.py:

DB_USER = "root"
DB_PASSWORD = "1234"
🔑 Gemini Setup (Optional)

Set your API key:

set GEMINI_API_KEY=your_api_key
▶️ Run the Project

Start the application:

streamlit run app.py
🔐 Login Credentials
Username: admin
Password: 1234
🔄 System Flow
Upload video
Perform face detection
Perform phone detection
Perform audio analysis
Generate alerts
Calculate cheating score
Generate AI decision
Store results in database
📊 Output
Cheating score and probability
Risk level
Low
Medium
High
Final decision
Clean
Suspicious
Cheating
Alerts and reasons
🚀 Future Improvements
Real-time monitoring
Improved audio analysis
More accurate behavior detection
👥 Contributors
Vishnupriya K.M
Hamsa S.M
Raheela Banu M.R
Shaik Shekha
Nandini R.R
Shreeraksha Girish Kulkarni
📌 Note
This project is developed for educational purposes
It demonstrates AI-based cheating detection
