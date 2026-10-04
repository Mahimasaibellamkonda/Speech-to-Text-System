# Speech-to-Text System

A web-based Text and Speech Analysis application that converts spoken language into written text using the browser's built-in Speech Recognition capability.

## Features

* Converts speech into text in real time
* Uses the device microphone
* Start and stop speech recognition
* Displays recognized speech in a text area
* Clear the generated text
* Simple and responsive web interface
* No separate audio-processing server is required

## Technologies Used

* Python
* Flask
* HTML5
* CSS3
* JavaScript
* Web Speech API

## Project Structure

```text
Speech-to-Text-System/
│
├── app.py
├── requirements.txt
├── README.md
│
├── templates/
│   └── index.html
│
└── static/
    └── style.css
```

## Installation

Open a terminal inside the project folder and run:

```bash
pip install -r requirements.txt
```

## Running the Application

Run:

```bash
python app.py
```

The application will start at:

```text
http://127.0.0.1:5000
```

Open the address in a supported web browser.

## How It Works

1. The Flask application loads the web interface.
2. The user clicks the "Start Recording" button.
3. The browser requests access to the microphone.
4. The Web Speech API processes the user's speech.
5. Recognized speech is converted into text.
6. The generated text is displayed in the text area.
7. The user can stop recording or clear the generated text.

## Example

### Spoken Input

```text
Natural Language Processing is used in many applications.
```

### Generated Text

```text
Natural Language Processing is used in many applications.
```

## Applications

Speech-to-text technology can be used in:

* Voice assistants
* Lecture transcription
* Meeting transcription
* Accessibility applications
* Voice-based search
* Dictation systems
* Customer support systems
* Note-taking applications

## Advantages

* Easy to use
* Real-time transcription
* No additional Python speech-recognition package is required
* Uses the browser's speech recognition capability
* Simple architecture

## Limitations

Speech recognition support depends on the browser and device. Recognition accuracy can also vary depending on pronunciation, background noise, microphone quality, and language settings.

The current application is configured for English using the `en-US` recognition language.

## Purpose

This project demonstrates the practical application of Speech Processing and Natural Language Processing by converting human speech into machine-readable text through a web interface.

## Author

B.E. CSE Student
