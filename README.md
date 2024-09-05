# Realtime-face-and-gesture-recognition

This project is a real-time face and gesture recognition application using Streamlit, OpenCV, DeepFace, and MediaPipe. It allows you to detect faces and gestures from a webcam feed and provides real-time feedback on recognized faces (age, gender, emotion) and gestures (thumbs up or thumbs down). Fun animations are also triggered based on detected gestures!

**Features**

- **Face Detection**: Detect faces and analyze attributes such as age, gender, and emotion using DeepFace.
- **Gesture Detection**: Recognize gestures like "Thumbs up" and "Thumbs down" using MediaPipe.
- **Real-time Feedback**: Display recognized faces and gestures in real-time with animations (balloons for thumbs up, snow for thumbs down).
- **Customizable Detection Interval**: Adjust the frequency of face detection through the sidebar control.

# Real-Time Face and Gesture Recognition

This project is a real-time face and gesture recognition application using Streamlit, OpenCV, DeepFace, and MediaPipe. It allows you to detect faces and gestures from a webcam feed and provides real-time feedback on recognized faces (age, gender, emotion) and gestures (thumbs up or thumbs down). Fun animations are also triggered based on detected gestures!

## Features

- **Face Detection**: Detect faces and analyze attributes such as age, gender, and emotion using DeepFace.
- **Gesture Detection**: Recognize gestures like "Thumbs up" and "Thumbs down" using MediaPipe.
- **Real-time Feedback**: Display recognized faces and gestures in real-time with animations (balloons for thumbs up, snow for thumbs down).
- **Customizable Detection Interval**: Adjust the frequency of face detection through the sidebar control.

**Demo**

**Requirements**

To run this project, you need to install the following dependencies:

- `streamlit`: For building the interactive user interface
- `opencv-python`: For capturing and processing video streams
- `numpy`: For handling arrays and numerical computations
- `deepface`: For face analysis (age, gender, emotion detection)
- `mediapipe`: For gesture recognition
- `threading`: For handling video streams in separate threads
- `time`: For managing sleep intervals and cooldowns


**How to Run**

**1.) Clone the repository:**
bash
git clone
cd realtime-face-gesture-recognition

**2.) Install the dependencies:**
bash
pip install -r requirements.txt

**3.) Run the Streamlit app:**
bash
streamlit run app.py
The application will open in your web browser. Allow access to your webcam to start recognizing faces and gestures in real-time.

**Future Enhancements**

1.) Add more gesture types using MediaPipe
2.) Implement face recognition for identifying known individuals
3.) Improve gesture animation effects
4.) Optimize performance for low-end devices


**License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**For more such projects visit my Portfolio:- ** https://www.jaydugad.com/project

