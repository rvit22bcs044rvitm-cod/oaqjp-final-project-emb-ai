Final project
# Emotion Detection Application

This application analyzes the emotions expressed in text using the Watson Natural Language Understanding API.

## Features
- Detects emotions (anger, disgust, fear, joy, sadness) from user input.
- Identifies the dominant emotion.
- Includes robust error handling for empty or invalid inputs.

## Setup Instructions
1. Clone the repository.
2. Install the required dependencies: `pip install flask requests`
3. Run the application: `python3 server.py`
4. Access the application in your browser at `http://localhost:5000`

## Testing
Run the unit tests with: `python3 -m unittest test_emotion_detection.py`
