### AI Mouse using Hand Gesture Recognition

This Python script leverages OpenCV, Mediapipe, and PyAutoGUI to create an AI-powered virtual mouse controlled by hand gestures captured through a camera.

#### Features:
- **Hand Gesture Recognition**: Utilizes the Mediapipe library to detect and track hand landmarks in real-time video frames.
- **Virtual Mouse Control**: Translates hand movements into cursor movements on the screen, enabling users to control the mouse pointer by moving their hand.
- **Click Action Detection**: Recognizes specific hand gestures to perform mouse click actions, such as left-clicking, based on the relative positions of the index finger and thumb.

#### Usage:
1. **Setup**:  The required libraries (OpenCV, Mediapipe, and PyAutoGUI) are installed in your Python environment.
2. **Execution**: Run the script, and it will activate your computer's camera to capture hand movements. Move your hand in front of the camera to control the virtual mouse.
3. **Mouse Clicks**: Perform a pinch gesture (bringing index finger and middle finger close together) to simulate a mouse click action.

#### Requirements:
- Python
- OpenCV library
- Mediapipe library
- PyAutoGUI library
