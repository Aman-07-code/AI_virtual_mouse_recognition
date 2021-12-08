# AI Virtual Mouse
Developed an AI-based approach for controlling the mouse movement using Python and openCV with real-time camera that detects hand landmarks, tracks gesture patterns instead of a physical mouse.

# Dependencies -

Please install all the required dependencies.

openCV - (For image processing and drawing)
mediapipe - (For Hand Tracking)
autopy - (For controlling the mouse movement and click)
numpy

# Project Description:

In this project, I am using my hand as a virtual mouse than can do everything that a mouse does without even touching your system. I am using the webcam of my system to detect my hands. It will then create a bounding box around my hand and focus on two fingers: The fore finger and the middle finger. The fore finger will act as a cursor and moving it around, we will be moving the cursor around. Now, inorder to successfully click using hand tracking, it is detecting the distance between the fore finger and the middle finger. If they are joined together, then it will perform a click.
