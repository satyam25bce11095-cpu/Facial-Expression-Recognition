🤖 Real-Time Emotion Detection using OpenCV and FER
This Python script utilizes your webcam to perform Real-Time Facial Expression Recognition (FER). It detects faces, identifies the dominant emotion, and displays the results directly on the screen.
📋 Prerequisites
To run this script successfully, you must have Python 3 and the following libraries installed on your system:

OpenCV (opencv-python): For video capture and display.

FER (fer): For the Facial Expression Recognition model.

TensorFlow/Keras: Dependencies required by the fer library for the underlying models.

You can install all necessary dependencies using a single command:

Bash
pip install opencv-python fer tensorflow keras

🚀 How to Run
Save the Code: Save the provided Python code into a file, for example, emotion_detector.py.

Connect Webcam: Ensure your default webcam (index 0) is connected and operational.

Execute the Script: Run the file from your command line or terminal:

Bash
python emotion_detector.py

✨ Key Features
Real-Time Processing: Continuously processes the video stream frame-by-frame from the live camera feed.

Robust Face Detection: Uses the MTCNN (Multi-task Cascaded Convolutional Networks) for accurate face localization prior to emotion analysis.

Emotion Display: Draws a green bounding box around the detected face and displays the dominant emotion (e.g., happy, sad, angry) along with its confidence score.

🛑 How to Exit
While the video window is active, press the q key on your keyboard. This will break the processing loop, release the camera resource, and close all windows.
