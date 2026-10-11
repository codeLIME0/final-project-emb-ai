# Emotion Detector

An AI-based web application that detects emotions (anger, disgust, fear, joy,
sadness) in text using the Watson NLP library, served with Flask.

## Structure

- `EmotionDetection/emotion_detection.py` – `emotion_detector` function
- `EmotionDetection/__init__.py` – package definition
- `test_emotion_detection.py` – unit tests
- `server.py` – Flask web app
- `templates/index.html`, `static/mywebscript.js` – front end

## Run

```bash
python3 server.py
```

Then open the app on port 5000.

## Test

```bash
python3 -m unittest test_emotion_detection.py
```

## Lint

```bash
python3 -m pylint server.py
```
