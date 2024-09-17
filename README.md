1. Project Title:

  Eye Blink and Iris Detection System

2. Project Description

  This project provides a real-time eye blink detection system using Eye Aspect Ratio (EAR) and a separate iris detection system with the ability to switch between left and right eye cameras. The project leverages OpenCV, dlib, and other computer vision techniques to track eye states and iris positions from webcam feeds.

3. Features:

  Eye Blink Detection: Detects whether the eyes are open or closed using the EAR method and facial landmarks.

  Iris Detection: Detects the iris position in both left and right eyes using the Hough Circle Transform.

  Camera Switching: Allows switching between two cameras for left and right eye monitoring.

  Real-Time Detection: Processes video frames in real-time to provide continuous feedback.

4. Technologies Used

  OpenCV: For capturing video frames and image processing.

  dlib: For facial landmark detection.

  NumPy: For handling array operations and mathematical calculations.

  SciPy: For calculating Euclidean distance in the EAR calculation.

5. Installation

  To set up and run this project, follow these steps:

  Prerequisites

  Python 3.x

  Required packages:

  OpenCV (opencv-python)

  dlib

  NumPy

  SciPy


Setup

  1. Clone the repository:

  git clone https://github.com/your-username/your-repository.git

  2. Install the dependencies:

  pip install opencv-python dlib numpy scipy

  3. Download the dlib shape predictor model file:

  shape_predictor_68_face_landmarks.dat can be downloaded from this link. Extract it and place it in the appropriate directory
