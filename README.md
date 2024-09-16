# Virtual Keyboard

A virtual keyboard application that uses hand gestures to input text. The application leverages MediaPipe for hand tracking and OpenCV for rendering the virtual keyboard and processing user inputs.

## Features

- Hand gesture-based text input.
- Virtual keyboard with keys and special buttons (Space, Delete).
- Real-time feedback and interaction.

## Prerequisites

Ensure you have the following installed:
- Python 3.x
- OpenCV
- MediaPipe

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/TOUZOUZ-Adnane/Virtual-Keyboard.git
2. Navigate into the project directory:
    ```bash
    cd Virtual-Keyboard
3. Create a virtual environment:
    ```bash
    python -m venv venv
4. Activate the virtual environment:
- On Windows:
   ```bash
   venv\Scripts\activate
- On macOS/Linux::
   ```bash
   source venv/bin/activate
5. Install the required Python libraries:
    ```bash
    pip install opencv-python mediapipe
## Usage
1. **Ensure that your webcam is properly connected.**
2. **Run the application:**
     ```bash
     python virtual_keyboard.py
3. Use the following hand gestures to interact with the virtual keyboard:

- **Input Text:**
  - Point to a key and press it by moving your hand downward.

- **Special Buttons:**
  - **Space:** Point to the "Space" button and press it by moving your hand downward.
  - **Delete:** Point to the "Delete" button and press it by moving your hand downward.

## Directory Structure

- `virtual_keyboard.py`: Main application script.

## Code Overview

- **Hand Tracking:** Uses MediaPipe to track hand landmarks and detect gestures.
- **Keyboard Rendering:** Renders the virtual keyboard and highlights the pressed keys.
- **Text Input:** Updates the displayed text based on key presses.

## Troubleshooting

- Ensure that your webcam is properly connected and accessible.
- Verify that all dependencies are correctly installed.
- If the application is not working as expected, check your webcam settings and ensure proper lighting conditions.

## Contact

For any issues or questions, please contact me via:

- Email: [adnane.touzouz.ta@gmail.com](mailto:adnane.touzouz.ta@gmail.com)
- LinkedIn: [Adnane Touzouz](https://www.linkedin.com/in/adnane-touzouz/)
