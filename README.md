# multimodal-stress-detection
Python-based multimodal stress detection using facial expression and voice analysis.
# Multimodal Stress Detection System

A Python-based project that explores potential stress indicators using facial emotion analysis, voice-based sentiment analysis, and manually entered heart-rate information.

## Features

- **Facial Emotion Analysis:** Uses DeepFace to analyze facial expressions through a webcam.
- **Voice Analysis:** Converts spoken words into text using speech recognition.
- **Sentiment Analysis:** Uses TextBlob to analyze the sentiment of recognized speech.
- **Heart-Rate Input:** Accepts heart-rate information manually from the user.
- **Combined Stress Indicator:** Combines facial, voice, and pulse-related scores.
- **Live Camera Display:** Displays facial analysis and input status in a camera window.
- **CSV Report:** Saves analysis results to a CSV file.

## Technologies Used

- Python
- OpenCV
- DeepFace
- SpeechRecognition
- TextBlob
- NumPy
- Pyttsx3
- CSV

## Requirements

- Python installed on your computer
- Webcam
- Microphone
- Internet connection for Google's speech recognition service

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/Rithika-Kailasa/multimodal-stress-detection.git
```

### 2. Open the project folder

```bash
cd multimodal-stress-detection
```

### 3. Install the required libraries

```bash
pip install opencv-python SpeechRecognition textblob numpy pyttsx3 deepface
```

## How to Run

Run the Python file:

```bash
python "stressdetection code.py"
```

## Controls

| Key | Function |
|---|---|
| V | Capture voice input and analyze its sentiment |
| H | Enter heart-rate information manually |
| S | Save the analysis report to a CSV file |
| Q | Quit the application |

## How It Works

1. The webcam captures frames for facial emotion analysis.
2. The user provides voice input.
3. The recognized speech is analyzed using TextBlob.
4. The user enters heart-rate information manually.
5. The program combines the three scores into an overall indicator.
6. The application displays the result and a general suggestion.
7. The user can save the results in a CSV file.

## Future Improvements

- Develop a web-based interface.
- Improve the scoring method using validated data.
- Integrate automatic heart-rate measurement using a suitable sensor.
- Add charts and historical report visualization.
- Evaluate the system using appropriate datasets and metrics.

## Disclaimer

This project is intended for educational purposes. It estimates potential stress indicators and is not a medical diagnostic tool. The results should not be used to make medical decisions.

## Author

**Rithika Kailasa**

GitHub: [Rithika-Kailasa](https://github.com/Rithika-Kailasa)
