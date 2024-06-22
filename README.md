## Face Recognition Attendance System 📸👨‍🎓👩‍🎓
Welcome to the Face Recognition Attendance System! This project utilizes Python, OpenCV, and the face_recognition library to identify faces from a webcam feed and mark attendance by recognizing pre-stored faces from images. 📷✅

## Features ✨
-Real-time face recognition from webcam feed.
-Mark attendance with timestamp in a CSV file.
-Easy to add new faces for recognition.

## Getting Started 🚀
### Prerequisites 📋
    - Python 3.x
    - OpenCV
    - face_recognition library
    - numpy

### You can install the required libraries using:
    pip install opencv-python face_recognition numpy

## Project Structure 📂
    .
    ├── ImagesAttendance     # Folder containing images for attendance
    │   ├── person1.jpg
    │   ├── person2.jpg
    │   └── ...
    ├── Attendance.csv       # CSV file to store attendance records
    ├── face_recognition_attendance.py # Main Python script
    └── README.md            # Project readme file

## Running the Project ▶️
### 1. Prepare Images:
Place images of the individuals (students/employees) in the ImagesAttendance folder. Ensure the file names are unique and meaningful as they will be used as identifiers.

### 2. Run the Script:
    python face_recognition_attendance.py
    
### 3. Attendance Marking:
The script will access the webcam and start recognizing faces. Recognized faces will be marked in Attendance.csv with the current timestamp.
