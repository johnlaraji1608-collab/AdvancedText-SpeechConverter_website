# AdvancedText-SpeechConverter_website
# Advanced Text-to-Speech Converter

## Overview

Advanced Text-to-Speech Converter is a modern web application that converts written text into spoken audio using the browser's Speech Synthesis API. The application provides voice selection, speech customization, speech recognition, theme switching, and text management features.

## Features

### Text-to-Speech

* Convert text into speech
* Multiple voice options
* Language support based on available browser voices
* Adjustable speech rate
* Adjustable pitch
* Adjustable volume

### Speech Controls

* Speak text
* Pause speech
* Resume speech
* Stop speech

### Speech-to-Text

* Voice input using browser speech recognition
* Automatically converts spoken words into text

### Text Utilities

* Copy text to clipboard
* Clear text
* Download text as TXT file
* Word counter
* Character counter

### User Experience

* Responsive design
* Dark mode and Light mode support
* Save preferences using Local Storage
* Modern user interface

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* Web Speech API

  * SpeechSynthesis API
  * SpeechRecognition API
* Local Storage API

## Project Structure

```text
text-to-speech-converter/
│
├── index.html
├── style.css
├── script.js
├── README.md
│
└── assets/
    ├── images/
    └── icons/
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/text-to-speech-converter.git
```

2. Open the project folder.

3. Run the application by opening:

```text
index.html
```

No additional installation is required.

## Usage

1. Enter text into the text area.
2. Select a voice from the dropdown.
3. Adjust speech rate, pitch, and volume.
4. Click Speak to start speech.
5. Use Pause, Resume, or Stop controls as needed.
6. Use the microphone button to convert speech into text.
7. Download text or copy it to the clipboard.

## Browser Compatibility

| Browser | Support |
| ------- | ------- |
| Chrome  | Yes     |
| Edge    | Yes     |
| Firefox | Partial |
| Safari  | Partial |

For best results, use the latest version of Google Chrome or Microsoft Edge.

## Future Enhancements

* MP3 audio download support
* AI voice generation
* PDF text reader
* DOCX text reader
* Multi-language translation
* Voice cloning
* Progressive Web App (PWA)
* Cloud-based text-to-speech integration

## Limitations

The browser Speech Synthesis API cannot directly generate downloadable MP3 files. To support MP3 downloads, integration with cloud services such as Google Cloud Text-to-Speech, Azure Speech Services, or ElevenLabs is required.

## Author

Developed by: John Lara J I

## License

This project is licensed under the MIT License.
