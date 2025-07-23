# Face Recognition Attendance System
A Python-based attendance system that uses face recognition for automated marking of student presence. Built using `dlib`, this system ensures contactless and accurate attendance tracking using real-time webcam capture.

---

## Features
-  Face detection and recognition using `dlib`
-  Webcam integration for live face capture
-  Attendance logging with timestamps
-  CSV-based attendance report generation
-  Easy to use and customizable

---

## Tech Stack
- Language: Python 3.7
- Libraries: 'dlib', 'OpenCV', 'NumPy', 'Pandas'
- IDE: Visual Studio Code
- Platform: Ubuntu 16.04 (or compatible Linux systems)

---

## Step-by-Step Installation & Run Guide
1. Update Ubuntu System
--->
sudo apt-get update
sudo apt-get upgrade

2. Check Python and Pip Installation
--->
python3 --version    # Should be Python 3.7.x
which python3
which pip3
#If not installed:
--->
sudo apt-get install python3.7
sudo apt-get install python3-pip

3.Create and Activate Virtual Environment
--->
sudo apt install python3.7-venv
python3.7 -m venv faceenv
source faceenv/bin/activate

4. Install Required Libraries
Install dependencies in your virtual environment:
--->
pip install numpy
pip install opencv-python
pip install tk
pip install Pillow
pip install face_recognition 
pip install imutils
pip install cmake
pip install dlib
Install required system packages
#If dlib fails, run these before installing it:
--->
sudo apt-get install build-essential cmake
sudo apt-get install libopenblas-dev liblapack-dev 
sudo apt-get install libx11-dev libgtk-3-dev
sudo apt-get install python3-dev
OR 
Step 1: Install CMake
---> Go to: https://cmake.org/download
Download the Windows Installer (x64) version.
During installation:
-- Make sure to check the box that says “Add CMake to system PATH for all users”.
Step 2: Install Visual C++ Build Tools (required by dlib)
If not already installed:
---> Go to: https://visualstudio.microsoft.com/visual-cpp-build-tools/
Download and install it.
In the installer, select:
✔ "C++ build tools"
✔ Ensure that “Windows 10 SDK” or “Windows 11 SDK” is selected
Step 3: Restart VS Code (Important!)
After installing CMake and Build Tools:
Close and reopen VS Code.
Open a new terminal and check if CMake is installed by running:
cmake --version
You should see something like:
cmake version 3.x.x -- cmake is installed

Step 5: Install dlib Again
Now run:
pip install dlib
If successful, finally run:
pip install face_recognition

Final Step 6: Run Your Project Again
Open VS Code in your project folder:
code .
Activate virtual env inside VS Code terminal:
source faceenv/bin/activate
Once dlib is installed, try running your app:
python app.py

----

**NOTE:** 
Fix the Upload Path in Your Code
Open app.py and look for this code and make correction in your path according to your folder path
UPLOAD_FOLDER = 'C:/Users/amrit/Desktop/Face-Recognition-Attendance-System-main/IMAGE_FILES

---

### Ensure your webcam is connected and working.

---

📂 Project Structure
Face-Recognition-Attendance-System/
├── face_recog_dlib_file                
├── IMAGE_FILES             # Stores Face Images
├── templates               # index and upload html files stored
├── venv                    
├── app.py                  # Main application script
├── attendance.csv
└── README.md

---

**Developed By**
Amrita Bera
[Computer Engineering Graduate | Python Developer | ML Enthusiast]

