
# Speech Recognition with Python

This project demonstrates speech recognition using various APIs in Python. It captures audio from the microphone and utilizes different speech recognition services to transcribe spoken words into text.

## Table of Contents

- Installation
- Usage
- Supported APIs
- Contributing

## Installation

To run the speech recognition script, follow these steps:

1. Ensure you have Python 3 installed on your system.
2. Install required dependencies using pip:

```bash
pip install SpeechRecognition pyaudio
```

3. Obtain API keys for the supported services mentioned in the script (e.g., Google Speech Recognition, Google Cloud Speech, Wit.ai, etc.).
4. Replace placeholder API keys in the script with your actual API keys.
5. Run the script:

```bash
python speech_recognition_script.py
```

## Usage

Once the script is running, it will prompt you to speak into the microphone. After capturing your audio, it will attempt to transcribe your speech using various speech recognition APIs.

Example usage:

```bash
python speech_recognition_script.py
```

## Supported APIs

This project supports the following speech recognition APIs:

- Sphinx
- Google Speech Recognition
- Google Cloud Speech
- Wit.ai
- Microsoft Bing Voice Recognition
- Microsoft Azure Speech
- Houndify
- IBM Speech to Text
- Whisper
- Whisper API (powered by OpenAI)

## Contributing

Contributions to this project are welcome! If you'd like to contribute, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/improvement`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/improvement`).
5. Create a new Pull Request.

