# Emotion Detector

An AI-based web application that detects emotions in text using the Watson NLP Emotion Predict API. Built with Python and Flask.

## What it does
Takes a sentence and returns scores for anger, disgust, fear, joy, and sadness, plus the dominant emotion. Blank input returns a clear error message.

## Project structure
- `EmotionDetection/` - Python package with the `emotion_detector` function
- `server.py` - Flask web app
- `test_emotion_detection.py` - unit tests
- `templates/` and `static/` - web interface

## Run it
- `python3 test_emotion_detection.py` runs the unit tests
- `python3 server.py` starts the app on port 5000

Note: the Watson endpoint is reachable from the IBM Skills Network lab environment.# Repository for final project
