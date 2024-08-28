# Speech-Recognition-Web-Application
This repository contains a Flask web application that allows users to upload audio files and convert them to text using Google’s Speech Recognition API.

# Overview
The application provides a simple web interface where users can upload audio files. The uploaded audio is processed and transcribed into text using the SpeechRecognition library and Google’s Speech Recognition API.

# Features
- Web Interface: A user-friendly web interface for uploading audio files.

- Speech Recognition: Converts audio files to text using Google’s Speech Recognition API.

- Real-Time Processing: Processes and transcribes audio files in real-time.

# Installation
 1. Clone the repository:
    ```bash
    git clone https://github.com/cizodevahm/Speech-Recognition-Web-Application.git
    ```
2. Navigate to the project directory:
   ```baash
   cd Speech-Recognition-Web-Application
   ```
3. Install the required dependencies:
   ```bash
   pip install flask speech_recognition
   ```

# Usage
 1. Run the Flask application:
    ```bash
    python app.py
    ```
2. Open your web browser and navigate to ```http://127.0.0.1:5000/```.
3. Upload an audio file and click “Submit” to get the transcribed text.

# License
This project is licensed under the MIT License.
