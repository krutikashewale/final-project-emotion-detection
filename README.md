# Emotion Detection Application

A web-based AI application that detects emotions (anger, disgust, fear, joy, and sadness) from user input text using IBM Watson NLP Embeddable AI libraries and Flask.

## Overview
This project performs emotion detection on text statements using Watson NLP and determines the dominant emotion. The application is packaged as a reusable Python library and deployed as a web application using Flask.

## Features
- Real-time emotion analysis (Anger, Disgust, Fear, Joy, Sadness)
- Dominant emotion identification
- Packaged as `EmotionDetection` module
- Comprehensive unit testing with `unittest`
- Responsive Flask web interface
- Robust error handling for invalid or blank entries
- Clean code following PEP 8 guidelines (verified via Pylint with 10.00/10 score)

## Project Structure
- `EmotionDetection/`: Python package containing emotion detection logic
  - `__init__.py`: Package initialization and imports
  - `emotion_detection.py`: Emotion detection function connecting to Watson NLP
- `templates/`: HTML templates for the web interface
  - `index.html`: Web interface for emotion analysis
- `static/`: Static files (JavaScript)
  - `mywebscript.js`: Client-side request handler
- `server.py`: Flask web application server
- `test_emotion_detection.py`: Unit test suite
