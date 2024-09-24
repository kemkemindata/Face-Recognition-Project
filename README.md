## Face Detection using Viola-Jones Algorithm
## INTRODUCTION
This project is a Face Detection App built using OpenCV and Streamlit. 
It leverages the Viola-Jones face detection algorithm to detect faces from a camera feed and draw rectangles around them. 

This app detects faces from a live camera feed using OpenCV's Haar cascades. Users can adjust detection parameters like minNeighbors and scaleFactor and the app will display and save detected faces with a bounding rectangle. The interface is powered by Streamlit, allowing for easy user interaction.

## OVERVIEW
-Detect faces using the Viola-Jones Algorithm.

-Real-time face detection through a webcam.

-Adjustable parameters for better face detection (minNeighbors and scaleFactor).

-Save detected face images to a local folder.

-Simple web interface with Streamlit.

## 🛠️ Installation

**To run this project locally, follow these steps:**

**Clone the repository**

git clone "add your github repository here"

cd face-detection-app




**Set up a virtual environment**

python -m venv venv

source venv/bin/activate    # For Linux/MacOS

venv\Scripts\activate       # For Windows




**Install the required dependencies:**

pip install -r requirements.txt

Ensure you have OpenCV installed:

You can install OpenCV using pip:

pip install opencv-python-headless


## 📄 Usage
To run the app:

**Run the Streamlit app:**

streamlit run app.py


**Instructions:**

-Open the web interface.

-Register your name.

-Adjust the detection parameters (e.g., minNeighbors, scaleFactor).

-Click Start Camera to begin face detection via webcam.

-The app will detect faces, and rectangles will be drawn around them.

-Detected face images will be saved in the detected_faces folder.

-Press q to exit the webcam feed or click the Exit button in the app.


## 🧰 Technologies Used

-Python: The programming language used to build the app.

-OpenCV: For face detection and camera feed handling.

-Streamlit: For creating the interactive web interface.

-Haar Cascade Classifier: Pre-trained model used for face detection.



