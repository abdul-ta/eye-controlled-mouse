Eye Controlled Mouse
Overview
The Eye Controlled Mouse project enables hands-free mouse navigation by leveraging eye movements. This application utilizes Python along with several powerful libraries: OpenCV for real-time image processing, MediaPipe for facial landmark detection, and PyAutoGUI for simulating mouse actions. By tracking specific facial landmarks, the application allows users to control their computer’s cursor simply by moving their eyes.

Features
Real-Time Eye Tracking: Utilizes your webcam to detect and track eye movements in real time.
Cursor Control: Moves the mouse cursor based on the position of your eyes, providing an intuitive hands-free experience.
Click Simulation: Detects when the user blinks to simulate a mouse click, enhancing interaction without the need for a physical mouse.
Installation
To run this project, you will need to have Python installed on your machine along with the required libraries. Follow the steps below to set up your environment:

Clone the repository:


https://github.com/abdul-ta/eye-controlled-mouse.git
cd eye-controlled-mouse
Install the required libraries:

You can install the necessary libraries using pip:


pip install opencv-python mediapipe pyautogui
Usage
Run the application:

Execute the following command in your terminal:


python eye_controlled_mouse.py
Webcam Setup: Ensure your webcam is active and positioned to capture your face clearly.

Control the Cursor: Use your eyes to navigate the mouse cursor on the screen. The cursor will move according to the detected eye position.

Simulate Clicks: Blink your eyes to simulate mouse clicks. The application detects the vertical position of the eyes to determine clicks.

Key Controls
Press 'q': Exit the application.
Limitations
Lighting Conditions: Performance may vary based on the lighting in your environment. Ensure adequate lighting for optimal detection.
Webcam Quality: The accuracy of eye tracking can be affected by the quality of the webcam being used.
Calibration: Some users may need to adjust their positioning or the application settings for optimal performance.
Contributing
Contributions are welcome! If you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request. Your feedback helps improve the project!



Contact
For any questions or inquiries, please reach out via [(https://github.com/abdul-ta)].
